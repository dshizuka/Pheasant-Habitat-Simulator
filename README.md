# What the PHS does and why we built it:

The Pheasant Habitat Simulator makes quantitative species-habitat models accessible for conservation planning through reactively updating plots. The Pheasant Habitat Simulator was built for the specific application of a ring-necked pheasant distribution model in Nebraska, USA, but may readily be customized to other species and systems using any species-habitat regression equation. To learn more about how and why we built the pheasant habitat simulator, check out our paper in PLOS One: 

# What is contained in this repository:

The files in this reprository comprise a shiny app (To learn more about Shiny, visit: https://shiny.rstudio.com/tutorial/), an interactive R-based application.The server file controls the application workflow, while the ui determines what the user sees. The "shiny_functions" file contains functions that help build the predictive data frames and rasters displayed in the ui. The "Value_per_Acre" file contains county-specific economic valuations for evaluating the economic tradeoffs of conservation actions in agricultural landscapes.

# Disclaimers and other data sources

If you want to download a desktop-deployable version (currently for windows 7-10 only) of the app to use offline, click here: https://osf.io/yk83m/

Although these data have been processed successfully, no warranty expressed or implied is made regarding the display or utility of the data on any other system or for general or scientific purposes, nor shall the act of distribution constitute any such warranty. The USGS or the U.S. Government shall not be held liable for improper or incorrect use of the data described and (or) contained herein.


