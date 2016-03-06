# Matplotlib HTML5 Canvas Backend #

This provides a web-delivered interactive matplotlib backend using HTML5 technologies including [WebSocket](http://en.wikipedia.org/wiki/WebSocket) and the [Canvas](http://en.wikipedia.org/wiki/Canvas_element) element.

Our main goal is to have a backend that is consistent across multiple platforms, has few installation dependencies, is easy and fast to animate, and retains compatibility with current matplotlib usage scenarios.

Installation instructions can be found below or on the project's [Wiki](http://code.google.com/p/mplh5canvas/wiki/Installation) page. The short answer:

```
easy_install mplh5canvas
```

# Features #

  * Pure Python
  * Uses mod\_pywebsocket to provide multi-browser support through multiple websocket standards
  * Requires up-to-date web browser with Canvas and WebSocket support (since the start of 2013 the latest versions of all major browsers should work out of the box - see [Wiki](http://code.google.com/p/mplh5canvas/wiki/Installation) page for more details)
  * Designed with animation and interactivity in mind (resizable, zoomable, clickable regions, etc)
  * Simple plots (e.g. a 2048-point line plot) can be animated at around 60 frames per second
  * Allows proper remote access to plots
  * Allows multiple concurrent access to plots
  * Thumbnail window allows quick cycling between plots on a single page


![http://mplh5canvas.googlecode.com/files/screenshot.png](http://mplh5canvas.googlecode.com/files/screenshot.png)