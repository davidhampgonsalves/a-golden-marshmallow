# A Golden Marshmallow
Animation of a golden marshmallow I made in opentoonz b/c their wasn't a single one on the internet and it was impeding my ability to communicate this concept.

<img src=https://github.com/davidhampgonsalves/a-golden-marshmallow/raw/main/marsh.gif />

https://giphy.com/gifs/transparent-xdM9c3eH2GWrQdQWse.

`ffmpeg -framerate 30 -i 'marsh.%04d.tif' -cr 0 marsh.mp4`

`convert -dispose previous -loop 0 -delay 6.66 "*.tif" marsh.gif`
