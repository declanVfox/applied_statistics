# Applied Statistics Assessments
**by Declan Fox**

This repository contains 2 Jupyter notebooks that perform various statistical analyses.

`Project.ipynb`

This notebook analyzes the [PlantGrowth R dataset](https://vincentarelbundock.github.io/Rdatasets/csv/datasets/PlantGrowth.csv). Here are some of the tasks it performs:

- Provides an overview of the dataset.
- Explains what a t-test is, how it works, and its assumptions.
- Conducts a t-test to determine if there is a significant difference between the treatment groups.
- Performs ANOVA to check for significant differences among the three groups: ctrl, trt1, and trt2.
- Explains why ANOVA is more appropriate than multiple t-tests when comparing more than two groups.

`Tasks.ipynb`

This notebook contains additional smaller tasks related to statistical concepts:

- Analyzes the lady tasting tea experiment.
- Assesses whether numpy.random.normal() generates normal values and uses scipy.stats.shapiro() to test for normality.
- Calculates the t-statistic using Python and compares it to the value given by scipy.stats.
- Estimates the probability of committing a type II error in specific circumstances.

## Running the Notebooks

### Using Visual Studio Code and Anaconda

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/PlantGrowth-Analysis.git
    ```
2. Navigate to the repository:
    ```bash
    cd PlantGrowth-Analysis
    ```
3. Open Visual Studio Code:
    ```bash
    code .
    ```
4. Ensure you have Anaconda installed and create a new environment:
    ```bash
    conda create --name plantgrowth-analysis python=3.x
    conda activate plantgrowth-analysis
    ```
5. Install the required packages:
    ```bash
    conda install pandas scipy statsmodels jupyter
    ```
6. Open the Jupyter notebooks from Visual Studio Code.

### Using GitHub Codespaces

1. Open the repository on GitHub.
2. Click on the `Code` button and select `Open with Codespaces`.
3. If you don't have a Codespace, create a new one.
4. Once the Codespace is ready, open the Jupyter notebooks directly in the browser.
