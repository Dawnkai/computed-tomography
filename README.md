# CT image reconstruction
This repository contains the algorithm used for reconstructing Computer Tomography images.
Everything has been enclosed in the Jupyter Notebook (CT Image Reconstruction.ipynb). If you do not have Jupyter Notebook, you can view the html output which works...
as long as you have a web browser.

You can see the results here:
![alt text](https://github.com/Dawnkai/computed-tomography/blob/main/result.png)

The project uses **parallel ray** model, [Bresenham's line algorithm](https://en.wikipedia.org/wiki/Bresenham%27s_line_algorithm), [Backprojection](http://xrayphysics.com/ctsim.html)
and [Convolution](https://en.wikipedia.org/wiki/Convolution).

The project uses the Jupyter Notebook for Markdown functionality so that I can explain every algorithm step in detail for anyone who wishes to learn CT image reconstruction.
Required libraries are available in the `requirements.txt` file (only numpy and scikit-image, which can be replaced with opencv library).

Algorithm steps (Radon transform and Bresenham's algorithm) are done manually, no premade libraries.

The project was done in collaboration with [Sopczasty](https://github.com/Sopczasty).
