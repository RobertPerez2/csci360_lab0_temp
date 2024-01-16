# Lab0
### CSCI-360 Spring 2024

## Overview
- Due date: Jan.26 11:59pm
- You are not required to turn in this assignment and CPs will not grade whether you finish or not. You need to do quality control of your own practice.
- This assignment serves as a practice to usage of multiple libraries, softwares and Python language, which will be heavily relied on later this semester. Therefore, it is recommended for you to finish this tutorial. TA and CP's office hour will be very crowded later.

## Getting started
- __Install Anaconda__

    It is highly recommended to create separate environments for different projects (not just for this course!). Follow the guideline _2. Setting up an Integrated Development Environment (IDE)_ in instruction PDF to ensure Anaconda is ready to be called in terminal before proceeding.

- __Install conda environment__

    Open terminal and enter the following commands one line at a time.
    ```
    conda create -n csci360 python=3.10
    conda activate csci360
    pip install -r requirements.txt
    ```
    You should see something like this proceeds your username on your computer (slightly different if you are using Windows or a Linux OS): `(csci360) Computer-Name:~ User-Name$`. The name in parentheses is the name of created conda environment.

- __Deactivate or activate the environment__
    - If you want to exit current conda environment, you can deactivate it by command:
        ```
        conda deactivate
        ```
    
    - If you want to activate an existing environment (e.g., open a new terminal window for another assignment), use command:
        ```
        conda activate csci360
        ```

- __Other usage of conda__

    Check out [conda cheatsheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf).

## TODO
- The skeleton code and data are provided in local folder `data`.
- Follow `data/CSCI_360_Lab0.ipynb` and `data/Lab0_Sklearn_Pandas.ipynb`, which serve as a walkthrough of instruction PDF.

## Submit
- Again, CPs do not grade this assignment, but we recommend you to practice submission to your own Github repo.
- To submit your homework, firstly update README.md and add any comment at the very top for CP to read when they grade. For example, how many late days to use if you submit late. You can choose not to use late days and save for future homeworks, but you must specify here. Also, if you want CP to grade a previous submission/commit, you also need to specify here.
- Secondly, make sure no unwanted or big files are uploaded. To do this, you need to edit `.gitignore` file and add those file names there. `.gitignore` is sometimes hidden by OS and you can google how to find them in your case.
- Finally, you need to add everything (including other library names you used in `requirements.txt`) to stage and make a commit to push to your Github account. Confirm your submission on Github webpage shortly after you push the commit.
