# Dog app project
This project is a part of Udacity's Deep learning course: Convolutional Neural Network(CNN) and Transfer learning

The purpose of this project for the students(me) to be able to implement CNN and transfer learning by themselves. We will be trying to train the model from scratch first and then use transfer learning from pre-existing model (VGG16). The result will be an app that detects a human(openCV face detector) and try predict which breed that person most resembles.


## Files included
* dog_app_reviewed.ipynb
* requirement.txt - contains pip packages. 

## Installation
* To use this on your local system - install (miniconda)[https://docs.conda.io/en/latest/miniconda.html]

* Open **Anaconda prompt** and install git:

  ``` conda install git ```

* Clone the repository and navigate to the folder.

  ``` git clone https://github.com/PwMarkLiu/TV-script-generator.git ```

* Create a new environment `deep-learning`
  - for Windows:
``` 
    conda create --name deep-learning python=3.6
    activate deep-learning 
```

* Install PyTorch and torchvision;
  - for Windows:
```
    conda install pytorch -c pytorch
    pip install torchvision
```

* Install pip packages in the `requirement.txt`
```
    pip install -r requirements.txt
```

* You can now navigate to the notebook and start using it.

