# MakeSynthetic

## Setup

1. create a python virtual environment 

```python

python3 -m venv env_synth
```
2. activate your enviornment 
3. download the files into that new directory
4. make sure you have a data directory - this is where it will write your csv file
5. install requirements 

```python
pip3 install -r requirements.txt
```
5. run the sample make_synthetic.py 

```python
python3 make_synthetic.py config_example_110k.json                

```

It's not perfect but will generate AFD OFI ready datasets. 

the program will generate a synthietic CSV dataset with predictive performance; AND a txt summary of the file with a profile of the datset, expected performance, and variable importance 

