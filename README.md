<p align="left">  <img src="https://raw.githubusercontent.com/piccolomo/plotext/master/images/logo.png" /></p>

`plotext` plots **directly on terminal**
- it allows for [scatter](https://github.com/piccolomo/plotext/blob/master/readme/basic.md#scatter-plot), [line](https://github.com/piccolomo/plotext/blob/master/readme/basic.md#line-plot), [bar](https://github.com/piccolomo/plotext/blob/master/readme/bar.md#simple-bar-plot), [histogram](https://github.com/piccolomo/plotext/blob/master/readme/bar.md#histogram-plot) and [date-time](https://github.com/piccolomo/plotext/blob/master/readme/datetime.md#datetime-plot) plots (including [candlestick](https://github.com/piccolomo/plotext/blob/master/readme/datetime.md#candlestick-plot)),
- it can also [plot images](https://github.com/piccolomo/plotext/blob/master/readme/image.md#image-plot) (including [GIF](https://github.com/piccolomo/plotext/blob/master/readme/image.md#gif-plot)) and [stream video](https://github.com/piccolomo/plotext/blob/master/readme/video.md#video-plot) with audio (including [YouTube](https://github.com/piccolomo/plotext/blob/master/readme/video.md#play-youtube)),
- it has **no dependencies** (except for optional dependencies for image/video plotting),
- it provides a simple [command line tool](https://github.com/piccolomo/plotext/blob/master/readme/utilities.md#command-line-tool),
- it can [save plots](https://github.com/piccolomo/plotext/blob/master/readme/utilities.md#useful-functions) as text or as colored `html`,
- it provides a tool to [color strings](https://github.com/piccolomo/plotext/blob/master/readme/utilities.md#colored-text).

![subplots](https://raw.githubusercontent.com/piccolomo/plotext/master/images/subplots.png)
image code [here](https://github.com/piccolomo/plotext/blob/master/readme/subplots.md).


## Install
- `pip install plotext` for normal installation,
- `pip install plotext --upgrade` to upgrade to the latest version,
- `pip install "plotext[image]"` to install the optional dependency for **image plotting** (including GIFs),
- `pip install "plotext[video]"` to install the optional dependencies for **video rendering**, which will also allow to plot images.
- the optional packages are `pillow` (for image plotting), `opencv-python` (for video rendering), `ffpyplayer` (to stream audio), and `pafy` and "youtube-dl"(to stream YouTube),
- `pip install git+https://github.com/piccolomo/plotext`, if you feel courageous, to install the [GitHub version](https://github.com/piccolomo/plotext), if more updated.


## Guide

#### Main Plots
- [Basic Plots](https://github.com/piccolomo/plotext/blob/master/readme/basic.md)
- [Bar Plots](https://github.com/piccolomo/plotext/blob/master/readme/bar.md)
- [Datetime Plots](https://github.com/piccolomo/plotext/blob/master/readme/datetime.md)
- [Other Plots](https://github.com/piccolomo/plotext/blob/master/readme/other.md)

#### 2D Plots
- [Image Plots](https://github.com/piccolomo/plotext/blob/master/readme/image.md)
- [Play Videos](https://github.com/piccolomo/plotext/blob/master/readme/video.md)

#### Plotting Utilities
- [Settings](https://github.com/piccolomo/plotext/blob/master/readme/settings.md)
- [Aspect](https://github.com/piccolomo/plotext/blob/master/readme/aspect.md)
- [Subplots](https://github.com/piccolomo/plotext/blob/master/readme/subplots.md)

#### Other Resources
- [Utilities](https://github.com/piccolomo/plotext/blob/master/readme/utilities.md)
- [Environments](https://github.com/piccolomo/plotext/blob/master/readme/environments.md)
- [Notes](https://github.com/piccolomo/plotext/blob/master/readme/notes.md)