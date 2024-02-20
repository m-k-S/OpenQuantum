# What is a twisted-beam interferometer?

A 'twisted beam' (also known as an [optical vortex](https://en.wikipedia.org/wiki/Optical_vortex)) is a beam whose wavefront spirals in a helix, so that it has net orbital angular momentum. When a twisted beam is split, recombined, and imaged, it produces intensity-differential pairs on the petals of a 'daisy-flower-like' interference pattern. By measuring these intensity peaks, we can recover differences in path-length with extremely high precision, which can then be used to determine e.g. displacement in position of some reference surface. 

# Why do we need it?

Practically speaking, this kind of interferometer can be used to measure differences in position to a resolution of 100 picometers (as reported in literature). In atomic physics and QED experiments, being able to measure and align objects and devices to sub-wavelength precision is often very important, e.g. for establishing superradiant modes within cavities. In particular, stabilization of distances to 100 picometer repeatability allows for the locking of lasers at kHz linewidths for accessing a wider variety of atomic transitions, particularly those for which a vapor reference cell cannot be used.

# How do we make it?

Reference: [Noise self-canceling picoscale twisted interferometer](https://opg.optica.org/ol/fulltext.cfm?uri=ol-47-22-5993&id=520220)

The optomechanics of the twisted interferometer are simple - only a mirror and cylindrical lens are needed. Traditionally, the complexity and cost of the device come from generating the twisted-beam in the first place, which is typically done with a liquid-crystal-on-silicon (LCoS) spatial light modulator (SLM). However, many modern projectors use phase-only spatial light modulators to create high resolution projections; since these devices are made at scale for consumer use, their cost is extremely low relative to lab equipment. [There exists literature describing how to reverse-engineer such equipment to be used in lab experiments](https://www.repairfaq.org/sam/projectorSLM.pdf); we can borrow these techniques but utilize [more modern tools](https://www.aaxatech.com/store/products/led_pico_plus_projector_store.html
) to create high-quality twisted beam profiles at very low cost.

# Student Objectives
- Open up the Pico+ Projector and remove the LCoS SLM component
- Validate that we can generate arbitrary diffraction patterns with the SLM using a control laptop
- Create a modulation pattern that leads to a twisted-beam profile and image this profile
- Fabricate and assemble the interferometer using all three components
- Acquire interferograms from cylindrical lens and SLM
- Write signal processing code to determine position displacement from interferogram

# Operation and Benchmarks
- Measure displacements and compare to high-precision source of ground truth e.g. Heidenhain encoder
- Lock laser with inteferometer for frequency stabilization

