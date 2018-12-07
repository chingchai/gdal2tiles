## 🗺️ gdal2tiles

Generates directory with TMS or XYZ tiles, KMLs and simple web viewers with multithreading support.

This is a fork of the script available at official [OSGeo/gdal](https://github.com/OSGeo/gdal) repository: [gdal2tiles](https://github.com/OSGeo/gdal/blob/trunk/gdal/swig/python/scripts/gdal2tiles.py)

### **Usage**
    
```bash
$ gdal2tiles.py [options ...] input_file [output_dir]
```

All supported options are available here: [www.gdal.org/gdal2tiles](http://www.gdal.org/gdal2tiles.html)

Extras:

**-x**, **--xyz**

additional option that allows tiles to be generated in the XYZ format

```bash
$ gdal2tiles --profile=mercator --xyz -z 8-22 nu_transparent_mosaic_group1.tif xyz-tiles -c gistnu -a 0
Generating Base Tiles:
0...10...20...30...40...50...60...70...80...90...100
Generating Overview Tiles:
0...10...20...30...40...50...60...70...80...90...100
```