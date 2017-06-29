
# Pd-feature_extractor_Wek
Session five assignement - Machine Learning for musicians and artists

In order to properly use this patch you'll need first to download and install Pure Data
The installers can be found here

https://puredata.info/downloads/pure-data



The pixel_analyzer uses the pix_drum object created for Jaime Oliver specifically for the computing of his silent drum (http://www.jaimeoliver.pe/archives/731)

The pix_drum searches for blackpixels and send all sort of data. 

For the purpose of this patch, I'm using just the second outlet for extracting my features:

Side: Left or right
Index for the secondary peak
X Coordinate
Y Coordinate
