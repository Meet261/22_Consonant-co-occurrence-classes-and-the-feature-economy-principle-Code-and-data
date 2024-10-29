# 22_Consonant-co-occurrence-classes-and-the-feature-economy-principle-Code-and-data

https://mybinder.org/v2/gh/Meet261/22_Consonant-co-occurrence-classes-and-the-feature-economy-principle-Code-and-data/HEAD
Launch Online [![Binder](https://mybinder.org/badge_logo.svg)](https://notebooks.gesis.org/binder/v2/gh/Meet261/22_Consonant-co-occurrence-classes-and-the-feature-economy-principle-Code-and-data/HEAD)

Here is the dependency tracker for the 22nd file:

| **Serial Number** | **File Name**                          | **Dependencies**                                                                                                                                               | **Reproducibility Status** | **Issue/Obstacle**                                                                                                                                                 |
|-------------------|----------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 22                | `redraw_figures.R`      | `r-viridis`, `r-extrafont`, `r-ape`, `r-corrplot`, `r-psych`, `r-lavaan`, `r-tidyverse`, `r-knitr`, `r-rmarkdown`                                               | Not Reproducible           | 1) Font Registration Issues: The script prompts for user input during the font registration process, which is not suitable for automated environments. 2) Cairo PDF Device Error: The script fails to start the cairo_pdf device, producing the error "unable to start device 'cairo_pdf'" due to output stream writing issues. 3) File Output Issues: Errors occurred during file writing, such as "could not open file 'img_new/basic_inventory_single_linkage.png'," preventing the proper output of plots and dendrograms. |

License: CC-By Attribution 4.0 International

This project uses data and resources from [Consonant co-occurrence classes and the feature-economy principle: Code and data](https://osf.io/2qjn5/). We acknowledge the contributions of the authors of the original project. Please refer to the [Consonant co-occurrence classes and the feature-economy principle: Code and data](https://osf.io/2qjn5/) for more details.
