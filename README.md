# MeteoBox

Table of Contents
-----------------

* [Overview](#overview)
* [Requirements](#requirements)
* [About data format](#METAR-and-TAF-data-formats)
* [Data sources](#sources)
* [ToDo](#todo)


Overview
--------

**MeteoBox** is a web component for (Seaside)[http://www.seaside.st] framework.
The main goals of this little project are:

1. Choose a airport meteo station (by example, ELBG) and displaying in realtime the meteo observations in a web page 
2. Based on regulary and officialy updated METAR notices
3. Apply a style to the info box
4. With cosmetic toys like smart icons, etc.
5. Forecasts (Must have).

**Note : **This repository (and eventually the website) is currently working in progress, so don't be too bad with the content but constructive. If you have remarks, suggestions, code or anything else, please share it.

Requirements
------------
TBC

METAR and TAF data formats
--------------------------

* Some informations about METAR Structure : [http://weather.unisys.com/wxp/Appendices/Formats/METAR.php](http://weather.unisys.com/wxp/Appendices/Formats/METAR.php)
* Another good Wikipedia reference : [https://fr.wikipedia.org/wiki/METAR] (https://fr.wikipedia.org/wiki/METAR)

Sources
-------

* Official observations repository : [http://tgftp.nws.noaa.gov/data/observations/metar](http://tgftp.nws.noaa.gov/data/observations/metar)
* Most recent stations list : [https://www.aviationweather.gov/docs/metar/stations.txt](https://www.aviationweather.gov/docs/metar/stations.txt)
* Stations and locations : [https://www.aviationweather.gov/docs/metar/sao.cty](https://www.aviationweather.gov/docs/metar/sao.cty)


Todo
----

* [ ] Api for app (REST mode).
* [ ] Store each request into database.
* [ ] Add session managment.
* [ ] Documentation.
