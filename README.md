# GANplayground
GAN projects for image generators
This project currently explores different combinations of network structure for GAN image generators.

Log -
17/04/2023: Trained the generator and discriminator for 3 epoches and it's already generating some images that resembles anime faces. 
UNet is used for both generator and discriminator in the anime face trial. 
In the CIFAR100 trial, the generator uses a UNet, and the discriminator uses a autodecoder structure. This bombination needs more fine tuning.

The anime face generator uses jpeg images of anime faces, provided by a dataset downloaded from Kaggle. Data size is about 800 mb, a total of 60000+ images.


