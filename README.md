# Blender SculptGL Importer

Simple importer script for Blender, which can import models from original SculptGL .sgl files.
Main goal of this script, to give ability to Import model with PBR data, which you currently cannot export from SculptGL.

![Colors image](pbrdemo.jpg)

Supports all of the features of original .sgl format (ver 3).
I didn't tested it much, but any model of correct version should load just fine, if not, load old version to SculptGL and save it again.

Color and PBR information stored in vertex colors  
![Colors image](colors.png)

PBR channel mapping is:
- **Red**: Roughness
- **Green**: Metallic
- **Blue**: Masking (From masking tool, not related to PBR, but original file stores mask in same array)

# Installation info
- Download Zip of this repository
- Go to **File** -> **User Preferences** -> **Addons**
- Click **Install from File** and open downloaded file
- Find and enable it in Addons, under **Import-Export** tab
- Click **Save User Settings**

Then you can import your files using **File** -> **Import** -> **Sculpt GL (.sgl)**
