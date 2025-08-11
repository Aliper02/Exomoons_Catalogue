README.txt
==========

Exomoon & Exoplanet Candidates Catalogues
------------------------------------------

This repository contains:

1. **Exomoon Candidates Catalogue** – compiled from multiple scientific articles, including key observational and inferred parameters for each candidate moon, host planet, and host star.  
2. **PLATO and HWO Candidate Exoplanets** – derived from the exoplanet.eu database (6038 planets) after applying mission-specific observational selection criteria:  
   - **PLATO**: transit detection optimization (592 candidates).  
   - **HWO**: direct imaging & habitable zone selection (12 candidates).  
3. **Stable PLATO Candidates** – subset of the PLATO candidate list that additionally satisfy all applied dynamical stability criteria (Hill stability, Roche limit, Laplace radius).

The provided CSV files are:
- [`plato_candidates.csv`](./plato_candidates.csv) – PLATO mission observationally filtered candidates.  
- [`hwo_candidates.csv`](./hwo_candidates.csv) – HWO mission observationally filtered candidates.  
- [`plato_stable_candidates.csv`](./plato_stable_candidates.csv) – PLATO candidates passing all dynamical stability tests.

The complete description of each column in the exomoon catalogue is given below.  
The PLATO, HWO, and PLATO stable candidates CSV files include the original exoplanet.eu parameters plus additional flags indicating unknown or missing values for each selection criterion.


-----------------------------
COLUMN DESCRIPTIONS
-----------------------------

**Exomoon** – Primary name or identifier of the exomoon candidate.  
**Alternative Moon names/characteristics** – Other names or qualitative properties.  
**Exomoon status** – Current classification: candidate, not candidate yet or controversial.

**M_m (M_J)** – Estimated mass of the moon in Jupiter masses.  
**+ΔM_m / -ΔM_m (M_J)** – Positive and negative uncertainty in moon mass.  
**M_m measured method** – Technique used for mass estimation (e.g., TTV, Microlensing).

**a_m (AU)** – Semi-major axis of the moon's orbit in astronomical units.  
**+Δa_m / -Δa_m (AU)** – Positive and negative uncertainty in moon semi-major axis.

**R_m (R_J)** – Radius of the moon in Jupiter radii.  
**+ΔR_m / -ΔR_m (R_J)** – Positive and negative uncertainty in moon radius.  
**R_m measure method** – Measurement technique (e.g., transits).

**P_m (days)** – Orbital period of the moon in days.  
**i_m (º)** – Inclination of the moon's orbit in degrees.  
**+i_m / -i_m (º)** – Uncertainty in orbital inclination.

**Host Star** – Name or prime identifier of the star.  
**Alternate Star name/characteristics** – Other names or highlighted features.  
**M_* (M_J)** – Mass of the host star in Jupiter masses.  
**+ΔM_* / -ΔM_* (M_J)** – Positive and negative uncertainty in stellar mass.

**R_* (R_sun)** – Radius of the host star in solar radii.  
**+ΔR_* / -ΔR_* (R_sun)** – Uncertainty in stellar radius.  
**Teff (K)** – Effective temperature of the host star.  
**+ΔTeff / -ΔTeff (K)** – Temperature uncertainty.

**Age (Gyr)** – Stellar age in billions of years.  
**+ΔAge / -ΔAge (Gyr)** – Age uncertainty.  
**m, spectral type** – Apparent magnitude and spectral classification.  
**Distance (pc)** – Distance from Earth in parsecs.  
**+Δd / -Δd (pc)** – Uncertainty in distance.  
**Met[F/H]** – Metallicity.  
**+Met[F/H] / -Met[F/H]** – Uncertainty in metallicity.

**RA (2000)** – Right Ascension (epoch J2000).  
**DEC (2000)** – Declination (epoch J2000).

**Host Planet** – Name or Primary identifier of the planet.  
**Alternative Planet name** – Other planet designations.  
**Planet Detection method & year** – Technique and year of discovery.

**M_p (M_J)** – Planetary mass in Jupiter masses.  
**+ΔM_p / -ΔM_p (M_J)** – Planet mass uncertainty.  
**M_p measure method** – Method used for mass estimation.

**a_P (AU)** – Semi-major axis of the planet.  
**+Δa_P / -Δa_P (AU)** – Uncertainty in orbital semi-major axis.

**R_p (R_J)** – Planet radius in Jupiter radii.  
**+ΔR_p / -ΔR_p (R_J)** – Uncertainty in radius.  
**R_p measure method** – Technique used (e.g., transit).

**P_p (days)** – Orbital period of the planet.  
**+ΔP_p / -ΔP_p (days)** – Period uncertainty.

**calculated T_p (K)** – Estimated temperature.  
**+ΔT_p / -ΔT_p (K)** – Uncertainty in planetary temperature.

**Eccentricity, e** – Orbital eccentricity.  
**+Δe / -Δe** – Eccentricity uncertainty.

**Impact parameter, b** – Impact parameter of transit geometry.  
**+Δb / -Δb** – Uncertainty in impact parameter.

**ω (º)** – Argument of periastron.  
**+Δω / -Δω (º)** – Uncertainty in ω.  
**i (º)** – Orbital inclination.  
**+-Δi (º)** – Uncertainty in inclination.

**Velocity semiamplitude, K (m/s)** – Radial velocity semi-amplitude.  
**+ΔK / -ΔK (m/s)** – Uncertainty in K.

**References** – List of original sources for the data.

-----------------------------
Notes
-----------------------------

- Units are included in parentheses.
- Missing or unknown values are indicated with a blank space.
- All measurements are referenced to published literature (see "References" column).
- PLATO and HWO candidate CSV files include all available parameters from the exoplanet.eu database plus selection flags for each filtering step.
- Candidate counts from filtering:
  - **PLATO:** 592 candidates
  - **HWO:** 12 candidates

-----------------------------
License
-----------------------------

This dataset is released under the Creative Commons Attribution 4.0 International (CC BY 4.0) License.

You are free to use, share, and adapt the material, provided that proper credit is given.

-----------------------------
Author and Contact
-----------------------------

Alicia Pérez Rodrigo  
Master's Thesis in Astrophysics (TFM) – [UCM]  
Contact: Aliper02  
Year: 2025
