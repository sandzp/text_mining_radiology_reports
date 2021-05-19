# Text Mining Radiology Reports

The task was to iterate through a zipped directory of multi-modal text files (including further zipped directories) containing synthetically generated radiology reports (CSV, Pickle and JSON) for patients with heart failure and extract the RV/LV ratios for each report which appear after a keyword. 

**e.g.** "The mean RV/LV ratio for this patient was 3.45..." or "RV:LV was 4.561 for this patient..." 

Though synthetic, this dataset reflected the general variabilty and ambiguity present in real life radiology reports. 

Once extracted the ratios were to be compiled and a mean ratio for all the reports was to be calculated and a histogram plotted.

Solutions:

![](https://github.com/sandzp/text_mining_radiology_reports/blob/main/figure1.png)

The mean RV/LV ratio, calculated from 83222 reports is 1.201


