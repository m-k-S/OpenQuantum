# What is an ion pump?

An ion pump, also known as an ion getter pump, is a type of vacuum pump used to create and maintain ultra-high vacuum (UHV) environments. It operates on the principle of ionizing gas molecules present in the vacuum chamber and then accelerating these ions into a solid getter material, where they are chemically or physically absorbed, effectively removing them from the vacuum. The ionization process is typically achieved using a strong electric field generated between closely spaced electrodes, while a magnetic field is often applied perpendicular to the electric field to increase the path length of the electrons, enhancing the ionization efficiency.

Ion pumps are particularly favored in applications requiring clean, oil-free vacuums, such as in scientific research and semiconductor manufacturing. They are capable of achieving pressures as low as 10^-11 Torr, making them suitable for ultra-high vacuum applications. Moreover, by measuring the current through the electrodes, a pressure measurement can be approximated, making them additionally useful as a coarse pressure gauge.

However, an ion pump can only be started from high vacuum (around 10^-5 Torr); if an ion pump is turned on at atmosphere, the titanium cathodes would instantly saturated with gettered particles, rendering the plate useless (although plates can be "recharged" by sanding and polishing).

# Why do we need it?

The requirement for UHV conditions in MOT is twofold. First, a low background pressure reduces the frequency of collisions between the trapped atoms and residual gas molecules, which can lead to heating and loss of atoms from the trap. Second, it minimizes the absorption and scattering of the trapping laser beams, ensuring efficient cooling and trapping of the atoms. Ion pumps are ideal for maintaining the UHV environment needed for MOT due to their ability to create oil-free vacuums and their compatibility with the magnetic fields used in the trapping process. By ensuring a clean and stable vacuum, ion pumps play a crucial role in the successful operation of magneto-optical traps.

# How do we make it?

References:
- [Miniature Lightweight Ion Pump - NASA Technical Reports Server (NTRS)](https://ntrs.nasa.gov/citations/20100009697)
- [Sputter-Ion Pumps (CERN)](https://cds.cern.ch/record/454179/files/p37.pdf)

An ion pump is comprised of four components:
- Vacuum shell; the housing for the electrical components including some sort of electrical passthrough
- Anode; usually made of stainless steel cylinders 
- Cathodes; usually two of them and almost always made of titanium
- High-voltage power supply
- Permanent magnets in a quadrupole configuration

An appropriate electrode and magnet geometry needs to be selected and then a corresponding UHV-grade shell needs to be fabricated to house them. High-voltage can be generated from low-voltage DC input using e.g. a small EMCO DC-DC boost converter module. By using a sense resistor, the current through the pump can be measured, which can be transduced into the chamber pressure using some simple equations.

# Student Objectives
- Design electrode and magnet geometry
- Procure or fabricate UHV-compatible case for electrodes
- Procure / fabricate / assemble electrodes and magnets
- Design and build HV driver circuit with current sensing
- Clean and attach to high-vacuum chamber

# Operation and Benchmarks
- Use commercial, external pressure gauge to measure the ultimate pressure floor
- Use the same gauge to calibrate the pressure measurement using current sensing
- Use needle valve to test pumping speed

