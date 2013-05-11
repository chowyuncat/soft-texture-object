A Software OpenGL Texture Object
================================
This project is a software implementation of mock OpenGL texture objects which
return a texel when queried with a UV coordinate.

This was born from my need to both display (hardware-accelerated) and export a 
point cloud color-mapped by height.

Initial mock coverage is:

* Type: TEXTURE\_1D
* Format: RGB, BYTE
* Filters: NEAREST, LINEAR
* Wrap Mode: CLAMP\_TO\_EDGE
* Texture Generation Mode: OBJECT\_LINEAR
* Mipmap Support: **NO**

