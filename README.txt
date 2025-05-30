Specularia v1.0

Specularia version 1.0 is a Grasshopper/Rhino plugin designed to simulate daylight in the PAR range and output a daily light integral which may be used to assess a space for plant-centric lighting. Specularia allows architects, lighting designers, researchers, and other interested parties to accurately assess the impact of design choices on agricultural lighting by dynamically simulating environmental changes for a given design space. Specularia uses the Radiance engine for simulations; the source code for Specularia is forked from Lark Spectral Lighting, an open-source plugin used to simulate circadian/non-visual metrics in built environments. Specularia provides components for simulations in both 3- and 9-channels and provides outputs for photopic lux, photosynthetically active radiation (PAR), and daily light integral (DLI). 

Specularia was developed as a collaboration between Bryant Callahan, Mehlika Inanici, Ph.D., and Gundula Prosch (University of Washington). 

The wavelength intervals used to parse the channels for 3- and 9-channel divisions are as follows: 

3 channel
R 587 780
B 499 587
B 380 499

9 channel
R1 700 780
R2 643 700
R3 587 643
G1 558 587
G2 529 558
G3 499 529
B1 449 499
B2 399 449
B3 380 399

Installation instructions:
On a Windows machine, install:
Rhino3D v6 or later (https://www.rhino3d.com/)
Radiance v5.4a (2021-02-07) Pre-release (tag: e87d63a4) or later (https://github.com/LBNL-ETA/Radiance/releases)
Ladybug v0.0.69 or later and Honeybee v0.0.66 or later [Legacy Plugins] (https://www.food4rhino.com/en/app/ladybug-tools) 
Follow the installation instructions for Ladybug/Honeybee (including the installation of Daysim v4.0) 
If you cannot find the FalseStartToggle after installing the Legacy Plugins, also install Ladybug Tools 1.5.0 or later (https://www.food4rhino.com/en/app/ladybug-tools)
In Windows, search for “Edit the system environment variables”, and make sure that for the “PATH” and "RAYPATH" variables, the Radiance installation directory paths (C:\Radiance\bin and C:\Radiance\lib) are at the top of the list, above any other path of software using Radiance such as Daysim. Once you saved the environment variables, open the terminal and type e.g. “where gendaylit”. The first path displayed should be the one of your original Radiance directory (C:\Radiance\bin\gendaylit.exe).
Go to https://www.food4rhino.com/en/app/specularia and download Specularia v1.0. Unzip the file.
Open Rhino and type "Grasshopper" into the command line (without quotations). Wait for grasshopper to load.
Select and drag all the userObject files (.ghuser) from the Specularia_v1 folder you downloaded onto your grasshopper canvas. You should see a Specularia tab appear on the Grasshopper tool bar.
Restart Rhino and grasshopper. You now have a fully-functioning Specularia v1.0. You can open and use the provided example 3D model (.3dm), example simulation inputs, and one of the three templates (.gh) as a starting point for your simulations.

Links:
Specularia Knowledgebase 
Specularia Github Repository

Software:
Available online at: https://www.food4rhino.com/en/app/specularia 