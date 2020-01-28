# 01_NTU_workshop_R_notebook
## Requirements
 ### 1. Operating system
 There is no special requirement for the system type. If your system supports Java and R you should be able to run the case. The R markdown notebook was tested on linux based system (openSUSE Leap 15.0 and 15.1), but you should be able to run it on Windows and Mac based machines.
 ### 2. Software
 In order to run R notebook you should install __R__, __RStudio__ and __Java__.  
 Please follow the instruction at https://htmlpreview.github.io/?https://github.com/jszlek/01_NTU_workshop_R_notebook/blob/master/PLGA_MPS_Notebook.html section `Installation of R (and Rstudio)`. Following packages are required through the R console or RStudio package manager: `corrplot`, `devtools`, `DT`, `dplyr`, `ggplot2`, `Hmisc`, `h2o`, `iml`, `knitr`.
 According to h2o.ai website (http://docs.h2o.ai/h2o/latest-stable/h2o-docs/welcome.html) Java 8, 9, 10, 11, 12, and 13 are supported. We will be running  binary package of H2O so JRE is required.  
  If you wish to run the case on your machine please clone or download the repository (https://github.com/jszlek/01_NTU_workshop_R_notebook) and open Rmd file via RStudio.  
 ### 3. Hardware
 Please, be advised that running H2O server can cause your machine to _freeze_ or even _crash_, if it has not enough resources (RAM and/or CPUs). If you wish to use the notebook on your own data sets please carefully set the `memFreeG` variable not to exceed your free RAM.
 
 ## Preview  
In order to view the case as an html file please follow the link  
https://htmlpreview.github.io/?https://github.com/jszlek/01_NTU_workshop_R_notebook/blob/master/PLGA_MPS_Notebook.html

If something goes wrong and you will have troubles in getting everything running, please do not hesitate to contact me: j.szlek[at]uj.edu.pl
