# What is a negative stiffness metamaterial?

[![Negative stiffness full-band shielding](https://img.youtube.com/vi/KSey5ngRhL4/0.jpg)](https://www.youtube.com/watch?v=KSey5ngRhL4)

A negative stiffness metamaterial is a type of engineered material that exhibits a counterintuitive mechanical behavior: when subjected to an external force, it deforms in the opposite direction to what conventional materials do. This means that under compression, it expands, and under tension, it contracts.

When a structure or system equipped with a negative stiffness metamaterial is subjected to vibrational energy, the negative stiffness component acts to counteract and absorb some of this energy. This reduces the amplitude of the vibrations and dissipates the energy more effectively than a system with only positive stiffness elements. As a result, negative stiffness metamaterials can be used to design isolators, dampers, and other devices that protect structures or sensitive equipment from unwanted vibrations.

# Why is it useful for quantum engineering?
The laser system we use for atom trapping requires an angle to be stabilized to within microradians of some optimal value. As you might imagine, any external vibration can cause variations in that angle that are substantially larger than the minimum precision we require for locking. Given that the entire optical setup is small and lightweight, there is very little mass to dampen such vibrations, and rather than bolt it into a big steel plate, it would be more elegant and convenient to utilize a negative-stiffness system to vibrationally isolate the optics.

# How do we make it?

Reference: [Mechanical Metamaterials for Full-Band Mechanical Wave Shielding](https://pdf.sciencedirectassets.com/312330/1-s2.0-S2352940720X00023/1-s2.0-S2352940720301189/am.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjENX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJHMEUCIDkl7owXJ9%2B83Eo0CkS3WNLqSRXGUvgVIIQVEjRLOzf5AiEA9W7kz4nIvuevAGDo%2BY1mgvZ6BgkeKN2O21d8ksN2c50qvAUIrf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAFGgwwNTkwMDM1NDY4NjUiDE6bf7KMsm340LNMgiqQBSY8P15ISAaN2Hfycb89%2FVEoS0924e8L5je%2FyHs7SatuRYD3IXMcFUWT9sqQluBnRB%2B14F4TfUNlv4AxL3Nqz8YnnKVwTrgFmqH1mLLTlWZVIq%2FUXiahJui6CAepJ3DPspbypJ1EC8tKKDm7QvU1RZFIL3PGGSnTedb09JCEs%2BFZN4%2FGkoJV6reiMeDXzFc%2FZwqZjZGH0YsESGDOAvROJMheyhqHzViigV7nRd0RedM793TCHVlV2IP7JsGiY3Ah9MAagJMwm0aY5D9fCgr8o6u%2BA0Bc0brU4tC26ltUWrwNsDo5U1%2FAaIUbf2wgeradQwW6R1pAACMhl95NtC%2FtXoI4rEOqgULiMf5cGyuBGtAOvCOf3kIMzd37CThPhSi0nxDP6%2FZJOmPV1wnYYmXfHOno9IjbZ%2FQpxI0%2BwxsBaLPJyZsFj7HqwRMa1KDlhJZyVGaKPNIzjtWppa8a40HK1rDySNXIZ4tXOoQ3sBe5LaKsfEV8MntRk0Jjai91VLT8CGUEQPZpK4xlzS0sh0cK26kiL3qYX4XnMm0aa%2FIp3eZvhoCfDqE1r%2BCvXH9mWCjVAZr%2FPgO7kMn6QlhOhSL8TY635yYM1FCrx8S4%2BQRycPSHxLKR0G6CkRjgxCD2dciXJGoLxQKoJ5kEkehpzD4LqqXyPggv2abAWYXwL5sFjniJuuBaf83x9v4Q4SGUZYDTuL85rU8%2F8RH4VBqbi2hMKIQvYfjetkMaP5EAwdlu6oM1xcv7nT5%2Fr8Okkyib3BwSNtCLa%2FzxcZTH3pyZ%2BB9FaShszUbTgZZ5L4DDZnnizTbCeLzoaWDWRAlnlyYWHDFdb%2BPc24Fp18fMqAfWOndiZZypSO8LgZXdZHkakTCL3IexMOHeua4GOrEBsSL7iylC5dA3cwUMZaPkXSkKGYyjHL5qhshDBDAEx4hbqBCMoQ5a8PCGNMxS%2FiLFAAslOeZs7Sgvv%2FnDoAlDuMcnse3t1S%2BlT5QaBeiDxhfZc%2FuGSWpQiTslU6D7rURRQLvsVt4Z0b00rDsFOguYp05WR52E7Z16yeezK%2BrS8mbrlfnDiprU%2B7prrGEY43nmwYX%2BKWy%2Bk%2Bn3AkIK8QD%2FSDTwc2m4JILpLktTnt0W%2BGT6&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20240215T205007Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYWA2U3VFM%2F20240215%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=4f41e2758c6b949de5c21870b3bf798438d35a4430ab0bca9cbce62cd647ad41&hash=9fe39b2148c3ed137a6a7e9aff13546c78a581fffd6675730eedf891eec58722&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S2352940720301189&tid=pdf-a0e11f7f-d1e8-4a8e-a6b4-eff2cda936ee&sid=1608a5d79adb4549714a9e4556b9e18641f2gxrqa&type=client)

This specific metamaterial unit cell consists of springs and rigid links arranged in a specific geometry. Two design criteria are derived based on energy balance considerations:
- The spring constants and link lengths must satisfy a specific ratio.
- The total potential energy stored in the springs must equal the input work done by external forces.
Satisfying these criteria ensures that, regardless of the displacement, the force transmitted to the payload remains constant. This means the payload experiences zero effective stiffness. With zero stiffness, the payload is completely isolated from any vibrations or displacements applied to the metamaterial. The input energy just circulates between the springs/links without affecting the payload.
This novel "energy circulation" mechanism yields the negative effective stiffness. It's fundamentally different from typical negative stiffness systems that combine positive and negative stiffness elements. In essence, the system becomes a mechanical inductor.

# Student Objectives
- Compute the required parameter values of the springs and linkages to stabilize the optical system
- Fabricate and assemble the components of the system

# Operation and Benchmarks
- Measure the performance of system with a pressure-wave generator and a vibrometer
- Measure the stability of the laser under the effects the pressure-wave generators 
