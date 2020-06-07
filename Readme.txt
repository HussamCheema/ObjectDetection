Requirements:
	-> Python 3.6
	-> GPU/CUDA
	-> Jupyter Notebook
	-> Libraries: sporco, matlab, scipy
	-> You may have to install other libraries if they aren't already install on your system
	-> To install those libraries simply put following script on cmd:
		"pip install <lib_name> --user"
	-> Download "backup" folder from the given link and move this folder to "cfg" folder.
		-> https://drive.google.com/open?id=1jgVMZqBn5qQT84rNW-CraOECSIA_dxjY
	-> Download "yolov3.weights" file from the given link and move this file into "yolov3-coco" folder.
		-> https://drive.google.com/open?id=1XD4dJNLeyiGo_z6TYZLrUhwfzd0cfgWR

How to run:
	-> Open "Main.ipynb" file on Jupyter Notebook
	-> Run all the cells one by one after installing all the libraries
	-> To input different "Infrared Image" and "Visible Image", you need to change the "image_id" accordingly.
		-> "image_id" describes the image id in folder "./Test Images/IV_images/" 
		-> In current example, I used image 2 from "IV_images" folder
	-> Every required file is included in this project
	-> Cell containing Matlab script might take few minutes to run because it will use Matlab engine in background.
	-> Matlab script would require 2 images (Panchromatic and Multispectral) as input
		-> Both of these images are in the folder of "Test Images"
	-> All the test images resides in folder "Test Images"
	-> You will find the outputs in "Outputs" folder
	-> Last script takes the aerial image from "./Test Images/DOTA_images/" folder, as input. You can test another image from that folder.