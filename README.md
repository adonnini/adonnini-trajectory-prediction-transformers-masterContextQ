## Set up
a) Create a working directory to hold the contents of ```adonnini-trajectory-prediction-transformers-masterContextQ```

b) Add executorch to the working directory following the instructions in
https://pytorch.org/executorch/stable/getting-started-setup.html

c) In the executorch direcotry, run the following commands to install pacakges necessary in order to train the model
pip install matplotlib scikit-learn scipy pydantic
pip install wheel
python3 setup.py bdist_wheel
pip install -U pip setuptools ruamel-yaml pyyaml PyYaml
pip install scipy geopandas pygeos transformers gensim
pip install scipy geopandas pygeos transformers gensim

## Running the Training and Evaluation Loop
1. Create a \models folder in the working directory.
2. In the working direcotry, execute the train-minimum.py script. 

Validation after every epoch has been disabled as it intefered with torchscript execution (when torchscript was enabled).


  

