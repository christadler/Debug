# Background Image won't display
*Test Repository for debugging*

I have problems displaying background images in Jupyter Notebooks (defined with `<div style='background-image: url("title01.jpg")>Text</div>`).

Please open this with binder/notebook and binder/lab and compare:

Binder/notebook: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christadler/Debug/HEAD?filepath=Test.ipynb)

Binder/lab: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/christadler/Debug/HEAD?labpath=Test.ipynb)


**Ex. (1) will display only in binder and only if you open binder in notebook style**. It won't show in "lab" nor on our local jupyterhub installation. The path to the image is right, it shows up if I just include it via markdown (Ex. 2), `<img>`-tag (Ex. 3) or python-code (Ex. 4). However we would like to overlay text and images for the heading.

I have no idea why? Why is it working in binder `notebook` but not in `lab`? Are some packages missing? Is this syntax not supported?
