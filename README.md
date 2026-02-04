# GW200105: Data release for the precessing-eccentric analysis with pyEFPE

This archive contains posterior samples, priors and metadata from gravitational‑wave
inference of the neutron star - black hole binary GW200105 with the precessing-eccentric waveform model **pyEFPE** (Morras et al.).

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

## Citation
If you use these data, please cite:
1. This Zenodo dataset using the DOI from the Zenodo landing page.
2. The associated paper: Gonzalo Morras, Geraint Pratten, Patricia Schmidt, _Orbital eccentricity in a neutron star - black hole merger_ https://doi.org/10.48550/arXiv.2503.15393

## License
These data are released under the Creative Commons Attribution 4.0
International (CC‑BY‑4.0) license, included as LICENSE in this archive.

## Contact
For questions about these files or their usage, please contact the authors of the associated analysis.

