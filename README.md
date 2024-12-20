## Applied Statistics ##

# Applied Statistics Module Repository

This repository contains all the materials for the Applied Statistics module of my Higher Diploma in Data Analytics at ATU. It includes notebooks, data, and other resources for completing the assigned tasks and the main project.

## Repository Contents

- **Jupyter Notebooks**
  - `tasks.ipynb`: Contains solutions to the four assigned tasks:
    1. Permutations and combinations
    2. The normal distribution
    3. T-tests
    4. ANOVA
  - `project.ipynb`: Contains my submission for the main project, which involves analyzing the PlantGrowth R dataset using t-tests and ANOVA.

- **data Folder**: Contains the datasets used for the tasks and the main project.
- **img Folder**: Includes any images generated or used in the tasks and project.
- **.gitignore File**: Specifies files and directories to be ignored by Git.
- **requirements.txt File**: Lists the Python dependencies required to run the notebooks.

## How to Run the Notebooks

You can run the notebooks on your local machine using either Visual Studio Code and Anaconda or directly in the cloud using GitHub Codespaces.

### Option 1: Using Visual Studio Code and Anaconda

1. Clone this repository to your local machine:
   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```

2. Create a new Conda environment and install the required dependencies:
   ```bash
   conda create --name stats_env --file requirements.txt
   conda activate stats_env
   ```

3. Open the repository in Visual Studio Code.

4. Ensure the Python extension is installed in Visual Studio Code, and select your `stats_env` environment as the interpreter.

5. Open the desired notebook (`tasks_notebook.ipynb` or `project_notebook.ipynb`) and start executing the cells.

### Option 2: Using GitHub Codespaces

1. Open this repository in GitHub and click the "Code" button.

2. Select "Open with Codespaces" to create a new Codespace.

3. Once the Codespace is ready, open the desired notebook (`tasks.ipynb` or `project.ipynb`) and start executing the cells.

## Overview of Work

### Tasks
Four tasks were completed as part of this module:
1. **Permutations and Combinations**: Explored combinatorial concepts and their applications.
2. **Normal Distribution**: Analyzed the properties of the normal distribution and its relevance to data analysis.
3. **T-Tests**: Conducted statistical hypothesis testing using t-tests.
4. **ANOVA**: Performed analysis of variance to compare multiple groups.

### Main Project
The main project involved analyzing the PlantGrowth R dataset. This included:
- Describing the data-set.
- Conducting t-tests to compare means between groups.
- Using ANOVA to analyze the effect of treatments on plant growth.
- Providing general information about t-tests and ANOVA and interpreting the results of the analyses carried out in this project.

## Requirements
The Python dependencies are listed in the `requirements.txt` file. These include commonly used libraries for data analysis and statistical testing, such as:
- `numpy`
- `pandas`
- `scipy`
- `matplotlib`
- `statsmodels`





