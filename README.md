# GW200105: Data release for the precessing-eccentric analysis with pyEFPE

This archive contains posterior samples, priors and metadata from gravitational‑wave
inference of the neutron star - black hole binary GW200105 with the precessing-eccentric waveform model **pyEFPE** ([Morras et al.](https://doi.org/10.1103/PhysRevD.111.084052)).

The results have been repackaged into a
minimal, self‑describing HDF5 format designed for long‑term archival, easy reuse,
and compatibility with any HDF5‑capable software. 
Each file provides a compact representation of the key scientific outputs
without including full bilby internals.

## HDF5 File Structure

Each file contains the following groups:

/posterior                 # Posterior samples

param1[nsamples]

param2[nsamples]

...

/priors                    # Priors as HDF5 attributes

param1

param2

...

/meta                      # Metadata as HDF5 attributes

### Parameter Definitions

| Parameter | Definition |
|-----------|------------|
| chirp_mass | Detector‑frame chirp mass of the binary (in solar masses) |
| chirp_mass_source | Source‑frame chirp mass corrected for cosmological redshift (in solar masses)|
| mass_ratio | Mass ratio q=m2/m1 ≤ 1 |
| mass_1_source | Source‑frame mass of the primary component (in solar masses) |
| mass_2_source | Source‑frame mass of the secondary component (in solar masses) |
| a_1 | Dimensionless spin magnitude of the primary component |
| a_2 | Dimensionless spin magnitude of the secondary component|
| chi_eff | Effective aligned spin parallel to the orbital angular momentum |
| chi_p | Effective precession spin parameter describing in‑plane spin components |
| eccentricity | Orbital eccentricity at the reference frequency |
| mean_anomaly | Mean anomaly at the reference frequency, specifying the orbital phase for eccentric binaries |
| luminosity_distance | Luminosity distance to the source (in Mpc) |
| redshift | Cosmological redshift inferred from the luminosity distance assuming the Planck15 cosmology |
| ra | Right ascension in the ICRS coordinate frame (radians) |
| dec | Declination in the ICRS coordinate frame (radians) |
| theta_jn | Angle between the total angular momentum vector and the line of sight at the reference frequency |
| log_likelihood | Log‑likelihood value associated with each posterior sample |


## Citation
If you use these data, please cite:
1. This Zenodo dataset using the DOI from the Zenodo landing page.
2. The associated paper: Gonzalo Morras, Geraint Pratten, Patricia Schmidt, _Orbital eccentricity in a neutron star - black hole merger_ https://doi.org/10.48550/arXiv.2503.15393

## License
These data are released under the Creative Commons Attribution 4.0
International (CC‑BY‑4.0) license, included as LICENSE in this archive.

## Contact
For questions about these files or their usage, please contact the authors of the associated analysis.

