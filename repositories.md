# Repositories & Libraries
## Fenics
- https://bleyerj.github.io/comet-fenicsx/
- SNES, Fracture : https://newfrac.gitlab.io/newfrac-fenicsx-training/python/README.html

### Contact mechanics
- https://bitbucket.org/fenics-project/dolfin/src/946dbd3e268dc20c64778eb5b734941ca5c343e5/python/demo/undocumented/contact-vi-snes/demo_contact-vi-snes.py?at=master#demo_contact-vi-snes.py-1,87:88,99
- Evzen Korec's thesis repo : https://github.com/evzenkorec/thesis_contact/tree/master
- https://fenicsproject.discourse.group/t/boundary-conditions-for-an-liquid-sphere/4158/5
  
### Tips
- Quadrature Elements in FenicsX : https://fenicsproject.discourse.group/t/vector-quadrature-element-in-fenicsx-0-7-0/12433

### Resources
- https://www.youtube.com/@FEniCS-Project/videos
- https://scientificcomputing.github.io/fenics2024/#session-1-9-00-10-00

## Research
- Implementation strain gradients in Fenics: https://www.sciencedirect.com/science/article/abs/pii/S0168874X14002121
- Bilen Emek's open-source codes on strain gradient homogenization in Fenics:  https://bilenemek.abali.org/
- Phase field : https://bitbucket.org/bin-mech/gradient_damage_polymer/src/master/traction_3D.py

### Installing MGIS
Clone tfel and mgis projects
install boost in the fenics environment "conda install -c conda-forge boost"

chmod +x install.sh
./install
source env.sh (in the mgis installation folder and anaconda environment)

mfront --obuild --interface=generic IsotropicLinearHardeningPlasticity.mfront

https://github.com/spack/spack/pull/28502


## UQ, Reduced Models
- UQ: https://uqpylab.uq-cloud.io/
- Surrogate Modelling : https://smt.readthedocs.io/en/latest/
- https://morwiki.mpi-magdeburg.mpg.de/morwiki/index.php/MOR_Wiki:Community_portal
