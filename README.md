# OSC-database

The OSC database contains  organic solar cell materials with their SMILES, HOMO, LUMO and device parameters such as open-circuit voltage (VOC), short circuit current (JSC), a fixed fill factor (FF) and PCE were present in the dataset.

The GUI was made to aid the organization and reuse of the OSC database. The SQLite database was integrated in the GUI. The database can be read, updated, deleted by the GUI. Moreover, users can look for target materials and properties by searching their names or source article titles, authors or DOIs in the search box of the GUI. The updated database can be exported as a CSV file, which can be used to explore the relationship between molecular structures, molecular properties and device parameters. GUI has been packaged as user-friendly software that can be downloaded and used directly

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](https://github.com/JinYSun/OSC-database/blob/main/LICENSE)



## News!

-[Jul/26/2023] OSC database v1.0.0 include experimental dataset  curated from about 500 articles. The dataset including 1027 NFAs such as PDI, DPP, A-D-A series acceptors. If a molecule appears several times in literature, its max PCE was chosen. The type of acceptors was ignored and assuming the donors are in an optimal environment. The detailed information about molecules and their source articles can be found in GUI application. Molecules containing Si and metal atoms were removed from the datasets. 

## Installation

To use the OSC-database, firstly install wget: 
```
pip install wget
```

Install the required packages: 
```
import wget
url = "https://github.com/JinYSun/OSC-database/releases/download/v1.0.0/OSC.Database.v1.0.0.exe"

```

Run: 
```
wget.download(url)
```

or directly download the file by clicking on the [url](https://github.com/JinYSun/OSC-database/releases/download/v1.0.0/OSC.Database.v1.0.0.exe)



**Download and Installation the executable(.exe) file**

![download](Fig\download.png)



## Usage

**Overview of the OSC database**

![overview](Fig\overview.jpg)

**Query the database according to material name, article title or DOI** 
Search the exact compound name in "**Exact watch**".
Search the element or part of compound name, article title, author name or DOI in "**Generic Watch**"
Click the "**Home**" button to view the full database
Click the "**Add**" or "**Insert**" button to add your own data 
Click the "**Delete**" button to delete the undesired data; 
Click the "**Cancel**" button to return to previous operation; 
Click the "**Save**" button to save the changes.

## Acknowledgement

Jinyu Sun

E-mail: jinyusun@csu.edu.cn

