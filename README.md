# GRIT@4MOST: Galaxies in Transition- Influence of group environment 

# Abstract:
More than half of the galaxies in the nearby Universe reside in groups, where slow encounters can
already alter their properties before they are accreted into larger systems such as galaxy clusters.
We target transition galaxies-red, low-Sérsic (n<2.5) systems, because they sit between late- and
early-type classes and already show changes: in groups they are smaller at fixed stellar mass and
form fewer stars than in the field, suggesting structural evolution via bulge growth and fading outer
discs. They comprise ~8-10% of group members and are widely dispersed on the sky, demanding
an efficient survey. 4MOST is ideal for this task due to its broad overlap with S-PLUS and
eROSITA surveys. The Low-Resolution Spectrograph (LRS) fibres, covering 370-950 nm at
R≈4000-7800, allow us to derive ages, metallicities, basic kinematics, and to separate star
formation from AGN and shocks. Through the supplementary-target mode, unused fibres are
allocated without additional pointings or observing time, enabling the construction of a clean, sky-
wide sample.

# PI & COPI:
PI: Erik Lima (USP/IAG, Brazil)
COPI: Laerte Sodre (USP/IAG, Brazil)
COPI: Ciria Lima Dias (Userena, Chile)

# Resolution:
(x) Low Resolution () High Resolution

# Target type
() Galactic (x) Extragalactic

# Which Surveys is this proposal related to? Which other supplementary target proposals is this proposal related to?
None

# Dataset Description

This dataset contains astronomical targets selected for observation with the 4MOST spectrograph. The file 4MOST_targets_LRS_GRIT.zip includes a compilation of 738 galaxies included in this catalogue are red and low-Sérsic systems selected from S-PLUS photometry, with their celestial coordinates, magnitudes, and other properties relevant for spectroscopic observations.

## Table Description – `4MOST_targets_LRS_GRIT.fits`

This FITS binary table contains **738 rows** and **35 columns**, following the VIS-MAN-4MOST-47110-1720-0001 format (version 2.6).  
Below is a summary of all table fields:

| Index | Name              | Description                                      | Unit           | Type   |
|:-----:|-------------------|--------------------------------------------------|----------------|--------|
| 1     | NAME              | Object identifier                               | —              | String |
| 2     | RA                | Right Ascension (J2027)                         | deg            | Float  |
| 3     | DEC               | Declination (J2027)                             | deg            | Float  |
| 4     | PMRA              | Proper motion in RA                             | mas·yr⁻¹       | Float  |
| 5     | PMDEC             | Proper motion in DEC                            | mas·yr⁻¹       | Float  |
| 6     | EPOCH             | Position epoch                                  | yr             | Float  |
| 7     | RESOLUTION        | Required spectral resolution                    | —              | Int    |
| 8     | SUBSURVEY         | Subsurvey identifier                            | —              | String |
| 9     | TEMPLATE          | Spectral template name                          | —              | String |
| 10    | RULESET           | Observation ruleset                             | —              | String |
| 11    | EXTENT_FLAG       | Object extent flag                              | —              | Int    |
| 12    | EXTENT_PARAMETER  | Extent parameter (angular size)                 | arcsec         | Float  |
| 13    | EXTENT_INDEX      | Extent index                                    | —              | Float  |
| 14    | MAG_TYPE          | Photometric magnitude system                    | —              | String |
| 15    | MAG               | Object magnitude                                | mag            | Float  |
| 16    | MAG_ERR           | Magnitude error                                 | mag            | Float  |
| 17    | DATE_EARLIEST     | Earliest observation date                       | d              | Float  |
| 18    | DATE_LATEST       | Latest observation date                         | d              | Float  |
| 19    | CADENCE           | Observation cadence                             | —              | Int    |
| 20    | REDDENING         | Reddening (E(B–V))                              | mag            | Float  |
| 21    | REDSHIFT_ESTIMATE | Estimated redshift                              | —              | Float  |
| 22    | REDSHIFT_ERROR    | Estimated redshift uncertainty                  | —              | Float  |
| 23    | TEMPLATE_REDSHIFT | Template redshift                               | —              | Float  |
| 24    | CAL_MAG_BLUE      | Calibrated magnitude (blue band)                | mag            | Float  |
| 25    | CAL_MAG_GREEN     | Calibrated magnitude (green band)               | mag            | Float  |
| 26    | CAL_MAG_RED       | Calibrated magnitude (red band)                 | mag            | Float  |
| 27    | CAL_MAG_ERR_BLUE  | Error in blue-band calibrated magnitude         | mag            | Float  |
| 28    | CAL_MAG_ERR_GREEN | Error in green-band calibrated magnitude        | mag            | Float  |
| 29    | CAL_MAG_ERR_RED   | Error in red-band calibrated magnitude          | mag            | Float  |
| 30    | CAL_MAG_ID_BLUE   | Calibration source ID (blue band)               | —              | String |
| 31    | CAL_MAG_ID_GREEN  | Calibration source ID (green band)              | —              | String |
| 32    | CAL_MAG_ID_RED    | Calibration source ID (red band)                | —              | String |
| 33    | CLASSIFICATION    | Object classification                           | —              | String |
| 34    | COMPLETENESS      | Observation completeness                        | —              | Float  |
| 35    | PARALLAX          | Object parallax                                 | mas            | Float  |

