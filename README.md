# healpix_mc_test
This code is for producing cut-outs from HEALPix maps with error propagation from their accompanying HEALPix noise maps. for 

The input and output objectives are essentially the same as my 'akari_mc_test' respository.

In:
  High[er] resolution data with noise map.
  
Out:
  Mosaic/cutout/otherwise processed image with propagated noise map.
  
In this case, we start with the HEALPix all-sky map, and its error map (if you have one...)
The output is the region you want, with the MC simulated error map to go with it, in a "normal" fits file.
