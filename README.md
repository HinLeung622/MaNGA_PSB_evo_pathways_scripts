# Publicly available scripts associated with Leung et al. 2025
Link to paper: pending DOI

This repository contains 7 scripts in the folder `scripts`. Five of which are used to reproduce figures 3-7 of the paper, while the last two scripts are demonstrations of how to use `Bagpipes` to perform the fits following the method detailed in the paper, both for the PSB and central regions.

Some of the data required for these scripts are not stored here. They can be found at pending url. After downloading files from there, the file struction should look like the following:
```
.
├── data
│   ├── peng2015                                # data from Peng et al. 2015 MZ relation
│   ├── stacked_spectrum_PSB                    # directory where all the stacked spectra and additional masking files of PSB regions of RPSBs live
│   ├── stacked_spectrum_central                # directory where all the stacked spectra and additional masking files of central regions of RPSBs live
│   ├── PSB_selection_visibility                # directory containing 3 .npy files that are used to calculate the PSB selection probabilities
│   ├── posterior_percentiles_CPSB.csv          # table of the 16th, 50th and 84th percentiles of a list of fitted properties of the CPSB sample
│   ├── posterior_percentiles_RPSB_PSB.csv      # same as above, but for the PSB regions in RPSBs
│   ├── posterior_percentiles_RPSB_central.csv  # same as above, but for the central regions in RPSBs
│   ├── posterior_samples_CPSB.csv              # table of the individual posterior draw values of a list of fitted properties of the CPSB sample
│   ├── posterior_samples_RPSB_PSB.csv          # same as above, but for the PSB regions in RPSBs
│   ├── posterior_samples_RPSB_central.csv      # same as above, but for the central regions in RPSBs
│   ├── Table1.csv                              # Machine readable version of Table 1 in the paper
│   ├── Table3.csv                              # Machine readable version of Table 3 in the paper
│   ├── Table4.csv                              # Machine readable version of Table 4 in the paper
│   └── skylines.txt                            # table of skyline wavelength, width and flux, adopted from Hanuschik 2003 https://ui.adsabs.harvard.edu/abs/2003A%26A...407.1157H/abstract
├── pipes                                       # Output files from bagpipes
├── plots                                       # plots saved by scripts in this repository
└── scripts                                     # The seven scripts
    ├── code_bits                               # a collection of .py files that adds additional functionalities to the base bagpipes build developed for this study
    ├── fit_functions_demo_PSB.ipynb
    ├── fit_functions_demo_central.ipynb
    ├── fig3_example_fitting_plots.ipynb
    ├── fig4_CPSBvsRPSB_SFH_scatter.ipynb
    ├── fig5_CPSBvsRPSB_MZR.ipynb
    ├── fig6_RPSBvsCentral_sfh.ipynb
    └── fig7_RPSBvsCentral_burstage_vs_halftime.ipynb
```
