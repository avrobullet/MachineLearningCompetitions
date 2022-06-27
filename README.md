# Machine Learning Competitions
- [Introduction](#introduction)
- [Competitions](#competitions)

## Introduction

As the name suggests, this repository is dedicated to gaining Machine Learning knowledge, however mostly through competitions hosted on sites like Kaggle. Please go to any of the following links to review my projects!

## Competitions
* [Kaggle's](https://www.kaggle.com/alexandersdouglas/competitions) **Titanic Machine Learning from Disaster challenge** where I reached the Top 15% ranked as of August 4th, 2020

## Debuggin'
Faced a weird situation on Windows where I tried to install both TensorFlow and Keras. I faced the following error message:

```
ERROR: Could not install packages due to an OSError: [Errno 2] No such file or directory: 'C:\Users\13434\AppData\Local\Packages\PythonSoftwareFoundation.Python.3.7_qbz5n2kfra8p0\LocalCache\local-packages\Python37\site-packages\sklearn\datasets\tests\data\openml\...
```
I followed the guide here to fix here  https://www.howtogeek.com/266621/how-to-make-windows-10-accept-file-paths-over-260-characters/. Apparently, it is related to a [260 character limit](https://stackoverflow.com/questions/65980952/python-could-not-install-packages-due-to-an-oserror-errno-2-no-such-file-or).