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
	
Usage
===========
::

usage: image_to_ascii.py [-h] [-w WIDTH] [-m MAPPING] [-o OUTPUT] [-r] [-c] [-q] file

--< IMAGE TO ASCII CONVERTER >--

positional arguments:
  file                  path to input file

optional arguments:
  -h, --help            show this help message and exit
  -w WIDTH, --width WIDTH
                        target ascii image width [in pixels]
  -m MAPPING, --mapping MAPPING
                        mapping key [1-5]
  -o OUTPUT, --output OUTPUT
                        path to output file
  -r, --reverse         reverse image color
  -c, --color           colorized image flag
  -q, --quiet           quiet mode - do not print image
	
Example images and their convertion
===========
.. image:: images/image1.png
.. image:: images/output1.png
.. image:: images/image2.png
.. image:: images/output2.png
