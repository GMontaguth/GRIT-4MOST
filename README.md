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

# FITS File Structure

The main file s contains a binary table with multiple columns describing the properties of the target objects. The data is formatted according to 4MOST requirements for observation proposals. Column Descriptions:

Index 	Name 	Description 	Type
0 	INDEX 	Row index in the table 	Long
1 	NAME 	Object identifier 	String
2 	RA 	Right ascension (J2027) in degrees 	Double
3 	DEC 	Declination (J2027) in degrees 	Double
4 	PMRA 	Proper motion in RA (mas/year) 	Double
5 	PMDEC 	Proper motion in DEC (mas/year) 	Double
6 	EPOCH 	Position epoch 	Double
7 	RESOLUTION 	Required spectral resolution 	Long
8 	SUBSURVEY 	Subsurvey identifier 	String
9 	TEMPLATE 	Spectral template to be used 	String
10 	RULESET 	Observation ruleset 	String
11 	EXTENT_FLAG 	Object extent flag 	Long
12 	EXTENT_PARAMETER 	Extent parameter 	Double
13 	EXTENT_INDEX 	Extent index 	Double
14 	MAG_TYPE 	Photometric magnitude system 	String
15 	MAG 	Object magnitude 	Double
16 	MAG_ERR 	Magnitude error 	Double
17 	DATE_EARLIEST 	Earliest observation date 	Long
18 	DATE_LATEST 	Latest observation date 	Long
19 	CADENCE 	Observation cadence 	Long
20 	REDDENING 	Reddening (E(B-V)) 	Double
21 	REDSHIFT_ESTIMATE 	Estimated redshift 	Double
22 	REDSHIFT_ERROR 	Estimated redshift error 	Double
23 	TEMPLATE_REDSHIFT 	Template redshift 	Double
24-32 	CAL_MAG_* 	Calibrated magnitudes in different bands 	Double
33 	CLASSIFICATION 	Object classification 	String
34 	COMPLETENESS 	Observation completeness 	Double
35 	PARALLAX 	Object parallax 	Double

## Notes & Assumptions

PMRA, PMDEC, PARALLAX are set to 0.0 (no Gaia values provided).

RESOLUTION = 1 corresponds to LRS.

EXTENT_PARAMETER is computed from effective radius (re) multiplied by the pixel scale 0.55 arcsec/pix.

RULESET was assigned uniformly as ST_RULESET_LRS; finer ruleset splitting by magnitude is possible but optional.

All calibration columns (CAL_MAG_*) are placeholders filled with 0.0.

## Sample Definition

The 738 galaxies included in this catalogue are red and low-Sérsic systems selected from S-PLUS photometry and structural measurements:

Colour cut: 

(u−r)>2.3, ensuring that the sample contains red galaxies.

Structural cut: Sérsic index in the r-band 

n_r<2.5, selecting galaxies with disc-like or transitional morphologies.

Photometric system: The S-PLUS r filter is designed to be SDSS r-like, ensuring compatibility with Sloan Digital Sky Survey measurements.

This combination of photometric and structural criteria identifies galaxies that are already evolving away from LTG population, making them suitable transition/quenched candidates for spectroscopic follow-up with 4MOST LRS.
