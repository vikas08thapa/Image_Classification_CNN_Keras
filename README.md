# Image_Classification_CNN_Keras

* This Repository shows the Implementation of the Image Classification by using Convolutional Neural Network In keras.
* Following are the required modules for this Project.

# step 1 Make an environment.

* Make Virtual Environment in pyhton

* This steps helps when you have to work on multiple version of the Library. Hence it is suggested to make an virtual environment.

* Make using conda install

`conda create -n environment_name python=3.7`

* Replace environment_name with your choice

# Activate the environement

* For Linux
`$ source activate environment_name`  for deactivation `$ source deactivate` or `conda deactivate`

# Step 2 Install required modules

* Tensorflow

* CPU version `conda install -c anaconda tensorflow = 1.15` GPU version  `conda install -c anaconda tensorflow-gpu`

* Keras installation

* CPU version `conda install -c anaconda keras` GPU version  `conda install -c anaconda keras-gpu`

# Step 3 Training

* Download mnist data from **http://yann.lecun.com/exdb/mnist/** or use any other dataset
* Put the images in DATA folder and chanage the training.py parameters *img_width, img_height = 28, 28* change the width and height according to image.

* classes_num = 10 *change according to your classes here its for mnist hence its 10*
* run `$ python Training.py` **you can change the number of epochs also the test the accuracy.**

# step 4 Testing
* Put the data under validation directory
* change the * img_width, img_height = 28, 28* according to your image width and height
* run `$ python Testing.py`


