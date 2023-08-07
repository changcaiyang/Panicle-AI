# Panicle-cloud
Zixuan Teng<sup>1*</sup>, Jiawei Chen<sup>2*</sup>, Jian Wang<sup>3*</sup>, Shuixiu Wu<sup>4</sup>, Riqing Chen<sup>1</sup>, Liyan Shen<sup>2</sup>,  Robert Jackson<sup>5</sup>, Ji Zhou<sup>2,5*</sup>, Changcai Yang<sup>1,6*</sup>

<sup>1</sup>Digital Fujian Research Institute of Big Data for Agriculture and Forestry, College of Computer and Information Sciences, Fujian Agriculture and Forestry University, Fuzhou 350002, China.

<sup>2</sup>State Key Laboratory of Crop Genetics & Germplasm Enhancement, academy for Advanced Interdisciplinary Studies, Nanjing Agricultural University, Nanjing 210095, China

<sup>3</sup>Ningxia Academy of Agriculture and Forestry Sciences, Yinchuan 750002, China

<sup>4</sup>College of Mechanical and Electrical Engineering, Fujian Agriculture and Forestry University, Fuzhou 350002, China

<sup>5</sup>Cambridge Crop Research, National Institute of Agricultural Botany (NIAB), Cambridge CB3 0LE, UK

<sup>6</sup>Key Laboratory of Smart Agriculture and Forestry (Fujian Agriculture and Forestry University), Fujian Province University, Fuzhou 350002, China\

## Install Python, Anaconda and Libraries
If you wish to run Panicle-AI from source code, you will need to set up Python on your operating system. 

1. Install Python releases:
   
   •	Read the beginner’s guide to Python if you are new to the language: 
   https://wiki.python.org/moin/BeginnersGuide
   
   •	For Windows users, Python 3 release can be downloaded via: 
   https://www.python.org/downloads/windows/
   
   •	Panicle-AI only supports Python 3 onwards

2. Install Anaconda Python distribution:
   
   •	Read the install instruction using the URL: https://docs.continuum.io/anaconda/install
   
   •	For Windows users, a detailed step-by-step installation guide can be found via: 
   https://docs.continuum.io/anaconda/install/windows 
   
   •	An Anaconda Graphical installer can be found via: 
   https://www.continuum.io/downloads

   •	We recommend users install the latest Anaconda Python distribution

3. Install packages:

   • Panicle-AI uses a number of 3rd-party libraries that you may need to add to your conda environment.
   These include, but are not limited to:
   
   matplotlib>=3.2.2
   numpy>=1.18.5
   opencv-python>=4.1.2
   Pillow>=7.1.2
   PyYAML>=5.3.1
   requests>=2.23.0
   scipy>=1.4.1
   torch>=1.7.0
   torchvision>=0.8.1
   tqdm>=4.41.0
   tensorboard>=2.4.1
   pandas>=1.1.4
   seaborn>=0.11.0

   
## Running Panicle-cloud GUI

Integrated six AI models were compatible with the cloud-based runtime environment into the platform (http://ai-panicle.com:32123), including Panicle-AI, YOLOv5, VFNet, FCOS, GFLv2, and RetinaNet.
