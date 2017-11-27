Automated Radio Telescope Image Processing Pipeline (ARTIP) is an end to end pipeline automating the entire process of flagging, calibration and imaging.

ARTIP starts with raw data i.e. Measurement Set and goes through multiple stages like Flux Calibration, Bandpass Calibration, Phase Calibration and Imaging to generate continuum and spectral line images. Each stage can also be run independently. 

It is written using standard python libraries and the CASA package and tested against datasets (~ 6 to 30GB) produced by Giant Metrewave Radio Telescope, Pune (GMRT) , Very Large Array, NM (VLA) , Westerbork Synthesis Radio Telescope Netherlands (WSRT). Its currently being tested for the data from MeerKAT Absorption Line Survey (MALS)

Pipeline also provides ability to generate reports of processed data in graphical format.

### Obtaining ARTIP
https://github.com/TWARTIP/artip/releases

### Documentation
https://github.com/TWARTIP/artipdoc/blob/master/artip_documentation.pdf
