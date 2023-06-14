# ATI_project

This project aims at generating floorplans of new buildings exploiting the House-GAN++ architecture.

main1.ipynb contains the connection to the mySQL database and the retrieving from it of useful data, which is going to be structured ad hoc in order to feed the GAN.
Files in data_reader folder are taken from https://github.com/sepidsh/Housegan-data-reader.git, used to read a floorplan structured as in the RPLAN dataset.
The raster_to_json function is taken from the same repository used to create the input for the GAN.

main2.ipynb contains the extraction of data exploiting speckle where the Revit projects had been uploaded. The extracted data is then processed to match the input structure of the House-GAN++ model.
