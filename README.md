[![Install](https://github.com/nogibjj/Diego_Rodriguez_Individual_Project1/actions/workflows/hello.yml/badge.svg)](https://github.com/nogibjj/Diego_Rodriguez_Individual_Project1/actions/workflows/hello.yml)
[![Format](https://github.com/nogibjj/Diego_Rodriguez_Individual_Project1/actions/workflows/format.yml/badge.svg)](https://github.com/nogibjj/Diego_Rodriguez_Individual_Project1/actions/workflows/format.yml)
[![Lint](https://github.com/nogibjj/Diego_Rodriguez_Individual_Project1/actions/workflows/lint.yml/badge.svg)](https://github.com/nogibjj/Diego_Rodriguez_Individual_Project1/actions/workflows/lint.yml)
[![Test](https://github.com/nogibjj/Diego_Rodriguez_Individual_Project1/actions/workflows/test.yml/badge.svg)](https://github.com/nogibjj/Diego_Rodriguez_Individual_Project1/actions/workflows/test.yml)
# Exploratory Analysis Using Pandas to Markdown
## File Structure 
```
Pandas_to_Report/
├── .devcontainer/
│   ├── devcontainer.json
│   └── Dockerfile
├── .github/
│   ├── workflows/hello.yml
|   ├── workflows/format.yml
|   ├── workflows/lint.yml
|   └── workflows/test.yml
├── Images/
│   ├── plot.png
|   └── test_plot.png
├── mylib/
|   └── lib.py
├── .gitignore
├── Data_summary.md
├── main.ipynb
├── main.py
├── Makefile
├── README.md
├── requirements.txt
├── test_lib.py
├── test_main.py
└── test.csv
```
## Youtube video
[Walkthrough the project](https://www.youtube.com/watch?v=V1b-8KlwHVU)

## Purpose of project
The purpose of this project is to present some transformation of data using Pandas. This repository use data from the World Bank, World Development Indicator dataset and automating the publishing process into Data_summary.md with CI/CD. 


## Visualizations
Here is a scatter plot:

![scatter_plot](images/plot.png)

Plot result can be found under Images folder and a complete summary of the information under Data_summary.md.

## Some summary statistics:
Describe GDP per capita (constant 2010 US$):
|statistics | value |
| -------- | ------------ |   
|count       | 198.000000 |
|mean      | 15335.724729 |
|std       | 22881.307340 |
|min         | 228.432544 |
|25%        | 1844.387439 |
|50%        | 6134.939066 |
|75%       | 17654.996438 |
|max      | 189464.583635 |

Describe Mortality rate, infant (per 1,000 live births):
| Statistics | Value |
| ----- | ----- |
| count | 193.00 |
| mean | 23.40 |
| std | 21.06 |
| min | 1.70 |
| 25% | 6.50 |
| 50% | 15.50 |
| 75% | 35.10 |
| max | 91.60 |

## Requirements
1. DevOps
   
   black ==22.3.0
   
   click == 8.1.3

   pytest == 7.4.0

   pytest-cov == 4.0.0

   nbval==0.10.0
   
2. Linter

   ruff==0.0.284

   boto3==1.24.87

3. Web

   fastapi == 0.85.0

   uvicorn == 0.18.3

4. Analytics

   pandas == 2.2.2

   numpy == 2.1.0

   seaborn == 0.13.2

   jupyter == 1.0.0

   tabulate==0.9.0

## Testing and Linting
Testing files go with the name test_* and work for main and library files. 
<img width="1059" alt="image" src="https://github.com/user-attachments/assets/17579751-3ff5-4ebd-b2dd-b3b51c4406d4">

