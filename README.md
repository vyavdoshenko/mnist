# mnist
My solution for kaggle [Digit Recognizer](https://www.kaggle.com/c/digit-recognizer/) Prediction Competition.

## Inspirations
- [Generative Deep Learning by David Foster](https://www.oreilly.com/library/view/generative-deep-learning/9781492041931/)
- [GitHub repository with examples for this book](https://github.com/davidADSP/GDL_code/)
- [This python notebook](https://www.kaggle.com/poonaml/deep-neural-network-keras-way/execution)
- [Image Data Generator & Data Augmentation](https://www.pyimagesearch.com/2019/07/08/keras-imagedatagenerator-and-data-augmentation/)

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
