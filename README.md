# Avalon Media System
[Avalon Media System](http://www.avalonmediasystem.org) is an open source system for managing large collections of digital audio and video. The project is led by the libraries of [Indiana University](http://www.iu.edu) and [Northwestern University](http://www.northwestern.edu) with funding in part by a three-year National Leadership Grant from the [Institute of Museum and Library Services](http://www.imls.gov).

For more information and regular project updates visit the [Avalon blog](http://www.avalonmediasystem.org/blog).

# Installing Avalon Media System
Instructions on how to get a local installation of Avalon Media System installed on your system are available for [Linux](https://wiki.dlib.indiana.edu/display/VarVideo/Getting+Started+(Linux\)) and [OS X](https://wiki.dlib.indiana.edu/display/VarVideo/Getting+Started+(OS+X\)).

# Getting started
* ```git submodule init```
* ```git submodule update```
* Install [Mediainfo cli](http://mediainfo.sourceforge.net)
* Copy config/avalon.yml.example to config/avalon.yml and [change](https://wiki.dlib.indiana.edu/display/VarVideo/Configuration+Files#ConfigurationFiles-config%2Favalon.yml) as necessary
* ```rake db:migrate```
* ```rake db:test:prepare```
* ```rake spec```
* ```rake avalon:services:start```
* ```rails s```