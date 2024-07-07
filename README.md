# Neutron Star Modeling

This project involves the modeling of a neutron star by plotting its mass and pressure profile using both classical and relativistic approaches. The analysis is based on the principles of hydrostatic equilibrium and the Tolman-Oppenheimer-Volkoff (TOV) equations.
![Neutron-Star-Jet](https://github.com/Abhishek-465/Neutron-Star-Model/assets/127030695/c64ef0a6-0a65-4fff-878b-99948af9af8d)

## Introduction to Neutron Stars

Neutron stars are incredibly dense remnants (almost a size of a city)  of massive stars that have undergone supernova explosions. These stars are composed almost entirely of neutrons and have masses comparable to that of the Sun but with radii of only about 10 kilometers. The study of neutron stars provides insights into the properties of matter under extreme conditions. Neutron stars can rotate at an astonishing speed which emit radiations that can be detected from earth. Due to high density it has a strong gravitational pull which results in gravitational lensing.

## Project Overview

This project models the mass and pressure profile of a neutron star using two approaches:
1. **Classical Approach**
2. **Relativistic Approach (TOV Equations)**

Both approaches are implemented in a Jupyter Notebook (`.ipynb` file), where we solve the relevant equations numerically and plot the resulting profiles.

## Equations and Formulas

### 1. Classical Hydrostatic Equilibrium

The classical hydrostatic equilibrium equation is given by:

\[ \frac{dP(r)}{dr} = -\frac{G \cdot M(r) \cdot \rho(r)}{r^2} \]

where:
- \( P(r) \) is the pressure at radius \( r \)
- \( G \) is the gravitational constant
- \( M(r) \) is the mass enclosed within radius \( r \)
- \( \rho(r) \) is the density at radius \( r \)

The mass continuity equation is:

\[ \frac{dM(r)}{dr} = 4\pi r^2 \rho(r) \]

### 2. Relativistic Approach (TOV Equations)

The Tolman-Oppenheimer-Volkoff (TOV) equations are:

\[ \frac{dP(r)}{dr} = -\frac{G \left( \rho(r) + \frac{P(r)}{c^2} \right) \left( M(r) + 4\pi r^3 \frac{P(r)}{c^2} \right)}{r^2 \left( 1 - \frac{2GM(r)}{rc^2} \right)} \]

\[ \frac{dM(r)}{dr} = 4\pi r^2 \rho(r) \]

where:
- \( c \) is the speed of light

### Energy Density and Initial Number Density

The energy density \( \epsilon \) is related to the mass density \( \rho \) by \( \epsilon = \rho c^2 \). The initial number density \( n_0 \) refers to the number of particles per unit volume at the core of the neutron star.

## Numerical Methods

The equations are solved numerically using a suitable integration method (e.g., Runge-Kutta) to obtain the mass and pressure profiles as functions of the radius.

## Results

The project includes plots of the mass and pressure profiles for both the classical and relativistic approaches. 

### Classical Approach
- Mass Profile: Shows how the mass of the neutron star increases with radius.
- Pressure Profile: Illustrates the pressure distribution within the neutron star.

### Relativistic Approach (TOV)
- Mass Profile: Provides a more accurate representation of mass distribution under strong gravitational fields.
- Pressure Profile: Reflects the pressure distribution considering relativistic effects.

## Conclusion

The relativistic approach using the TOV equations provides a more accurate approximation of the neutron star's properties compared to the classical hydrostatic equilibrium. This is due to the significant effects of general relativity in such extreme conditions.
