# Visualisation-of-FCC-crystal-surfaces
Visualization of crystal surfaces is one of the interested topics in the crystallography. 
For the visualization of crystal surfaces you can go through these steps:
step1: install jupyter-lab using $pip install jupyter-lab
step2: to open this jupyter-lab use this command:$jupyter-lab
Now you are ready to visualize the crystallographic surfaces using these codes:
from ase.visualize import view   # For the visualization we have to import view from ase.visualize lib.
from ase.build import fcc111     # fcc111() function is imported from the ase.build lib.
s=fcc111('Cu',(3,3,3))           #fcc111() is defined on Cu atom with crytallographic dimension (x,y,z)
view(s,repeat=(2,2,1))           #repeat(m,n,l) is used to repeat the coordinates of the (x,y,z) above.
