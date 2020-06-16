New Deep Learning Model for Road Safety Attribute Detection

Step 1: Download DeepLearningModel.zip file (4.7gb - file with trained models) using following link: https://drive.google.com/file/d/1QGxofiBeZ_cLqeghOye3Wl3pouLqiYP5/view?usp=sharing

Step 2: Unzip it and put all files and directories at one place 

Step 3: Click on mainProgram.exe file or run it by typing mainProgram in command prompt
Step 4: The program will run and display various outputs on the screen, wait until it finishes.
Step 5: Open excel file from output directory to see the results (1 means object detected, 0 means not detected). You can also view segmented images in output/fuse_vis directory. Original resized images are in  output/ori_resized directory. Original input files are in output/ori directory.

Important Note: If you want to run program again, you must delete all directories and files from 'output' directory except 'ori' directory. Output/ori directory should have test images which you want to test. It will only recognise attributes/objects such as roads, lanes and poles because we have supplied only 3 trained models (trained model files are too big). We have models for more than 30 roadside attributes.

Testing with own images 
Step 1: Put test images (jpg format) with a size greater than 800x800 (RGB colour) in directory output/ori
Step 2: Click on mainProgram.exe file or run it by typing mainProgram in command prompt
