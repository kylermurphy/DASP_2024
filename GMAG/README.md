# GMAG 

```gmag``` is an open-source Python library to access ground-based magnetometer data. 

- [GMAG paper](https://www.frontiersin.org/articles/10.3389/fspas.2022.1005061/full)
- [GMAG Website/Docs](https://kylermurphy.github.io/gmag/)
- [GMAG repository](https://github.com/kylermurphy/gmag)

The notebooks in this tutorial will go over the basics of GMAG, loading data, accessing data & metadata, identifying stations in key locations, and plotting & basic analysis of data. 

The notebooks can be ran in either:

1. [Google Colab](https://colab.research.google.com/): this method is the simplest and requires no Python distribution, installation of any code, or downloading of data to your computer. **This is ideal if you only want to follow along with the tutorial.**
1. Locally on your computer: this method requires you to download and install the GMAG package and set your download directory. It also requires a Python distribution (I suggest Anaconda). **This is ideal if you intend on using ground-based magnetometer data.**

**If you choose to run GMAG locally follow the [Installation Instruction](#gmag-installation) below.**

**Tutorial Notebooks**

Based on your preference click the Colab link below to open the tutorial in Colab or download the Local Notebook to run the tutorial locally.

- Colab
- Local

## GMAG Installation

- Download (and unzip) the [GMAG](https://github.com/kylermurphy/gmag) github repository to your Python/Coding directory.
- Open a terminal and navigate to the GMAG directory.
    - If you've install Anacond open and ```cd``` to the GMAG directory.
- Now install the GMAG package using:
```python
pip install . 
```
- Once installed you need to rename or copy the ```/gmag/gmag_rcexample``` file to ```/gmag/gmagrc```
- Open ```/gmag/gmagrc``` and modify the ```data_dir``` variable by adding the local directory where you would like all ground-based magnetometer data to be downloaded.
- You should now be able to use GMAG. 




