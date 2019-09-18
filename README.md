
## A MaterialBuilder Script for SideFx Houdinis Mantra

### Features

- Provides a Materialbuilder for PrincipledShader which converts textures to .rat format on import as well
- Provides an OCIO-Materialbuilder which converts textures to .rat format on import
- Provides a script which converts already linked textures to .rat (via COPs) - orignal files are untouched, new files will be placed in the origin-directory
- creates a tree based on Filnames and works best with strings provided by Substance
  - base_color or basecolor
  - roughness
  - normal
  - metallic
  - reflect
  - height
  - displace
  - bump
  - ao or ambient_occlusion
- The strings to look for can easily be changed at the bottom of each script


###  Example Node tree for MaterialBuilder


![alt text](https://raw.githubusercontent.com/eglaubauf/materialBuildMantra/master/images/Tree.png "The Tree created by one of the Scripts")

### Installation:

Append egLib to Houdini Python path or add to 123.py or 456.py

```
import sys
sys.path.append("<PathToLib>\scripts")
```

### Notes:


All of the scripts are free of charge for free use, commercial or non commercial whatsoever.  Individual Licenses are added to each file as some of these are based on work done by other devs and shall be included in branches, adaptions of this scripts. Anyone is allowed to modify, develop, change the files for his/her purpose.
But this scripts may brake your workflow. So be warned.

Some of the Files need a modified HOUDINI.ENV. An Example File is provided in the prefs Folder. I try to remove the dependencies to Houdini.env. 

The Scripts in the scripts Folder shall be added as tools to a custom Toolbar. Linking them with some keyboard shortcuts is recommended.

### Contact/Issues/Features/Questions

If you find any bugs, have suggestions or anything else please contact me via Twitter or per Mail. Please check out my other Repos as well, they might be handy to you. For any questions and/or improvement suggestions just contact me via twitter or mail.<br>
Twitter: @eglaubauf <br>
Web: www.elmar-glaubauf.at
