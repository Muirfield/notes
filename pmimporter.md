# pmimporter

- tracking source for imported stuff?
 

## Adding LevelDB support


Compile using latest php compile script

Iterate over leveldb to generate regions. Return regions. 

Fork and read chunk Dara's

<?php

$db = new LevelDB("/path/to/leveldb-test-db");
$it = new LevelDBIterator($db); // equals to： $it = $db->getIterator();

// Loop in iterator style
while($it->valid()) {
    var_dump($it->key() . " => " . $it->current() . "\n");
}

// Or loop in foreach
foreach($it as $key => $value) {
    echo "{$key} => {$value}\n";
}


