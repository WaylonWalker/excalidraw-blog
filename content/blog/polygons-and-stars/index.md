---
title: How to use the library; Polygons and Stars
date: 2020-11-26
author: Lipis
link: https://twitter.com/lipis
---

What makes Excalidraw so great is the simplicity and of course we don't want to start adding more and more features, as this simplicity will be lost. What we can do though is to make use of one of our latest and very powerful feature: **the library**.

<!-- end -->

![Excalidraw Library](library.png)

The first implementation of the library was made by [Pete Hunt](https://github.com/excalidraw/excalidraw/pull/1787) a few months back. So by now you might already know how you can start adding shapes to the library, that you use often for later use in different diagrams (press `9` or shoose it from the top menu). Afterwards you can export it and share with others or open an existing library that you found somewhere else.

Another way to import is to upload your library somewhere (like [gist](http://gist.github.com/)) and then by getting the direct link to the raw file you can use that URL to add the shapes directly into your library like this:

```
https://excalidraw.com/?addLibrary=<link-to-excalidrawlib>
```

### Polygons and Stars example

As an example you can add [polygons](https://excalidraw.com/?addLibrary=https://gist.githubusercontent.com/lipis/c148134151ac57b7f5df62cba69a4ee4/raw/a52fa9df8fc892e0a63d48aa6f3645299922bcc2/polygons.excalidrawlib) or [stars](https://excalidraw.com/?addLibrary=https://gist.githubusercontent.com/lipis/a0de24a467a2869ed45635fa976afdcf/raw/ace7e402f7b0e48dc6738ddac6b5e6608b2aa7d4/stars.excalidawlib) directly into your library and modify them as you need.

Here is how they look, what is going to be imported and as awlays you can click the images to open them directly in Excalidraw.

https://excalidraw.com/#json=5666429063921664,h0yDjfkDndzI10H-OnNEcA

https://excalidraw.com/#json=5394737318068224,XZC0jx3WBYiFI6mcGofmIQ

These shapes were automatically generated using Python with tht help of the Excalidraw lib. Checkout the source of [`polygons.py`](https://github.com/excalidraw/excalidraw-playground/blob/master/excalidraw/polygons.py) and [`stars.py`](https://github.com/excalidraw/excalidraw-playground/blob/master/excalidraw/stars.py) if you are interested on how they were done. Feel free to experiment with different shapes.
