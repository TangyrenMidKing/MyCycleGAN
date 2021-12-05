# MyCycleGAN

# Group Member 
Weiyuan Wu, 
Shibo Ding, 
Shenyang Liu, 
Dunquan Zheng

# Instruction
$python3 oldmain.py

# Abstract
It is very impressive to translate image styles. So many different approaches are utilized these days to get style translation with better qualities. Among all these methods, CycleGAN is one the most famous methods (with more than 10,000 citings) to use GAN along with a cycle-consistency loss to finish the style translation task for unpaired images.  However, this 2017 paper has some issues with its loss functions and in our project, we would like to train the original CycleGAN first and then modify loss functions to check if these functions could help improve the performance of CycleGAN. After searching a large amount of paper with loss functions for GAN improvement, we select feature matching, which is at first commonly used in paired images translation. The result shows that when using CycleGAN with feature matching,  more details can be kept from the original input image to the generated image which improves the image quality of the translated image. 
