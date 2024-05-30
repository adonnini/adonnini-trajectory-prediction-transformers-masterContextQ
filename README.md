
## Set up
a) Create a working directory to hold the contents of ```adonnini-trajectory-prediction-transformers-masterContextQ```

b) Add executorch to the working directory following the instructions in
https://pytorch.org/executorch/stable/getting-started-setup.html

c) In the executorch directory, run the following commands to install pacakges necessary in order to train the model
- pip install wheel
- python3 setup.py bdist_wheel
- pip install -U pip setuptools ruamel-yaml pyyaml PyYaml
- pip install matplotlib scikit-learn scipy pydantic
- pip install scipy geopandas pygeos transformers gensim

## Running the Training Loop and Executorch Model Export
1. Create a \models folder in the working directory.
2. In the working direcotry, execute the train-minimum.py script. 

Validation after every epoch has been disabled as it intefered with torchscript execution (when torchscript was enabled).

## Notes - Please Read
i) I am new to Python. Please bear in this mind as you will probably find some (many) of the things I did not "professional"

ii) ```train-minimum.py``` is (very) messy. There are many lines which are commented out. They are iethr instructions, notes, or code which I tried and disabled because it did not work. I am sorry as this will make navigating/understanding train-minimum.py (more) difficult to navigate.

iii) I did not test the instructions in this ```readme.md``` file
  

