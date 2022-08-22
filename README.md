# FOSS4G PH 2016 GeoPython Workshop
Notebook url: [https://nbviewer.jupyter.org/github/lkpanganiban/geopython-tutorial/blob/master/GeoPython%20Workshop.ipynb](https://nbviewer.jupyter.org/github/lkpanganiban/geopython-tutorial/blob/master/GeoPython%20Workshop.ipynb)

## Setup Guide
### Windows
1. Download Miniconda with the appropriate version for your operating system (32 or 64 bit)  using the following link: [http://conda.pydata.org/miniconda.html](http://conda.pydata.org/miniconda.html) Download the Python 3.x version.
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
5. Test if you have installed the jupyter notebook. Type the following in your command prompt <br />
   `jupyter notebook` <br />
   This will open a web browser. If the command does not open up browser just open your browser and go to http://localhost:8888
6. You should now see the jupyter notebook running in your browser.

### Linux
1. Create a virtualenv.
2. Install the dependencies by running `pip install -r requirements.txt`.
3. Run the `Jupyter` notebook by executing `jupyter notebook`.
4. open your browser and go to http://localhost:8888


## Reminders
 - Bring your Laptop
 - Laptop Charger
 - Internet Dongles
 - Yourself
