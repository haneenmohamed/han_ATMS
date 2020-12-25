First of all , 

Go to the Db file and install it on phpmyadmin
after that

Please go to this path

han_hr\application\config


you will find


$db['default'] = array(
    'dsn'   => '',
    'hostname' => 'localhost',
    'username' => 'onoostor_hr1',
    'password' => 'Hh102030+++',
    'database' => 'onoostor_hr1',
    'dbdriver' => 'mysqli',
    'dbprefix' => '',
    'pconnect' => FALSE,
    'db_debug' => (ENVIRONMENT !== 'production'),
    'cache_on' => FALSE,
    'cachedir' => '',
    'char_set' => 'utf8',
    'dbcollat' => 'utf8_general_ci',
    'swap_pre' => '',
    'encrypt'  => FALSE,
    'compress' => FALSE,
    'autoinit' => TRUE,//ci version 2.x
    'stricton' => FALSE,
    'failover' => array(),
    'save_queries' => TRUE
);
 

please change the db info and the link of your server
