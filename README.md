# s2toolkit

S2Toolkit QGIS Plugin adds tools that let create S2 Geometry in QGIS processing provider.
* In the first version only "S2 From Extent" tool is available, that can create S2 geometry of any level from vector layer (using minimal bounding box) directly in QGIS.
* Next, this toolbox will be updated with tools like "S2 From Geometry" and so on...

## References
This QGIS plugin uses Python open package [s2sphere](https://github.com/sidewalklabs/s2sphere) to create S2 geometry.
This package downloaded in the source folder, so you don't need to install it manually.
