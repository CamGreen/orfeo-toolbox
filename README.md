# OTB guided tour

## Teachers part

1. Install VirtualBox https://www.virtualbox.org/
2. Download the Ubuntu Budgies iso https://ubuntubudgie.org/downloads
3. Download the OTB standalone package https://www.orfeo-toolbox.org/download/
4. Download the Miniconda installer https://docs.conda.io/en/latest/miniconda.html
4. Create Virtual Machine (2048Mo, VMDK, 15Gio) and install VirtualBox Guest Additions
5. Install librairies and softwares
    - Miniconda : ./Miniconda3-latest-Linux-x86_64.sh
    - Create otb env : conda create -n otb python=3.5 numpy rasterio jupyter matplotlib gdal
    - Install ipyleaflet : pip install --user ipyleaflet + 
    - OTB : ./OTB-6.6.1-Linux64.run --target /home/otb/OTB
    - Jupyter :
6. Configure network settings (proxy & certificates) for CNES environment.
   Instructions from : https://gitlab.cnes.fr/hpc/wikiHPC/wikis/connexion-proxy
   and https://gitlab.cnes.fr/hpc/wikiHPC/wikis/Acc%C3%A8s-%C3%A0-un-site-https-hors-master-CNES
7. Add dataset


**Note:** Python3 workaround (https://gitlab.orfeo-toolbox.org/orfeotoolbox/otb/issues/1540)

## Training kit

### Libraries and softwares

### Dataset

### Notebook

## Students part

1. Install VirtualBox https://www.virtualbox.org/
