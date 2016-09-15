# gitpybeauty
Run through all files committed by git users within the last week and return code statistics as a table. Uses flake8 as the code analysis tool. The number of warnings per lines of python are taken as the metric ("prettiness"). There is commented code to analyse ipython notebooks, however this seems to skew the numbers (sometimes notebooks contain many standard one-liners, therefore less errors).

#Installation

```
pip install -r requirements.txt
```

# Running
Change into a code repository containing python code. 

```
./code_analysis.sh
```

