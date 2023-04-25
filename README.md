# XBT-WorldPlotter
*Expendable Bathythermograph data decoder and plotter*

Download *XBT_Plotter_v1.exe* and execute (Windows). MATLAB version 9.11 (R2021b) Runtime must be installed to run (https://www.mathworks.com/products/compiler/matlab-runtime.html)

With MATLAB: Copy all files to the same local directory and run *XBTPlotterApp.mlapp* in MATLAB.

**MAIN TAB**
![xbtplotter_mainTab](https://user-images.githubusercontent.com/89260258/234381162-6424236b-674c-4a09-acf1-d67c5969489f.png)
On this tab you have 2 options: (A) Work on the FTP and (B) Work with locally picked files.
(A) FTP: The ftp has a Date filter: 1st select the range of dates, so it will browse and return the list of remote files that correspond to that condition (based on the filename format YYYMMDD).
Then select among the available Callsigns. You can select multiple ships and will be plotted in different colors. Click Plot to display the map, and it will first download the binary files to the working directory, in the XBTplotter_downloads directory.
(B) Local: Select one or more files from a local directory.

MAP: Click on the map and then you can use the arrow keys, and the +/- to move or zoom in/out.
Click on any of the deployment sites to decode, plot the profile and display the metadata.

Click on the green button to export the file as ASCII in .txt format. It will be saved in the working directory path, in the XBTascii_export directory.

**CONFIG TAB**
![xbtplotter_ConfigTab](https://user-images.githubusercontent.com/89260258/234381414-16a4f2ad-6907-4614-b09f-49cce36bc331.png)
Change the ftp credentials, if we ever move the files from the current directory.
Set the Working directory where files are downloaded and exported.
Change the map type. Matlab comes with a few different maps to play with.
Change the scale factor that is used as a measure to PAN and ZOOM, in degrees [d.ddd].
Save the configuration and it will be loaded next time you use the app.

**TABLE TAB**
![xbtplotter_TableTab](https://user-images.githubusercontent.com/89260258/234381663-fdce961c-be39-4afa-a8a5-33f5598e9690.png)
Summary of all the profiles displayed in the map, with some basic metadata info

