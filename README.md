# GaussianBeamVI
A handy tool to visualize Gaussian beam propagation through lenses

  Here I present a handy tool written in Python to visualize how Gaussain beams propagate through two simple lenses. It provides a friendly 
environment to graphically see how beam property changes as we tune the beam intial beam size, lens focus and position. I utilize
the widgets embedded in Matpyplot to create a dynamical user interface. It gives a graphical and intuitive sense when setting
up the optics. 

Packages needed:
numpy 
matpylot 

For Theory regarding Gaussian Optics, please see the following link:
http://nic.ucsf.edu/blog/wp-content/uploads/2014/06/Gaussian-Beam-Optics.pdf

Todo list：
1. Include beam property parameter M^2
2. Add more lenses
3. Fix the plotting issue when the second lens to set before the first lens. 

Note for users:

1. Please make sure the second lens is always set before the first lens and the the beam waist of the first images. I will try to fix this issue in the future.
2. My intuition tells me this code can be done more elegantly and simply, excuse me for the code being too complex, will try to imporve

