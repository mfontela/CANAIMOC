# CANAIMOC

Carbon cycle in the ocean - Methods to estimate anthropogenic carbon


*Marcos Fontela (CCMAR)*


**List of resources for the 2021 CANAIMOC Workshop**

* Biogeochemical back-calculation phi_Cant method [Download toolbox](http://oceano.iim.csic.es/_media/cantphict0_toolbox_20190213.zip)

* Seawater carbon calculations in Matlab with [CO2SYS](https://github.com/jamesorr/CO2SYS-MATLAB/archive/master.zip) from [James Orr Github](https://github.com/jamesorr/CO2SYS-MATLAB)

* [GLODAPv2.2020 Data Product for the Atlantic Ocean](https://www.ncei.noaa.gov/data/oceans/ncei/ocads/data/0210813/GLODAPv2.2020_Atlantic_Ocean.mat)(in *.mat* extension): 

* **R packages**: *(run this chunk of code from any R console)*

        #This step install packages when needed
        list.of.packages <- c("R.matlab", "rlist", "tidyverse", "readxl", "marmap", "seacarb", "xlsx", "reshape2", "Imap", "patchwork", "ncdf4", "lubridate", "plotly")
        new.packages <- list.of.packages[!(list.of.packages %in% installed.packages()[,"Package"])]
        if(length(new.packages)) install.packages(new.packages)
