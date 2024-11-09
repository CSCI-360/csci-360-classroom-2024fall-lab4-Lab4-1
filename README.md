
# CSCI360 (2024 Fall) Lab4


## Installation
No additional libraries required besides the ones used in lab3. If you want to create a brand new environment for lab 4, use commands:
```
conda create -n csci360_lab4 python=3.8
conda activate csci360_lab4
pip install -r requirements.txt
```
Or, you can install new libraries to previous environment with commands:
```
conda activate [PREVIOUS_ENV_NAME]
pip install -U scikit-learn
pip install pandas
pip install matplotlib
```

## Instructions
- Both main part and extra credit of Lab 4 are in `lab4.ipynb`. You should have Jupyter Notebook installed back to Lab 0. If not, please run command in your current environment `conda install -c anaconda jupyter`.
- We provide skeleton code in `lab4.ipynb`. You are required to fill blanks in between `# ===== XXX ===== #` and `# ===== End of XXX ===== #`. If the next block starts with `# TEST ...`, your program should pass all assertions.


## FAQ
### Rules of helper function/class
Write inside `# ===== XXX ===== #` blocks where you will use. When grading, we will call each block once from top. If we encounter an error because you place functions in a later block, we are not going to give points back during regrading (even major point deduction due to syntax error). Note that some compiled functions are saved in memory temporarily so you never get error if you once called the block later.


### How we will grade
Please check instruction PDF for point assignment. We will not disclose further detailed rubrics.
