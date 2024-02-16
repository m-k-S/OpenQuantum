# What is a wavemeter?

A wavemeter is an instrument designed to accurately measure the wavelength of light. It is similar to a spectrometer in function but typically is intended to operate on coherent light sources and determines wavelength to extreme levels of precision, often down to the picometer or femtometer scale, using e.g. interference phenomena. 

Wavemeters are essential in applications requiring precise control and characterization of optical frequencies, e.g. locking lasers to fundamental frequencies, calibrating lasers, optically pumped magnetometers, molecular spectroscopy, etc.

# Why is it useful in quantum engineering?

The laser system we use for atom trapping is tuneable but only within a narrow range known as the 'mode-hop free tuning range', which is typically is of the order of single GHz (or, for our wavelength, in the single picometer range). 

Since the linewidth of the transition we want to access is 10MHz, we need to be within single GHz of that transition frequency, otherwise we will be unable to observe substantial fluorescence. 

Therefore, having a wavemeter with a wide spectral range to make a coarse measurement of the laser frequency so that it can be tuned to within the mode-hop free tuning range of the transition frequency is an essential tool for achieving stable locking. 

# How do we make it?

Reference: [Compact and high-precision wavemeters using the Talbot effect and signal processing](https://arxiv.org/abs/1907.11072)

The wavemeter is a very simple device; it requires just a beam expander, a transmission grating, and a CCD sensor. However, the CCD needs to be positioned at a precise angle with respect to the grating to generate a high-quality interferogram from which the wavelength can be computed. Once the pattern is recorder, a tone parameter extraction algorithm is used to extract the frequency.

# Student Objectives
- Fabricate and assemble the wavemeter optomechanical components
- Align wavemeter and produce interferogram
- Analyze interferogram with tone parameter extraction algorithm

# Operation and Benchmarks
- Calibrate the performance of the wavemeter against a stable laser e.g. a temperature-stabilized HeNe
- Measure the wavelength of the ECDL and cross-reference against vapor cell absorption