
## A MaterialBuilder Script for SideFx Houdinis Mantra

### Moved Permanently

https://github.com/eglaubauf/egMantraTools

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
- A shelf is provided in the toolbar folder (put it to $HOUDINI_USER_PREF_DIR/toolbar)


###  Example Node tree for MaterialBuilder


![alt text](https://raw.githubusercontent.com/eglaubauf/materialBuildMantra/master/images/Tree.png "The Tree created by one of the Scripts")

### Installation:

Append egLib to Houdini Python path or add to 123.py or 456.py

```
import sys
sys.path.append("<PathToLib>\scripts")
```

### Notes:


All of the scripts are free of charge for free use, commercial or non commercial whatsoever. 
But this scripts may brake your workflow.

