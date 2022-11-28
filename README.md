# Modelling of the optical properties of gold & silver nanoparticles with alternating morphologies using finite element method
The code is written in plain text, and is meant to be copy/pasted into the MATLAB editor. Only the '.m' files containing refractive indices have to be installed.
## Analytical model for spherical nanoparticles
  1. Ensure that files nrau.m, nrag.m, niau.m and niag.m are installed and visible in the MATLAB folder.
  2. Run the [absorption calculation code](https://github.com/Lasseb200/P3/blob/main/MATLAB%20Analytical%20model%20for%20spherical%20nanoparticles).
## Finite element method
### Pulse expansion:
  1. Ensure that files nrau.m, nrag.m, niau.m and niag.m are installed and visible in the MATLAB folder.
  2. Run the 3D model for either [spheres](https://github.com/Lasseb200/P3/blob/main/MATLAB-finite-element-method/Pulse%20expansion/Sphere%20point%20model%20with%20normal%20vectors%20and%20area%20calculations), [rods](https://github.com/Lasseb200/P3/blob/main/MATLAB-finite-element-method/Pulse%20expansion/Rod%20point%20model%20with%20normal%20vectors%20and%20area%20calculations) or [prisms](https://github.com/Lasseb200/P3/blob/main/MATLAB-finite-element-method/Pulse%20expansion/Prism%20point%20model%20with%20normal%20vectors%20and%20area%20calculations).
  3. Run the [absorption calculation code](https://github.com/Lasseb200/P3/blob/main/MATLAB-finite-element-method/Pulse%20expansion/Calculation%20and%20plot%20of%20absorption%20cross%20section). Make sure that the variables from the 3D model haven't been cleared.
  
notes: Choose between gold or silver nanoparticles by choosing permitivitty on line 61 in the absorption calculation code, the direction of the E-field is chosen on line 58. The prism model can be rotated around the z-axis on line 278 in its source code. 
```diff
! This feature is not working properly in the current state !
```

![3D_point_model_of_prism](3D_point_model_of_prism.png) ![Ag_rods_plot](Ag_rods_plot.png)
### Linear expansion (WIP)
Disclaimer: The script used in the linear expansion model is based on code from supervisor Thomas Søndergaard, used in his book *Green's Function Integral Equation Methods in Nano-optics*.
  1. Ensure that files nrau.m, nrag.m, niau.m and niag.m are installed and visible in the MATLAB folder.
  2. Ensure that the MATLAB add-on '[Partial Differential Equation Toolbox](https://se.mathworks.com/products/pde.html)' is installed.
