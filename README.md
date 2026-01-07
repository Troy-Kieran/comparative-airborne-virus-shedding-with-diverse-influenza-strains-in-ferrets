## Overview
R code used to perform statistical analyses and create figures as part of this research study and manuscript on the comparative evaluation of airborne influenza virus shedding in ferrets. 

## Code Usage
Source_Data directory contains the source data used to make manuscript Figure 1, created in GraphPad Prisim v10.5.0, as well as for supplemental figures 1 and 2, along with a PNG file for import and use with figpatch in R and all other source data for analysis and figure creation in R. 

AR_analysis.R script is self contained. Requires the relevent R packages installed, found in the script and in the section below. Whole script should only take a few minutes to run. However, output commands such as figure outputs using ragg has been commented out to make the output of figure files optional.  

## Manuscript
Pulit-Penaloza JA, Kieran TJ, Brock N, Belser JA, Sun X, Zeng H, Pappas C, De La Cruz JA, Hatta Y, Di H, Davis CT, Tumpey TM, Maines TR. Advancing A(H5N1) influenza risk assessment in ferrets through comparative evaluation of airborne virus shedding patterns. (Under Review).

## Manuscript Abstract
Recent zoonotic outbreaks of highly pathogenic avian influenza A(H5N1) viruses in North America, particularly those linked to poultry and cattle, have underscored the urgent need to assess the pandemic potential of emerging strains. In this study, we investigated the pathogenesis, transmission dynamics, and airborne virus shedding of two B3.13 and two D1.1 genotype A(H5N1) viruses isolated from humans in 2024 using the ferret model. All four viruses caused severe, rapidly progressing systemic disease with high mortality following intranasal inoculation. One B3.13 genotype virus transmitted efficiently in the presence of direct contact, resulting in fatal outcomes in all exposed ferrets, whereas one D1.1 genotype virus showed limited transmission, with one of three contacts developing clinical signs of infection and another seroconverting to the challenge virus. None of the four strains tested transmitted via respiratory droplets. To better understand the relationship between viral replication and transmission potential, we conducted aerosol sampling using two air collection platforms (BC251 and SPOT) and expanded our virus panel to include additional A(H5N1), A(H9N2), A(H7N9), and A(H1N1)pdm09 strains with known differences in airborne transmissibility. Quantitative analysis of nasal wash and air samples revealed a strong correlation between viral loads in the respiratory tract and levels of airborne virus shedding, particularly for viruses known to transmit efficiently in ferrets. Although not airborne-transmissible in this study, B3.13 viruses exhibited significantly higher predicted airborne transmission potential than D1.1 viruses, based on greater amounts of infectious virus detected in the air, consistent with previously tested B3.13 strains that demonstrated limited airborne spread in the ferret model. These findings highlight the value of integrating quantitative measurements of virus shedding in the air with observed transmission outcomes to improve the resolution of pandemic risk assessments. This approach can help identify zoonotic influenza viruses that may be undergoing adaptation toward mammalian transmissibility, even in the absence of detectable airborne spread.

## Verified versions used
R version 4.4.0 (2024-04-24 ucrt)
Platform: x86_64-w64-mingw32/x64
Running under: Windows 11 x64 (build 26100)

Matrix products: default

locale:
[1] LC_COLLATE=English_United States.utf8  LC_CTYPE=English_United States.utf8   
[3] LC_MONETARY=English_United States.utf8 LC_NUMERIC=C                          
[5] LC_TIME=English_United States.utf8    

time zone: America/New_York
tzcode source: internal

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] patchwork_1.3.0 tidylog_1.1.0   lubridate_1.9.3 forcats_1.0.0   stringr_1.5.1  
 [6] dplyr_1.1.4     purrr_1.0.2     readr_2.1.5     tidyr_1.3.1     tibble_3.2.1   
[11] ggplot2_3.5.1   tidyverse_2.0.0

loaded via a namespace (and not attached):
 [1] gtable_0.3.5      compiler_4.4.0    Rcpp_1.0.13       tidyselect_1.2.1 
 [5] magick_2.8.5      scales_1.3.0      figpatch_0.3.0    R6_2.5.1         
 [9] generics_0.1.3    munsell_0.5.1     pillar_1.10.2     tzdb_0.4.0       
[13] rlang_1.1.4       stringi_1.8.4     timechange_0.3.0  cli_3.6.3        
[17] withr_3.0.1       magrittr_2.0.3    grid_4.4.0        rstudioapi_0.16.0
[21] hms_1.1.3         clisymbols_1.2.0  lifecycle_1.0.4   vctrs_0.6.5      
[25] glue_1.8.0        farver_2.1.2      colorspace_2.1-1  tools_4.4.0      
[29] pkgconfig_2.0.3  

Other:
ragg_1.3.3
rstatix_0.7.2
figpatch_0.3.0


##
##
##
  
## Public Domain Standard Notice
This repository constitutes a work of the United States Government and is not
subject to domestic copyright protection under 17 USC § 105. This repository is in
the public domain within the United States, and copyright and related rights in
the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
All contributions to this repository will be released under the CC0 dedication. By
submitting a pull request you are agreeing to comply with this waiver of
copyright interest.

## License Standard Notice
The repository utilizes code licensed under the terms of the Apache Software
License and therefore is licensed under ASL v2 or later.

This source code in this repository is free: you can redistribute it and/or modify it under
the terms of the Apache Software License version 2, or (at your option) any
later version.

This source code in this repository is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE. See the Apache Software License for more details.

You should have received a copy of the Apache Software License along with this
program. If not, see http://www.apache.org/licenses/LICENSE-2.0.html

The source code forked from other open source projects will inherit its license.

## Privacy Standard Notice
This repository contains only non-sensitive, publicly available data and
information. All material and community participation is covered by the
[Disclaimer](DISCLAIMER.md)
and [Code of Conduct](code-of-conduct.md).
For more information about CDC's privacy policy, please visit [http://www.cdc.gov/other/privacy.html](https://www.cdc.gov/other/privacy.html).

## Contributing Standard Notice
Anyone is encouraged to contribute to the repository by [forking](https://help.github.com/articles/fork-a-repo)
and submitting a pull request. (If you are new to GitHub, you might start with a
[basic tutorial](https://help.github.com/articles/set-up-git).) By contributing
to this project, you grant a world-wide, royalty-free, perpetual, irrevocable,
non-exclusive, transferable license to all users under the terms of the
[Apache Software License v2](http://www.apache.org/licenses/LICENSE-2.0.html) or
later.

All comments, messages, pull requests, and other submissions received through
CDC including this GitHub page may be subject to applicable federal law, including but not limited to the Federal Records Act, and may be archived. Learn more at [http://www.cdc.gov/other/privacy.html](http://www.cdc.gov/other/privacy.html).

## Records Management Standard Notice
This repository is not a source of government records, but is a copy to increase
collaboration and collaborative potential. All government records will be
published through the [CDC web site](http://www.cdc.gov).
