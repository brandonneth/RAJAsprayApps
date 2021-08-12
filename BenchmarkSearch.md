# Sparse Codes

Lots of sparse matrix and tensor codes involve reduction operations. This section contains notes about my search for bnechmarks that might be useful in testing RAJA+spray.

https://arxiv.org/pdf/2001.00660.pdf

This paper gives a bunch of examples. Anytime I see a summation I'm going to assume there's a reduction happening, even if there are schedules that don't do the reduction like that.
- Tensor-Times-Vector Product
- Tensor-Times-Matrix Product
- Matriced Tensor-Times-Khatri-Rao Product


# Climate Science and Related Codes

GEOSX is simulation code for carbon storage. It has a bunch of tutorials. Concerning that tutorial 9 is called "Hydraulic Fracturing", but we'll look at Tutorial 6 which is "CO2 injection into an unstructured grid."



