# What is an ECDL?

A Littrow external cavity diode laser (ECDL) is a type of laser configuration that enhances the wavelength selectivity and tunability of a diode laser. This setup involves extending the cavity of the diode laser with an external optical element—a diffraction grating. The grating acts as a feedback mechanism, reflecting a specific wavelength back into the diode, which stabilizes the output and allows for fine-tuning of the laser's wavelength. This design is particularly advantageous for applications requiring narrow linewidths and precise control over the laser emission wavelength, such as spectroscopy, atomic physics, and optical communications.

The operation of a Littrow ECDL hinges on the diffraction grating, which is oriented so that the angle of incidence equals the angle of diffraction for the desired wavelength. When the diode emits light, it spreads over a range of wavelengths. The grating, positioned at the Littrow configuration, diffracts the light, with a specific wavelength being efficiently reflected back into the diode. This feedback reinforces the emission at this wavelength, suppressing others, and thus narrowing the output spectrum. By adjusting the angle of the grating, the reflected wavelength can be finely tuned, allowing the laser's output wavelength to be precisely controlled. This mechanism provides the ECDL with its narrow linewidth and tunability.

# Why do we need it?

To create a magneto-optical trap, we perform *Doppler cooling*. Doppler cooling is a technique used to reduce the temperature of atoms or ions by exploiting the Doppler effect; when photons red-detuned slightly below the resonant frequency of an atomic transition are incident upon an atom traveling towards the photons, as the atoms move toward the laser, the light's frequency appears blue-shifted due to the Doppler effect, bringing it closer to resonance with the atomic transition. This increases the probability of the atoms absorbing photons, which exerts a force that opposes their motion, effectively slowing them down and reducing their kinetic energy. The linewidth of the atomic transition determines the range of velocities over which the cooling is effective. After absorption, the atoms spontaneously emit photons in random directions, which averages out to no net momentum change. By carefully tuning the laser frequency and considering the atomic transition linewidth, Doppler cooling can reduce the temperature of atomic ensembles to the order of microkelvins, limited by the natural linewidth of the transition used for cooling.

Of course, to perform this technique reliably, we need to be able to stabilize the photon frequency reliably. The ECDL is one of the simplest and cheapest ways to generate narrow-linewidth photons on demand, and can be used to create the cooling beams necessary for the MOT.


# How do we make it?

References: 
- [\[2009.10535\] 3D Printing an External Cavity Diode Laser Housing](https://arxiv.org/abs/2009.10535)
- [\[2104.06019\] A simple, powerful diode laser system for atomic physics](https://arxiv.org/abs/2104.06019)
- [\[2205.14149\] Low-Drift-Rate External Cavity Diode Laser](https://arxiv.org/abs/2205.14149)
- [\[physics/0312047\] Simple external cavity diode laser](https://arxiv.org/abs/physics/0312047)

To make fabrication and replication as simple as possible, we will use a design that can be entirely 3D printed from thermoplastics. Compared to monolithic metal designs, thermoplastic designs exhibit more hygroscopicity and and worse stiffness, making them theoretically less performant over long durations. However, they are significantly cheaper and faster to create, require no manufacturing knowledge, and have lower thermal conductivity which can assist with stability on shorter timescales. 

In short, a Littrow ECDL has four components: 
- a laser diode that is temperature stabilized using a temperature sensor and thermoelectric cooler
- a diffraction grating mounted at an angle with respect to the laser diode with finely tunable resolution
- a 'coarse' method of adjusting the angle (e.g. 100 threads-per-inch screw) and a 'fine' electromechanical method of adjusting the angle (e.g. piezoelectric actuator)
- an alignment tool to back-couple the light from the grating into the laser diode to stabilize emission

# Student Objectives
- Fabricate and assemble the ECDL; wire up electronics and ensure observation of lasing
- Measure power output from ECDL with power meter and ensure power is at least 70% of nominal diode power for the given driver current
- Control diode current and temperature from control PC via command-line interface

# Operation and Benchmarks
- Measure the performance of system with wavemeter
- Observe fluorescence in the vapor reference cell by scanning through the grating angle.


