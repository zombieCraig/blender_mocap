# Blender Mocap Addon by Benjy Cook
This is a port of the Mocap addon by Benjy Cook that was for the 2.7x version of Blender.
It no longer worked with blender 2.8x and above and lost it's maintainer.  I am not planning
on maintaining it but it's a great piece of code and very handy.  So I ported it to 2.9.0
and plan to hack in some features that I personally want for my own projects.

Feel free to fork this and better yet...become the maintainer so we can have this as
a standard plugin again in Blender.

## Installing

copy the mocap/ folder to:

blender_folder_name/2.90/scripts/addons/

Restart blender and then goto Edit->Preferences and search for 'Motion'.

## Porting to other versions
In theory it should work is any version above 2.8x now.  To test edit the __init__.py
and update the line ```"blender": (2, 90, 0),``` to point to your current version.
