#Computer Vision Template Matching project 

The project will be broken up into a few main parts in one Python notebook:

## Project Instructions


### Amazon Web Services

This project benefits from the use of GPU acceleration to run more efficiently. Please refer to the instructions for setting up a GPU instance for this project,https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html


### Local Environment Instructions


1. Clone the repository, and navigate to the downloaded folder.
```
git clone https://github.com/rutwikc47/skylarkcv.git
```

2. Create (and activate) a new environment with Python 3.5 and the `numpy` package.

	- __Linux__ or __Mac__: 
	```
	conda create --name skylark-cv python=3.5 numpy
	source activate skylark-cv
	```
	- __Windows__: 
	```
	conda create --name skylark-cv python=3.5 numpy scipy
	activate skylark-cv
	```

3. Install/Update TensorFlow (for this project, you may use CPU only).
	- Option 1: __To install TensorFlow with GPU support__, follow [the guide](https://www.tensorflow.org/install/) to install the necessary NVIDIA software on your system.  If you are using the Udacity AMI, you can skip this step and only need to install the `tensorflow-gpu` package:
	```
	pip install tensorflow-gpu==1.1.0
	```
	- Option 2: __To install TensorFlow with CPU support only__:
	```
	pip install tensorflow==1.1.0
	```

4. Install/Update Keras.
 ```
pip install keras -U
```

5. Switch [Keras backend](https://keras.io/backend/) to TensorFlow.
	- __Linux__ or __Mac__: 
	```
	KERAS_BACKEND=tensorflow python -c "from keras import backend"
	```
	- __Windows__: 
	```
	set KERAS_BACKEND=tensorflow
	python -c "from keras import backend"
	```

6. Install a few required pip packages (including OpenCV).
```
pip install -r requirements.txt
```


### Data

All of the data you'll need are in the subdirectory `train` and `validation` .

Now, with that data unzipped, you should have everything you need!

## Notebook

1. Navigate back to the repo. (Also your source environment should still be activated at this point)
```shell
cd
```

2. Open the notebook and follow the instructions.
```shell
jupyter notebook skylarkcv.ipynb
```

