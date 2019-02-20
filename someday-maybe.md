# Muirfield Someday/Maybe


## ItemCasePE

## GrabBag

## SimpleAuthHelper

## KillRate

## LiveSigns

- Split the text generation from text use
- FloatingText in all worlds
- Rcon to grab the output of a command and display it
- youtube channels
- permissions?

## libcommon

- persistent sessions
- Generic session class + persistent support
- extended item names OK? -- enhance BasicHUD

## GoldStd

- @iVertx : decouple ChestInventory menu from NPC
     - Shopping by Command
     - Shopping by ChestShop

## MagicTelePortal

- list portals
- delete portals
- gc - delete portals definitions in non-existing worlds

## SignWarp

- Add FTServer support
- Add Warps

## WorldProtect


## Scorched

* Re-factor?
* Fire multiple arrows in one shot
* Fire arrows
* rewrite documentation
* @CaptainKenji17 : SnowBall grenade (tnt without destroying blocks?)
* wtf is magic stick?
So you'll need stick to use the magic

the plugin is about a magical arm and to use you will just shoot with stick and the shooting control is same as snowball .

Ex:
*Player holds screen to shoot*

And once he shoot the thing will appear is arrow with enchanted particle (not critical) and once that stick hits a block itll explode with many particles and once that explosion hits player the player gets nausea 5 sec and thr potion which player gives damage and that's 5 sec as well


you can config on config.yml if you want the explosion explode like tnt (break blocks or not)

and and im not done
once that arrow directly hits player that player will being trhow far away like knockback 1000 level and after that he will explode. (with out breaking blocks)

and the stick you can only use it 1x per 10 second. once you used stick itll turns to bone, after 10 second the stick will return and ready to shot peoples again :)


## NetherChest


## ToyBox

   - Ladder when stick taps
   - Toy box sneaking sponge. 
public function onTouch(PlayerInteractEvent $e){
$p = $e->get player();
$it = $e->getItem();

if($it->getID() === 345){//Compass
 
   $p->setDataFlag(Entity::DATA_FLAGS, Entity::DATA_FLAG_SNEAKING, true);

  }elseif($it->getID() === 0){//Air
$p->setDataFlag(Entity::DATA_FLAGS, Entity::DATA_FLAG_SNEAKING, false);

}

## FireBlade

Rename to MagicBlades:

  - Fireblade - causes damage, sets player on fire and starts fires .  GIves fire protection
  - Frostblade - freeze player
  - Wolverine - heals player over time
  - Summoner - summons wolves that attack target ... wolves only last for 60 seconds or until enemy dies....
  - KarmicBlade - when player suffers damage, opponent also takes damage.
  - berserker -   - deal damage to all nearby entities
  - Soul Stealer - Deal damage and you get healed (can we identify zombies?)
  - Rogue Wave - Deal damage and steals items
  - Water Blade - Protects from fire i.e. if lit on fire will put fire out, breath underwater
  - Tyson Blade - Super knock back that causes damages and breaks stuff
  - null blade - reverses effects of all blades
  - knockout blade - half the opponents health in one blow (will not kill though... but cause knocback)
  - apocalypse blade - knockbacks opponent and causes an explosion where they land
  - immortal blade - you suffer damage but don't die (you always stay 1/2 heart)
  - voodoo blade - kill villager raises a zombie, kill zombie raised a villager?

* Activate by double tap
* Need to have the two swords and they are switched from hand to inventory

- Iron, Wooden, Stone, Diamond, Gold
- Axe, PickAxe, Sword, Shovel, Hoe

## Mobsters

## BasicHUD

- add item held ID and name to vars
- option to disable item name. 
- vars: update to KillRate v2.0.0 API
- support for extended item names
- vars: update to add PurePerms group

## Others

- Create a form for crash archive:
  - [Crash Archive](http://crash.pocketmine.net/search)

