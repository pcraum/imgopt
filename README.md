imgopt README

# Authors: Joel Hardi, Rob Smith, Daniel Kamil Kozar, Patrick Poulain
# Version: 0.0.1 2014-04-11
#
# For more information and usage examples, see:
# http://lyncd.com/2009/03/imgopt-lossless-optimize-png-jpeg/

Fork from https://github.com/kormoc/imgopt

------------
Installation
------------

1. imgopt is ready to run. Copy imgopt into your path and chmod it executable.
   i.e. as root or via sudo:
   cp imgopt /usr/local/bin/ && chmod a+x /usr/local/bin/imgopt

2. brew install pngcrush
   brew install https://gist.githubusercontent.com/lucasmichot/10379237/raw/ed849e34d32d47f91fca08eec13bdbbe871f10b9/pngout.rb
   brew install jpegtran


-----
Usage
-----

imgopt [FILE/DIR] [FILE/DIR] [FILE/DIR] ...

Optimizes any combination of files and directories. Directories are searched
recursively, and all image files in any subdirectories are optimized.

Examples:

 imgopt .      Optimize all images in current directory and any subdirectories
 imgopt *.png  Optimize all pngs in current directory only
