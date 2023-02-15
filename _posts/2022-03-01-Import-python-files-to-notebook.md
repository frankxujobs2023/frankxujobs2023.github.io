## How to import python files into a jupyter notebook?
>**Ans**: There are mutiple ways to address this issue. The best solution is install the python file as a package.


Suppose the python file names functions.py, you can access functions.py file from any iPython notebook located in any place, but at the given environment (kernel).
Once you changed any function in functions.py file, you don't need to reload your iPython notebook again and again. It will automatically reload every change.
This is the way how it can be done:

1. Create setup.py file in your project folder

2. Activate your virtual environment, go to your project location, and use this command 
`pip install -e .`

3. add following codes in your iPython notebook:
```python
%load_ext autoreload
%autoreload 2
```
