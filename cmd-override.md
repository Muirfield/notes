# Command Override

You want to override the `tell` command, that has also the `w` and `msg` aliases by default.
The class that will override these commands is MyTellCommand (extends PluginCommand).


To do this, you've to set the original command in a state that allows it to be overriden.
Also, aliases will be registered directly, but since all the work was done for the first registration, it's pretty simple.


    //We are in the context of a plugin
    
    $commandMap = $this->getServer()->getCommandMap();
    $commandToOverride = $commandMap->getCommand("tell");
    $commandToOverride->setLabel("tell_disabled");     //This prepares the command for the next step, setting up the Command->nextLabel
    $commandToOverride->unregister($commandMap); //This changes the current label
    
    //Now, we can register our command.

    $command = new MyTellCommand($this);
    $commandMap->register("myfallbackprefix", $command);
    
    //And the aliases
    $commandMap->register("myfallbackprefix", $command, "w");
    $commandMap->register("myfallbackprefix", $command, "msg");


