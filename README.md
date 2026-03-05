# JOIS 2022
[![DOI](https://zenodo.org/badge/1173615346.svg)](https://doi.org/10.5281/zenodo.18880776)

Expedition from 15/09/2022 – 14/10/2022 on the Louis St. Laurent. Departed Cambridge Bay, Nunavut, Canada. Returned to Kugluktuk, Nunavut, Canada.

Questions regarding JOIS data should be sent to Núria Casacuberta, ETHZ: nuria.casacubertaarola@usys.ethz.ch

## Geochemistry Data
`00_j22_isotopes.xlsx` contains one sheet with the following radionuclides collected during JOIS 2022:
- Iodine-129
- Uranium-236

Samples were collected in rinsed cubitainers using the ship CTD rosette, unfiltered. Iodine and Uranium were separated by column chromatography and measured by AMS at LIP, ETHZ. Post-processing was carried out using BATS, Excel, and MATLAB.

The fields `I129_at_l`, `unc_I129_at_l`, `U236_at_l`, `unc_U236_at_l` are reported at x10⁷ for iodine and x10⁶ for uranium and do not need to be corrected.

## CTD Data
`00_j22_ctd.mat` is a MATLAB-compatible structure containing all CTD variables including pressure, salinity, and temperature.

Data sourced from the [Beaufort Gyre Exploration Project](https://www2.whoi.edu/site/beaufortgyre/data/ctd-and-geochemistry/). Questions regarding the CTD data should be directed to Sarah Zimmermann at DFO Canada: sarah.zimmermann@dfo-mpo.gc.ca
