=== Plugin Name ===

Bath OUE block
Author:Hittesh Ahuja
Requires at least: Moodle 2.2 
License: GPLv2 or later
Copyright : University of Bath 2015
License URI: http://www.gnu.org/licenses/gpl-2.0.html

== Description ==

This is an Unit Evaluation Block built for the University of Bath's Moodle VLE.
It displays a block and a notification bar for users who have unit evaluations pending.

== Prerequisites ==

OCI8 plugin to connect to SITS
SITS credentials stored in config.php for e.g,
//SITS plugin config
define('SITS_DB_USER', 'dbuser');
define('SITS_DB_PASS', 'yoursecretpassword');
define('SITS_DB_NAME', 'host/dbname');

== Installation ==

1. Place the bath_oue under the 'blocks' folder of your Moodle installation.
2. Make sure the SITS specific functions,variables and SQL scripts are in the sits.final.class.php and sits_db.abstract.class.php
3. Install the plugin by going to the ADMIN section
4. Once installed, make sure you set the Global Error Msg under the plugin settings

== Usage ==

Once installed successfully,if the block is not available by default(this can be done by changing the config.php file under root folder), make sure the block is added to the root 'Home' page.

Enjoy!
