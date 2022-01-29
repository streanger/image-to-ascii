image_to_ascii
===========
Python image to ascii converter


Install
===========

1. Copy repo (or at least image_to_ascii.py) to your local device:
::
    git clone https://github.com/streanger/image_to_ascii
2. Install dependencies (PIL, termcolor) with command:
::
    pip install Pillow termcolor
    
3. Run script in the following way:
::
    python image_to_ascii.py image.png
	
	
Usage
===========
Run script in the following way:
::
    python image_to_ascii.py image.png
	
For now only filename is passed to commandline arguments. Every other parameters should be edited inside the script file. So if you want to set things like width, you should change it in line with calling image_to_ascii function. Each parameter is described below:
::
    filename		- name of image file to be converted
    target_width	- width of output image in characters
    reverse		- reverse color flag
    colorized		- colorized output flag. Switch between color/black-white
    mapping_key		- key of ascii characters mapping set. Try each from 1-5
	
Example images and their convertion
===========
.. image:: images/image1.png
.. image:: images/output1.png
.. image:: images/image2.png
.. image:: images/output2.png
