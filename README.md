# rock-paper-scissors
## Dependencies
Install the required dependencies by using following command on cmd/terminal

pip install -r requirements.txt

This will install the version of libraries on which i build this project. If u want u can install the latest versions too by upgrading the installed dependencies.

## Model
I have already included my trained model with the project.
To run the project directly run play.py and enjoy.

If u want to train your own model follow the following steps:-

## 1) Creating dataset images 
run following command on terminal/cmd

python gather_images.py rock 200

press 'a' to start storing rock images. It will store 200 images.You can change the amount by changing the number in the end of command.

Do similarly for paper, scissors and none images.
none will store the blank images i.e images with no hand gesture in it.

## 2) Training

train the model by running train.py
If the model get a training accuracy over 99% or 0.99 than its a good  model.

## 3) Test
create some test images and run test.py with the location of image as command line argument.
for eg    python test.py C:/location_of_image

## 4) Run
Run the project by running play.py and enjoy.

#### Future updates may include scoring capabilities right now this project does not have scoring capabilities.
