# Interactive_Image_Viewer_GUI_Python

![alt tag](https://raw.githubusercontent.com/cpoetter/Interactive_Image_Viewer_GUI_Python/master/Screenshot.png)

The interactive 2D Image Viewer is a small GUI which displays 16 bit Numpy arrays. After initiating an instance of the GUI class a spereate process is lunched to enable a fluent and uninterrupted user facing experienct, while simultaniously running heavy calculations in the main python file. The second process is every time in communication with the calling file over a queue. Images, text or commands can be pushed to the viewer. The Viewer itself can be described as interactive. The user can scroll back in the images history, change contrast and brightness, and start and stop autoviewing.
