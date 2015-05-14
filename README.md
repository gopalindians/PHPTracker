# PHPTracker 0.3.0
[![Build Status](https://img.shields.io/travis/tcz/PHPTracker.svg?style=flat-square&branch=master)](https://travis-ci.org/tcz/PHPTracker)

PHPTracker is a library which makes it easy to create your own private file distribution system using the BitTorrent protocol. There are libraries here which can provide a simple tracker, seed a torrent and download a torrent as well.

**PLEASE NOTE:** If you forked this project before the 8th May 2015, you may have some problems contributing. This is because previously the master branch contained the unstable, and API breaking v0.4.0 development stream which is very much in a state of flux. From herein, the master branch will always refer to the most recent, stable version of PHPTracker.


## Examples
For examples see example_*.php or check [http://php-tracker.org/]

If you want to use the MySQL persistance object, see mysql.sql for the table structure.

## Contributing
Contributions are welcomed and encouraged. To get started, fork the repository and create your own feature branch. Inside this branch create all the changes and fixes you'd like to see get added to PHPTracker.

If your commits change existing functionality, or add new functionality, please be sure to provide sufficient tests to cover your code and make sure they pass.

### Running Tests

Tests can be run with PHPUnit, see phpunit.xml for bootstrap configuration.

## Bleeding Edge
Version 0.4.0 is the current development version and can be found in the develop branch. 

## Licence
Licence is BSD 3 Clause. Please see the licence file for more information.
