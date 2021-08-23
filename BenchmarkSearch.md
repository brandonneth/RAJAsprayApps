# Sparse Codes

Lots of sparse matrix and tensor codes involve reduction operations. This section contains notes about my search for bnechmarks that might be useful in testing RAJA+spray.

https://arxiv.org/pdf/2001.00660.pdf

This paper gives a bunch of examples. Anytime I see a summation I'm going to assume there's a reduction happening, even if there are schedules that don't do the reduction like that.
- Tensor-Times-Vector Product
- Tensor-Times-Matrix Product
- Matriced Tensor-Times-Khatri-Rao Product


# Climate Science and Related Codes

GEOSX is simulation code for carbon storage. It has a bunch of tutorials. Concerning that tutorial 9 is called "Hydraulic Fracturing", but we'll look at Tutorial 6 which is "CO2 injection into an unstructured grid."

## Stuff Found Searching Google

From "HPC Systems for Weather Modeling"
- Weather Modeling and Forecasting Process
- North American Mesoscale Model
- Weather Research and Forecasting
- Global Forecast System

NOAA has HPCC that do climate simulations

Numerical weather prediction (NWP)

Atlas is a library for numerical weather prediction and climate modelling. https://github.com/ecmwf/atlas/
Seeing some kernels: https://github.com/ecmwf/atlas/blob/develop/src/atlas/numerics/fvm/Nabla.cc

Petascale pattern recognition: https://link.springer.com/chapter/10.1007/978-3-319-23117-4_37

Community Atmosphere Model (CAM v5)

CMIP-5 archive, used for IPCC

https://www.osti.gov/servlets/purl/1265491
DOE ACME
Spectral Eulerian numerical method for evolving thy dynamical equations in the atmosphere
Community Earch System Model (CESM) DOE has an "ACME" branch of CESM

https://github.com/exawind/nalu-wind Wind turbine and wind farm solver

https://github.com/gahansen/Albany labelled as climate by SANDIA

https://github.com/E3SM-Project/scream cloud stuff


### Weather Research and Forecasting

It looks like they "offer two dynamical solvers for computation": WRF-ARW and WRF-NMM

narac.llnl.gov has info about some inhouse use. Here's a github repo: https://github.com/LLNL/WRF-IBM



Particle in Cell codes for fusion simulation: https://www.nersc.gov/assets/pubs_presos/SC12ProxyNovFinal.pdf



