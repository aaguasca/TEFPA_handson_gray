Hands-on session of TEFPA about the analysis of very-high-energy gamma-ray sources using Gammapy

## Install

- You will need to install [miniconda](https://docs.conda.io/en/latest/miniconda.html) (recommended) or [anaconda](https://www.anaconda.com/distribution/#download-section) first. 

- Clone the repository
```
git clone https://github.com/aaguasca/TEFPA_gray_handson.git
cd TEFPA_gray_handson
```
Or download it without git as follows: On the main page of the repository, in the top right of the webpage, press CODE (green button) and click the "Download ZIP" option at the bottom of the pop-up options. Move the zip file to the desired location and decompress it. Open a terminal and `cd` to the TEFPA_gray_handson directory. 

- Create and activate the gammapy v1.0 environment
If you use Windows, use (once inside the TEFPA_gray_handson directory):
```
conda env create -f gammapy-1.0-environment_windows.yml
conda activate gammapy-1.0
```
Else,
```
conda env create -f gammapy-1.0-environment.yml
conda activate gammapy-1.0
```
