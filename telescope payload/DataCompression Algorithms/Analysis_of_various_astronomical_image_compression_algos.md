# Analysis of various astronomical image compression algorithms

### Abstract of the analysis :

We compare a variety of lossless image compression methods on a large sample of astronomical images and show how the compression ratios and speeds of the algorithms are affected by the amount of noise (that is, entropy) in the images.

We perform image compression tests on a large sample of 16-bit integer astronomical CCD
images using the GZIP compression program and using a newer FITS tiled-image compression
method that currently supports 4 compression algorithms: Rice, Hcompress, PLIO, and the same
Lempel-Ziv algorithm that is used by GZIP. Overall, the Rice compression algorithm strikes the
best balance of compression and computational efficiency; it is 2–3 times faster and produces
about 1.4 times greater compression than GZIP (the uncompression speeds are about the same).
The Rice algorithm has a measured K value of 1.2 bits per pixel, and thus produces 75%–90%
(depending on the amount of noise in the image) as much compression as an ideal algorithm with
K = 0. Hcompress produces slightly better compression but at the expense of 3 times more CPU
time than Rice. 

</br>

Compression tests on a sample of 32-bit integer images show similar results, but
the relative speed and compression ratio advantage of Rice over GZIP is even greater. 


