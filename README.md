# Fractalmakufu

Inspired by [Recursive PowerPoint Presentations [Gone Fractal!]](https://www.youtube.com/watch?v=b-Fa6HtvGtQ) on Matt Parker's YouTube channel.

This Danmakufu script allows you to do a fractal-ish animation of a 512x512 image by utilizing Render Targets in Danmakufu. 

See `script/main/main.dnh` for the source code.

The toggleable parameters are:

* `WAITPERIOD` - frames between updates
* `RESEED_PERIOD` - how long before the animation resets (note that two cycles are performed each iteration)
* `NUM_HORIZ` - number of horizontal repetitions
* `NUM_VERT` - number of vertical repetitions
* `IMAGENAME` - Image to use as source
