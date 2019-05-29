Direct surface wave radial anisotropy tomography code (DSurfRTomo)

please refer to:

	Hu, S., H. Yao, and H. Huang (2019), Direct surface wave radial 
	anisotropy tomography in the crust of the eastern Himalayan 
	syntaxis. Submitted

for details of the code

#############

2019/05/18
The code may still need minor modification  

##############

output is 
	: lon lat dep vsv gamma

For visualization,
to compute average shear wave velocity (vs) and radial anisotropy (xi)
using the following equaitons:

1.	vs=vsv*(1+gamma)/2.0

2.	xi=2*(gamma-1)/(gamma+1)*100
