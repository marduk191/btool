btool
=====

Android pack and unpack script for abootimg

#This script depends on abootimg.

````
sudo apt-get install abootimg
````


Usage:
````
Copy your boot or recovery image to the base directory and type:
btool -u to unpack your ramdisk for editing 
btool -p pack your image back up
btool -c to delete everything
or btool -h for this help text :P
````