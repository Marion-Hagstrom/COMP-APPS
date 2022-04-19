# COMP-APPS
fprintf("Team Name")

Background and Motivation: Lung cancer is the leading cause of cancer death for men and women in the United States. Lung cancer can show up on a chest X-ray as a small mass. Many patients do not know they may have cancer until they are X-rayed. However, lung cancer is easy to misidentify and can be overlooked if the patient does not know they have lung cancer. Hence, we created this code to help screen X-ray images for masses in the lungs. This program uses deep learning and has an expected accuracy rate of 91%. The reported label from a program is meant to be supplemental, to help doctors screen for lung masses. If the doctor and the program disagree, more attention may be brought to a scan. However, this program is NOT meant to replace a doctor’s diagnosis. 

How to use: 
Gather the images that you want to use for this program (our orignal images are in Final.zip). If the images are greyscale (ex. chest x-rays), process them through the image_fix.mlx code before running them through the main code. This will convert your original images into rgb and save them into a new folder. Edit the code as needed (file names, number of images in loop, file location, etc.) If using this code, create a folder called FinalEdit in your directory first. The images will populate into that folder. Then sort into mass and no mass subfolders.

After saving your rbg image, navigate to “BME3053C_Final (1).mlx” and follow the prompts at the end of the code for inserting your image. Remove the comments (%) before running. (Our processed rgb images that we loaded into this code is the folded called FinalEdit)

Credits: This code utilizes the neural network AlexNet. We trained the network on images from the NIH Chest X-ray dataset. Then code was ran on MATLAB 2022a. The members of this project that contributed are Marion Hagstrom, Karen Villancio-Wolter, Sarah Scott, and Brendan McCue.
