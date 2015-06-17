Exploring a 24-hours watch face.

 - 24 hours dial
 - single hand watch
 - date
 - location-relevant dusk and noon
   (thanks to excellent [Sunrise-Sunset API](http://sunrise-sunset.org/api),
 - using processingjs, jquery, navigator.geolocation, window.localStorage
 - licensed under GPL v2

There are a few options to tweak in the header:

```
int SHOW_12 = 1;
int SHOW_ROMAN = 0;
int SHOW_ALL_HOURS = 1;
int SHOW_TOP_0 = 0;
int SHOW_NIGHTTIME = 1;
int TH_IX = 1;
```

TODO:

 * code cleanup
 * experience this a bit, let it sink
 * investigate this with SVG instead
 * animations

Notes:

 - https://maxwellito.github.io/vivus/
 - http://svgjs.com/
 - https://en.wikipedia.org/wiki/24-hour_analog_dial
 - https://en.wikipedia.org/wiki/24-hour_clock
