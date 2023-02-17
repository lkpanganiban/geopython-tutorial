# PISTA NG MAPA GeoPython Workshtop
## Setup Guide
1. Download Miniconda with the appropriate version for your operating system (32 or 64 bit)  using the following link: [http://conda.pydata.org/miniconda.html](http://conda.pydata.org/miniconda.html) Download the Python 2.7 version.
2. Install Miniconda using the installer and check all the boxes when prompted. <br />
   **Note:** If you have a previous installation of python, you don't need to check the second box.
3. After installing miniconda, open your command prompt.
4. Type the following in your command prompt to install the required packages<br />
   - `conda install jupyter`
   - `conda install gdal`
   - `conda install fiona` 
   - `conda install -c http://conda.anaconda.org/scitools shapely`
   - `conda install rasterio`
   - `conda install -c http://conda.anaconda.org/ioos folium`
   - `conda install owslib`
5. Test if you have installed the jupyter notebook. Type the following in your command prompt <br />
   `jupyter notebook` <br />
   This will open a web browser. If the command does not open up browser just open your browser and go to http://localhost:8888
6. You should now see the jupyter notebook running in your browser.
