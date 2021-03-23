# Analysis

All analyses have been done in the [Jupyter Notebook](https://jupyter.org/) [`Analysis.ipynb`](https://github.com/manual-testing-study/manual-testing-esec-fse-21/blob/main/analysis/Analysis.ipynb).
To reproduce all plots that we report in the paper, re-run the notebook to generate the graphs based on the [survey results](https://github.com/manual-testing-study/manual-testing-esec-fse-21/blob/main/survey/survey-answers_anonymized.xlsx).

## Prerequisites

To run the notebook, make sure to fulfill the following prerequisites:
- Python 3.6+
- Jupyter Notebook (`pip3 install notebook`)

## Setup

To install all required Python packages, run (ideally in a [virtual environment](https://docs.python.org/3/tutorial/venv.html)):
```shell script
$ pip3 install -r requirements.txt
# or directly
$ pip3 install pandas numpy matplotlib openpyxl
```

## Output

When running the cells of the notebook, the plots are by default stored as PDF files in the location of the notebook and contain the respective research question in the file name (e.g., `rq1-2.pdf` for the plot related to RQ1.2).
