Direct surface wave radial anisotropy tomography package (DSurfRTomo)

please refer to:

	Hu, S., H. Yao, and H. Huang (2019), Direct surface wave radial 
	anisotropy tomography in the crust of the eastern Himalayan 
	syntaxis. Submitted

for details of the code

The dispersion data (ALLR.dat for Rayleigh wave 
and ALLT.dat for Love wave), resulting model (DSurfRTomo.inMeasurement.dat) 
in the crust of the eastern Himalayan syntaxis is provided in example/

#############

2019/05/18
The code may still need minor modification  

##############

output (default DSurfRTomo.inMeasure.dat) is in the format
	: lon lat dep vsv gamma

For visualization,
to compute average shear wave velocity (vs) and radial anisotropy (xi)
using the following equaitons:

1.	vs=vsv*(1+gamma)/2.0

2.	xi=2*(gamma-1)/(gamma+1)*100


##############
