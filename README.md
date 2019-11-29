# DATASET MICROSCOPY #


Python script used to generate patches used by CSBDeep for super resolution microscopy.

Create patches where common spots have been found between multiple image stacks.

This tool uses modified code of picasso (https://github.com/jungmannlab/picasso) for spot localization and modified patches creation function from CSBDeep (https://github.com/CSBDeep/CSBDeep).


Getting started
===============
To work with DatasetMicroscopy :
1) save your image files (*.tif*) in a data directory
- **target** for great quality images
- **source** for poor quality images


Example of directory
- data/target/{file1.ome.tif, file2.ome.tif, file3.ome.tif, file4.ome.tif}
- data/source/{file1.ome.tif, file2.ome.tif, file3.ome.tif, file4.ome.tif}

The files must have the same names between target and source directories


2) Run generateData.py (python generateData.py)
