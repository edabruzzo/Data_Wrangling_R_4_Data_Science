# Data_Wrangling_R_4_Data_Science - MBA - DATA SCIENCE & ANALYTICS - USP/ESALQ

Comandos para instalação do core do R e do RStudio no Linux -> Ubuntu 20.04

$ sudo apt-get install r-base
$ sudo apt-get install gdebi-core
$ wget https://lnkd.in/eBKzZxd2
$ sudo gdebi rstudio-server-2021.09.1-372-amd64.deb

RStudio Server
 RStudio is a set of integrated tools designed to help you be more productive with R. It includes a console, syntax-highlighting editor that supports direct code execution, as well as tools for plotting, history, and workspace management.

Created symlink /etc/systemd/system/multi-user.target.wants/rstudio-server.service → /lib/systemd/system/rstudio-server.service.
● rstudio-server.service - RStudio Server
  Loaded: loaded (/lib/systemd/system/rstudio-server.service; enabled; vendor preset: enabled)
  Active: active (running) since Sun 2021-11-28 19:22:24 -03; 1s ago
 Process: 15277 ExecStart=/usr/lib/rstudio-server/bin/rserver (code=exited, status=0/SUCCESS)
 Main PID: 15282 (rserver)
   Tasks: 3 (limit: 4915)
  CGroup: /system.slice/rstudio-server.service
          └─15282 /usr/lib/rstudio-server/bin/rserver

nov 28 19:22:24 emmanuel-HP-EliteDesk-800-G4-DM-35W-Brazil systemd[1]: Starting RStudio Server...
nov 28 19:22:24 emmanuel-HP-EliteDesk-800-G4-DM-35W-Brazil systemd[1]: Started RStudio Server.

-----
BIBLIOTECAS NECESSÁRIAS PARA INSTALAÇÃO DO PACOTE tidyverse

$ sudo apt-get install libxml2-dev

$ sudo apt-get install libcurl4-openssl-dev

$ R
> install.packages("tidyverse")

Para executar um script em R:

$ Rscript teste.R

#----------------------------------------------
Para executar o R em linha de comando:

$ R

R version 3.4.4 (2018-03-15) -- "Someone to Lean On"
Copyright (C) 2018 The R Foundation for Statistical Computing
Platform: x86_64-pc-linux-gnu (64-bit)

R is free software and comes with ABSOLUTELY NO WARRANTY.
You are welcome to redistribute it under certain conditions.
Type 'license()' or 'licence()' for distribution details.

 Natural language support but running in an English locale

R is a collaborative project with many contributors.
Type 'contributors()' for more information and
'citation()' on how to cite R or R packages in publications.

Type 'demo()' for some demos, 'help()' for on-line help, or
'help.start()' for an HTML browser interface to help.
Type 'q()' to quit R.

> q()
Save workspace image? [y/n/c]: n


http://localhost:8787/


Github: https://lnkd.in/eCwpn_3p


Links úteis para aprendizado e instalação;

https://lnkd.in/eG_mGjYU

https://lnkd.in/e-nJ4bVS

R 4 Data Science: https://lnkd.in/eyEJuRdu


