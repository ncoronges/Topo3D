
Madrid cerceda bounding box

north most N 40'50
south most N 40'34

west most W 4'20'
east most W 3'46'

First translate hgt files to dat. Then load scad file 

gdal_translate -of AAIGrid -srcwin 600 600 150 150 N40W109.hgt ../../../scad/rockies.dat 

