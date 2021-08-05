# FIOLA
An accelerated pipeline for Fluorescence Imaging OnLine Analysis. 

FIOLA exploits computational graphs and accelerated hardware to preprocess fluorescence imaging movies to extract neural activity at speeds in excess of 300Hz on standard fields of view for calcium imaging and at over 400Hz for voltage imaging movies.

## INSTALL
git clone https://github.com/nel-lab/FIOLA.git

cd FIOLA

conda create --name fiola python==3.8

conda activate fiola

pip install -r requirements_simple.txt

conda install spyder

pip install -e.

## Getting started 
Google colab: https://colab.research.google.com/drive/1yKoyi1Fz9bzNtOhrjuC8h12_WzWHYIvz?usp=sharing

Python demo: demo_fiola_pipeline.py
