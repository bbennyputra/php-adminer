```
/** Adminer - Compact database management
* @link http://www.adminer.org/
* @author Jakub Vrana, http://www.vrana.cz/
* @copyright 2007 Jakub Vrana
* @license http://www.apache.org/licenses/LICENSE-2.0 Apache License, Version 2.0
* @license http://www.gnu.org/licenses/gpl-2.0.html GNU General Public License, version 2 (one or other)
* @version 4.2.2
*/
```
## System installation
```
apt-get update & apt-get upgrade
apt-get install php5-curl php5-sqlite php5-cli

apt-get install git
git clone https://github.com/intrd/php-adminer/
```
## Directory structure
Follow this sample structure..
```
|_Your_project_directory
 |_index.php //index of your project including php-adminer/adminer.php
 |_php-adminer //this cloned directory

