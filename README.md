# MEL-database

This is the code used to generate a synthetic dataset of deformable objects for our paper **Active garment recognition and target grasping point detection using deep learning**. For this, you will need a pointcloud file of the clothing classes you are interested in. 
The script *Save_Images_and_point_info_from_jeans.mel* will help you to generate both depth images of the clothing and save the relevant information of each sample in a csv file. The scripts *Prepare_environment_to_save_jeans_info.mel* and *Prepare_environment_to_save_jeans_and_take_depth_images.mel* should be helpful to setup the environment to capture depth images and physical properties of your clothing.

The scripts *Save_depth_images_from_two_garments_one_over_the_other.mel*  and *Save_depth_images_from_two_garments_in_the_same_grasping_point.mel* involve more challenging views with more than two garments grasped.

The paper is available at https://www.sciencedirect.com/science/article/abs/pii/S0031320317303941. If you have any comments or suggestions, please email me at _enriccorona93@gmail.com_.