---

**Additional information:**
- **FMTDOC:** VIS-MAN-4MOST-47110-1720-0001  
- **FMTVERS:** 2.6  
- **Number of rows:** 738  
- **Number of columns:** 35  
- **Checksum:** WmPDXlMAWlMAWlMA  
- **Created:** 2025-10-21  

---
# Scientific Context

Galaxy groups are the most common environment in the nearby Universe and play a central role in the hierarchical growth of cosmic structures. Their relatively shallow potential wells and high interaction rates make them ideal laboratories for studying environmental mechanisms such as tidal interactions, strangulation, and minor mergers that can transform galaxies before they fall into clusters — a process known as pre-processing. In this context, transition galaxies (TGs) — red systems with low Sérsic indices — are key tracers of morphological and star formation quenching. Previous works (e.g. Montaguth et al. 2023, 2025) have shown that TGs in compact and non-compact groups display distinct structural properties compared to their field counterparts, with steeper and lower normalised mass–size relations that point to bulge growth and disc fading as environmental effects. The GRIT@4MOST project aims to obtain low-resolution spectra (R ≈ 4000–7800) for a representative sample of transition galaxies in groups identified from the 2PIGG and S-PLUS/eROSITA catalogues. This will allow detailed measurements of stellar populations, metallicities, ionisation mechanisms, and kinematics, providing the first homogeneous spectroscopic characterisation of transition galaxies in group environments and offering crucial insight into the physical processes driving galaxy transformation and pre-processing.

## Sample Definition

Targets were drawn from galaxy groups in the southern hemisphere using the 2PIGG (Eke et al. 2004) and S-PLUS/eROSITA (Doubrawa et al., in prep.) catalogues. Groups were cross-matched with S-PLUS imaging to derive consistent structural parameters across 12 filters. Sérsic indices were measured with MorphoPLUS, a pipeline based on GALFITM that performs multi-band Sérsic fitting. Transition galaxies (TGs) were defined as systems with red colours 

Colour cut: 

(u−r)>2.3, ensuring that the sample contains red galaxies.

Structural cut: Sérsic index in the r-band 

n_r<2.5, selecting galaxies with disc-like or transitional morphologies.

Photometric system: The S-PLUS r filter is designed to be SDSS r-like, ensuring compatibility with Sloan Digital Sky Survey measurements.

This combination of photometric and structural criteria identifies galaxies that are already evolving away from LTG population, making them suitable transition/quenched candidates for spectroscopic follow-up with 4MOST LRS.
