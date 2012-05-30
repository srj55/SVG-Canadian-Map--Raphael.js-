SVG-Canadian-Map--Raphael.js-
=============================

SVG Canadian map, with plotable lat,lng. made with Raphael.js

Requirements:

* [Raphael](http://raphaeljs.com/)
* [gRaphael](http://g.raphaeljs.com/) - just for the mouseover tags
* [ScaleRaphael](http://www.shapevent.com/scaleraphael/) - the scalability

Usage:

    var yourIntendedMapWidth = 600;
    var container = 'dom-id-of-your-container-div';
   
    var paper = new ScaleRaphael(container, 950, 650);
    var map = paper.CDNMap();
    paper.scaleAll(yourIntendedMapWidth/map.width);
   
    map.plot(43.6481,79.4042, "Toronto ON");
    map.darkenprovince('ON', 0.07);


## Credits

* this project is based on: https://github.com/the55/usmap