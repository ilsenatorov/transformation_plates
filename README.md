## Instructions

Calculate the transformation efficiencies for each team's preparation.
Calculate the transformation efficiencies for each strain/protocol category. There should be 6 in total:

DH5 Alpha / FB

Mach1 T1R / FB
]
TOP10F' / FB

DH5 Alpha / P25

Mach1 T1R / P25

TOP10F' / P25

Make sure you __exclude outliers__ from your calculations, based on your colleagues' comments. This should be colony forming units per µg pUC19 DNA per aliquot (cfu/µg). For commercial cells this figure is usually larger than 10E6 (10E9 for 'ultra' competent cells).
* Do the paired high and low plates agree with each other?
Do the 10 and 100 ng transformation results lead to similar transformation efficiencies?
You can then try to answer several questions through statistics (__t-tests__, and ANOVAs where you are comparing more than 2 datasets):
* Is one protocol better than the other?
* Is one strain better than the others?


In the tutorial you will discuss your analysis and results with your tutor.

***


## How to use
To work on this code you can fork it to your own repo and then request the merge
### Instructions:
1. Download the [spreadsheet](https://docs.google.com/spreadsheets/d/11JbAbH3viqJeoCytiQdK4s_BZsxCUvCdz520vkZfTbw/edit#gid=0) from google doc __in csv format__ (the initial_data.csv might be outdated)
1. Make sure you have all the necessary packages installed. To install them run:
```bash
sudo pip3 install <packagename>
```
packages needed are: 
* matplotlib
* numpy
* scipy

3. Edit Cell 2 in the notebook, so that the lines below have the actual location of the csv you downloaded in step 1
```python
initial_data_location = '/home/ilya/Documents/uni_year3/BIOC3301/trasnformations/initial_data.csv' #location of initial speadsheet
parsed_data_location = '/home/ilya/Documents/uni_year3/BIOC3301/trasnformations/parsed_data.csv' # location of the new, better spreadsheet
```

4. Run the rest of the cells which should give you the nice graphs and data

***

If you encounter bugs please submit an issue!
