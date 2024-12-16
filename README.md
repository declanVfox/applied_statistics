# Applied Statistics Assessments
**by Declan Fox**

## Repository Contents

This repository contains 2 Jupyter notebooks that perform various statistical analyses.

**`project.ipynb`**

This notebook analyses the [PlantGrowth R dataset](https://vincentarelbundock.github.io/Rdatasets/csv/datasets/PlantGrowth.csv). Here are some of the tasks it performs:

- Provides an overview of the dataset.
- Explains what a t-test is, how it works, and its assumptions.
- Conducts a t-test to determine if there is a significant difference between the treatment groups.
- Performs ANOVA to check for significant differences among the three groups: ctrl, trt1, and trt2.
- Explains why ANOVA is more appropriate than multiple t-tests when comparing more than two groups.

**`tasks.ipynb`**

This notebook contains additional smaller tasks related to statistical concepts:

- Analyses the lady tasting tea experiment.
- Assesses whether `numpy.random.normal()` generates normal values and uses `scipy.stats.shapiro()` to test for normality.
- Calculates the `t-statistic` using Python and compares it to the value given by `scipy.stats`.
- Estimates the probability of committing a type II error in specific circumstances.

## Getting Started

You can run the notebooks in two ways:

Using [Visual Studio Code](https://code.visualstudio.com/) and [Anaconda](https://www.anaconda.com/download)

Using [GitHub Codespaces](https://github.com/features/codespaces)

### Using Visual Studio Code and Anaconda

1. Clone the repository:
    ```bash
    git clone https://github.com/declanVfox/applied_statistics.git
     ```
2. Navigate to the repository:
    ```bash
    cd applied_statistics
    ```
3. Download and install [Visual Studio Code.](https://code.visualstudio.com/Download)
4. Download and install the [Anaconda Python Distribution](https://www.anaconda.com/download/success)
4. Open Visual Studio Code:
    ```bash
    code .
    ```
5. Install the required packages:
    ```bash
    conda install numpy matplotlib seaborn scipy pandas jupyter
    ```
6. Select Notebook

### Using GitHub Codespaces

1. Open the repository on GitHub.
2. Click on the `Code` button and select `Open with Codespaces`.
3. If you don't have a Codespace, create a new one.
4. Once the Codespace is ready, select the Jupyter notebook directly in the browser.

### Other Environments

For all other environments:

```bash
pip install -r requirements.txt
```
