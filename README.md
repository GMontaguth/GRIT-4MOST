# GRIT@4MOST

## Notes & Assumptions

PMRA, PMDEC, PARALLAX are set to 0.0 (no Gaia values provided).

RESOLUTION = 1 corresponds to LRS.

EXTENT_PARAMETER is computed from effective radius (re) multiplied by the pixel scale 0.55 arcsec/pix.

RULESET was assigned uniformly as ST_RULESET_LRS; finer ruleset splitting by magnitude is possible but optional.

All calibration columns (CAL_MAG_*) are placeholders filled with 0.0.

## Sample Definition

The galaxies included in this catalogue are red and low-Sérsic systems selected from S-PLUS photometry and structural measurements:

Colour cut: 

(u−r)>2.3, ensuring that the sample contains red galaxies.

Structural cut: Sérsic index in the r-band 

n_r<2.5, selecting galaxies with disc-like or transitional morphologies.

Photometric system: The S-PLUS r filter is designed to be SDSS r-like, ensuring compatibility with Sloan Digital Sky Survey measurements.

This combination of photometric and structural criteria identifies galaxies that are already evolving away from LTG population, making them suitable transition/quenched candidates for spectroscopic follow-up with 4MOST LRS.
