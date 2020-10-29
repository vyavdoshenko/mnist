# mnist
My solution for kaggle [Digit Recognizer](https://www.kaggle.com/c/digit-recognizer/) Prediction Competition.

## Install

 I use the [Anaconda](https://www.anaconda.com/).
 
 The following packages can be installed using the NVidia GPU.
```
$ conda install cudatoolkit cudnn
```
 Install python packages:

 For GPU:
```
$ pip install --use-feature=2020-resolver tensorflow-gpu
```

 For CPU:
```
$ pip install --use-feature=2020-resolver tensorflow
```

For both:
```
$ pip install --use-feature=2020-resolver keras jupyter numpy pandas matplot sklearn
```

 Install Kaggle API: [GitHub](https://github.com/Kaggle/kaggle-api)
```
$ pip install --use-feature=2020-resolver kaggle
```
 Don't forget to setup the username and access token.

 Get data:
```
$ mkdir input
$ cd input
$ kaggle competitions download -c digit-recognizer
$ unzip digit-recognizer.zip
$ cd ..
```

 Start Jupiter Notebook:
```
$ jupyter notebook --ip='0.0.0.0' --NotebookApp.token='' --NotebookApp.password=''
```
