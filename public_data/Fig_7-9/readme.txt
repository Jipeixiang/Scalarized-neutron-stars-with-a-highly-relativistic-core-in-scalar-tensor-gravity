We provide data needed of scalaried neutron stars in massless/massive DEF/MO theory with positive beta and AP4 EOS.
The specific theory, coupling parameter beta, and the reduced Compton wavelength are showed in the file name.
Taking ‘massive_DEF_AP4_50_1.json’ as an example, the theory is DEF, the EOS is AP4, beta = 50,and barlambda = 10/1 km.

Each json file includes a lot of dictionaries with different central densities of neutron stars.
Each dictionary contains a number of scalarized solutions, while an empty dictionary indicates no scalarized solutions.
Each specific scalarized solution is packaged in a dictionary with the folling keys:
e_c: central mass density
phi_c: scalar field value at stellar centar
phi_s: scalar field value at stellar surface
psi_s: the radial derivative of scalar field at stellar surface
A_s: the value of conformal function at stellar surface
R_s: stellar radius in Einstein frame
R_j: stellar radius in Jordan frame
m_s: gravitational mass inside the stellar surface
m_bar: baryonic mass
nu_s: potential function at stellar surface
omega_s: function omega at stellar surface
varpi_s: the radial derivative of function omega at stellar surface
phi_last: the value of scalar field at numerical spatial infinity
infinify: the radial coordinate of numerical spatial infinity
m_ADM: ADM mass evaluated at numerical spatial infinity
nu_inf: potential function at numerical spatial infinity
phi_inf: scalar field value at numerical spatial infinity
psi_inf: the radial derivative of scalar field at numerical spatial infinity
omega_inf: function omega at numerical spatial infinity
varpi_inf: the radial derivative of function omega at numerical spatial infinity
H1_inf: the function H with boundary condition Eq.(91) at numerical spatial infinity
J1_inf: the function J with boundary condition Eq.(91) at numerical spatial infinity
H1p_inf: the radial derivative of function H with boundary condition Eq.(91) at numerical spatial infinity
J1p_inf: the radial derivative of function J with boundary condition Eq.(91) at numerical spatial infinity
H2_inf: the function H with boundary condition Eq.(92) at numerical spatial infinity
J2_inf: the function J with boundary condition Eq.(92) at numerical spatial infinity
H2p_inf: the radial derivative of function H with boundary condition Eq.(92) at numerical spatial infinity
J2p_inf: the radial derivative of function J with boundary condition Eq.(92) at numerical spatial infinity
Compactness: compactness
MoI: moment of inertia
H_inf: the function H with boundary condition of vanishing scalar field at spatial infinity
Hp_inf: the radial derivative of function H with boundary condition of vanishing scalar field at spatial infinity
Jp_inf: the radial derivative of function J with boundary condition of vanishing scalar field at spatial infinity
y_inf: the value y_i in Eq.(100)
C_inf: the value C_i in Eq.(100)
k2: tidal Love number
lam2: tidal deformability
