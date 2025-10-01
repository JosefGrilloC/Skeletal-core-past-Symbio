# Skeletal-core-past-Symbio

 This repository contains the analysis code and data supporting: Grillo et al. 2025 - Coral skeletal cores as windows into past Symbiodiniaceae community dynamics. Global Change Biology (doi: )

 ## Contents
- `analysis/`: R Markdown notebook with full analysis. }
- `data/`: Processed data used in analyses.
  - **Absolute_abundance.txt**: Post-MED sequences of the reconstructed Symbiodiniaceae communities of the skeletal cores.
  - **Metadata.txt**: Raw data associated with the coral skeletal cores and Post-MED sequences including location, age and species
  - **SST_NOAA_CRW_joined:** Daily bleaching alerts obtained from the NOAA Coral Reef Watch [https://pae-paha.pacioos.hawaii.edu/erddap/griddap/dhw_5km.html]
- `figures/`: Figures generated for the manuscript.

## Raw sequence data
Raw sequences are archived at [https://www.ncbi.nlm.nih.gov/sra/PRJNA1330243]. **Note:** Raw sequences were not directly employed in this workflow

## Notes
The repository includes a Rmarkdown file (Grillo_et_al_2025.Rmd) with all the commented code and all the necessary explanations for how the analysis was performed.
A knitted html file is also included.
