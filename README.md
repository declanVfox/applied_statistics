# Applied Statistics Assessments
**by Declan Fox**

This repository contains 2 Jupyter notebooks that perform various statistical analyses.

The `Project.ipynb` notebook analyzes the [PlantGrowth R dataset](https://vincentarelbundock.github.io/Rdatasets/csv/datasets/PlantGrowth.csv). Here is a summary of some of the tasks carried out in it:

- Download and save the dataset to the repository.
- An overview of the dataset is provided. 
- Explanation of what a t-test is, how it works, and its assumptions.
- Conduct a t-test to determine if there is a significant difference between the treatment groups.
- Conduct ANOVA to determine if there is a significant difference among the three groups: ctrl, trt1, and trt2.
- Explanation of why ANOVA is more appropriate than multiple t-tests when comparing more than two groups.



The `Tasks.ipynb` notebook containing additional smaller tasks related to statistical concepts.

- Analysis of the lady tasting tea experiment.
- Assess whether `numpy.random.normal()` properly generates normal values and use `scipy.stats.shapiro()` to test for normality.
- Calculate the t-statistic using Python and compare it to the value given by `scipy.stats`.
- Estimate the probability of committing a type II error in specific circumstances.

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
