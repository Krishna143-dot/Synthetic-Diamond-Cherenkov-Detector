# Synthetic-Diamond-Cherenkov-Detector
Its primary objective is to develop a detector capable of measuring energetic particles, particularly cosmic-ray and Solar Energetic Particle (SEP) ions, over a wider continuous energy range. 
# Development and Characterization of a Synthetic Diamond Cherenkov Detector for Space Radiation Measurements

**Research Proposal**

**Prepared by:** Krishna Prasad Adhikari  
Assistant Professor of Physics  
Tribhuvan University, Nepal

## 1. Introduction and Background

Measurements of energetic particles in space are essential for understanding cosmic-ray propagation, solar energetic particle events, and the radiation environment surrounding spacecraft. Solar energetic particles, particularly high-energy protons, can pose significant risks to spacecraft electronics, astronauts, and other space-based systems. Reliable measurements of their energy spectra are therefore important for both fundamental space physics and space-weather applications.

Conventional instruments often employ silicon solid-state detector stacks for relatively low-energy particles and Cherenkov detectors for higher-energy particles. However, achieving continuous energy coverage remains challenging.

Synthetic diamond has attracted interest as a potential Cherenkov radiator because of its high refractive index, radiation hardness, and favorable thermal properties. Its theoretical proton Cherenkov threshold is approximately 92 MeV, making it potentially useful for extending the energy coverage between conventional silicon detectors and higher-threshold Cherenkov systems.

This research proposes a theoretical and computational investigation of synthetic diamond Cherenkov detectors, with particular emphasis on numerical modeling, detector characterization, and applications to space radiation measurements.

## 2. Research Problem

The performance of a Cherenkov detector depends on several physical and instrumental parameters, including particle velocity, refractive index, radiator thickness, photon production, optical transmission, and photodetector efficiency.

Although the theoretical Cherenkov threshold can be calculated analytically, the actual detector response also depends on the optical and electronic properties of the complete detection system.

A systematic computational framework is therefore needed to investigate how these parameters influence detector performance and to identify suitable configurations for space radiation measurements.

## 3. Research Objectives

The main objective is to investigate the feasibility and performance of synthetic diamond as a Cherenkov radiator for energetic particle measurements in space.

Specific objectives include:

1. Calculate the theoretical Cherenkov threshold for protons in synthetic diamond using relativistic kinematics.
2. Model Cherenkov photon production using the Frank–Tamm equation.
3. Investigate the influence of radiator thickness, refractive index, and wavelength on photon production.
4. Develop Python-based numerical models of optical collection and photodetector response.
5. Compare the theoretical performance of diamond with other Cherenkov radiator materials.
6. Investigate the potential application of the detector to high-energy proton measurements during Solar Energetic Particle events.

## 4. Theoretical Framework

The production of Cherenkov radiation occurs when a charged particle moves through a dielectric medium faster than the phase velocity of light in that medium.

The Cherenkov condition is:

βn(λ) > 1

The Cherenkov angle is expressed as:

cos θ = 1/[βn(λ)]

The threshold kinetic energy for a proton is:

K_th = m_p c²(γ_th − 1)

where:

γ_th = 1/√[1 − 1/n²]

The spectral photon production is described by the Frank–Tamm equation:

d²N/(dx dλ) = (2πα/λ²)[1 − 1/(β²n²)]

These relations provide the theoretical foundation for calculating the energy-dependent Cherenkov response of synthetic diamond.

## 5. Research Methodology

The research will initially focus on analytical calculations and computational modeling using Python.

### 5.1 Theoretical calculations

Relativistic particle kinematics will be used to calculate proton velocities, Lorentz factors, Cherenkov thresholds, and emission angles.

### 5.2 Numerical modeling

Python libraries, particularly NumPy, SciPy, Matplotlib, and Pandas, will be used to implement the theoretical equations and investigate the energy-dependent behavior of Cherenkov radiation.

The simulations will examine different proton energies and radiator properties.

### 5.3 Optical response modeling

The model will subsequently incorporate wavelength-dependent refractive index, optical transmission, photon collection efficiency, and photodetector quantum efficiency.

The expected detected photon count will be compared with the ideal theoretical photon yield.

### 5.4 Detector characterization

If suitable laboratory measurements or experimental data become available, the numerical model will be compared with measured detector responses. This will help assess the accuracy of the theoretical assumptions and identify possible sources of uncertainty.

### 5.5 Space radiation applications

The final stage will investigate how the detector response could be used to identify high-energy proton enhancements during SEP events and contribute to measurements of the space radiation environment.

## 6. Expected Results

The proposed research is expected to produce:

- A numerical model of Cherenkov radiation in synthetic diamond.
- Theoretical calculations of proton energy thresholds and emission angles.
- Energy-dependent photon-yield simulations.
- An assessment of the influence of optical and detector efficiencies.
- Comparative analysis of candidate Cherenkov radiator materials.
- A computational framework for future detector calibration and space radiation studies.

## 7. Scientific Significance

The proposed research will contribute to understanding the performance of synthetic diamond Cherenkov radiators for space radiation instrumentation.

A better understanding of their energy thresholds and detector response may help improve the measurement of energetic protons and extend the capabilities of compact space radiation instruments.

The project will also provide an opportunity to connect detector physics with broader questions in heliophysics, particularly the measurement of high-energy particles associated with solar energetic particle events.

## 8. Proposed Research Timeline

**Year 1:** Literature review, theoretical development, relativistic calculations, and initial Python simulations.

**Year 2:** Advanced numerical modeling, optical response calculations, detector parameter studies, and comparison with available experimental data.

**Year 3:** Detector characterization, uncertainty analysis, and application to space radiation measurements.

**Year 4:** Integration of results, scientific publications, dissertation preparation, and further investigation of space instrumentation applications.

## 9. Conclusion

This proposal aims to investigate synthetic diamond as a Cherenkov radiator for measuring energetic particles in space. By combining theoretical physics, Python-based numerical modeling, and experimental characterization where feasible, the research will explore the relationship between particle energy, Cherenkov photon production, and detector response.

The broader goal is to contribute to the development of reliable and compact radiation measurement systems for studying energetic particles in the space environment.

## 10. Selected References

1. Connell, J. J., Lopate, C. A., & Tabeling, J. W. (2019). A novel synthetic diamond Cherenkov radiator for measuring space radiation. *Nuclear Instruments and Methods in Physics Research Section A*, 942, 162338. https://doi.org/10.1016/j.nima.2019.162338

2. Frank, I. M., & Tamm, I. E. (1937). Coherent visible radiation of fast electrons passing through matter. *Comptes Rendus de l'Académie des Sciences de l'URSS*.

3. Particle Data Group. Review of Particle Physics: Passage of Particles Through Matter and Cherenkov Detectors. https://pdg.lbl.gov/
