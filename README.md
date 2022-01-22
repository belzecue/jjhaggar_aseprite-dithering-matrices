# Aseprite Dithering Matrices

This is an Aseprite [extension](https://github.com/aseprite/aseprite/tree/master/data/extensions) I made after reading [this post](https://community.aseprite.org/t/new-pattern-fill/1627), it's under [MIT License](LICENSE.txt).


### How to install ###

First of all, download the latest version of this extension. You can do that by clicking on _**Download Repository**_ from [here](https://bitbucket.org/jjhaggar/aseprite-dithering-matrices/src/). That will let you download a .zip file of the complete repository (which will also work as an Aseprite extension).
![imgs/howto_download.png](imgs/howto_download.png)

After that, you have two options:

1.  Use _Edit > Preferences > Extensions > Add Extension_ and select the .zip (this is recommended because then you can _Uninstall_ the extension from the same dialog)
2.  Or you can uncompress the .zip file in a subfolder of the `extensions` folder e.g. `Aseprite/data/extensions/myextension`), this is what the _Add Extension_ button does from the UI (+ creates an extra file for uninstallation)


### How to create more dithering matrices ###

If you want to experiment and create more dithering matrices, you can create an extension (a .zip file or a directory) with a content similar to [this one](https://github.com/aseprite/aseprite/tree/master/data/extensions/bayer-matrices).

(TO-DO: add more instructions in the future)