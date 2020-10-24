# mnist
My solution for kaggle [MNIST](https://www.kaggle.com/c/digit-recognizer/) contest.

## Install

 I use the [Anaconda](https://www.anaconda.com/).
 
 The following packages can be installed using the NVidia GPU.
```
$ conda install cudatoolkit cudnn
```
 Install python packages:

 For GPU:
```
$ pip install --use-feature=2020-resolver keras tensorflow-gpu
```

 For CPU:
```
$ pip install --use-feature=2020-resolver keras tensorflow
```

 Install Kaggle API: [GitHub](https://github.com/Kaggle/kaggle-api)
```
$ pip install --use-feature=2020-resolver kaggle
```
 Don't forget to setup username and access token.

 Get data:
```
$ kaggle competitions download -c digit-recognizer
```
