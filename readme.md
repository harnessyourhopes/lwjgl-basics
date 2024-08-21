_lwjgl-basics_ is a minimal shader-based library for 2D LWJGL sprite games. It provides essential utilities for handling textures, shaders, and sprite rendering.

For a large game project, a platform like [LibGDX](https://libgdx.com/) may be more suitable.

The [source code](https://github.com/mattdesl/lwjgl-basics) is hosted on GitHub.

### OpenGL & Shader Tutorials

Check the Wiki tab for various OpenGL and GLSL tutorials.

### Installing the API

The best way to install the API is to use Eclipse and EGit (or another IDE with Git support) to pull the most recent source code. Included in the `lib` and `native` folder is a distribution of LWJGL 2.8.5, as well as an Eclipse project with class path set up for you. You can download newer versions of LWJGL from their [downloads page](http://lwjgl.org/download). 

Alternatively, you can download the full library as a ZIP:

![ZIP](http://i.imgur.com/Dkvp0.png)

Then, simply open the Eclipse project to start testing. Ensure your LWJGL JARs and natives have been set correctly in [IntelliJ Idea](https://github.com/LWJGL/lwjgl3-wiki/wiki/1.2.-Install#intellij-idea), [NetBeans](https://github.com/LWJGL/lwjgl3-wiki/wiki/1.2.-Install#netbeans) or [Eclipse](https://github.com/LWJGL/lwjgl3-wiki/wiki/1.2.-Install#eclipse), and include lwjgl-basics as a class library. lwjgl-basics also uses PNGDecoder.jar as a dependency, which can be downloaded [here](https://web.archive.org/web/20130920035443/http://twl.l33tlabs.org/textureloader/).

See the [tests](https://github.com/mattdesl/lwjgl-basics/tree/master/test/mdesl/test) package to get started with some basic examples.


### Credits

- PNG decoder by Matthias Mann
- [PT Font](http://www.fontsquirrel.com/fonts/PT-Sans)
- [Grass & Water Tileset](http://opengameart.org/content/grass-and-water-tiles)
- [Tiling textures](http://opengameart.org/content/tilling-textures-pack-33)
- [2D Game Scene](http://opengameart.org/content/grassland-tileset)
- Code written by Matt DesLauriers (aka: davedes or mattdesl) unless otherwise stated.
