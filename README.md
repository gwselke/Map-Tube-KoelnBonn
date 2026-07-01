A Map::Tube implementation for the Köln/Bonn (Cologne/Bonn) U- and S-Bahn and tramway.

This module allows to find the shortest route between any two given tube
stations in Köln and Bonn. Underground, tramway, and S-Bahn lines
are covered for the wider Köln-Bonn area (VRS).

All interesting methods are provided by the role L<Map::Tube>.

To build this module, use the classical steps:

* perl Makefile.PL
* make
* make test
* make install

(If you are using Srawberry Perl under Windows, you may want to replace "make"
with "gmake".)
