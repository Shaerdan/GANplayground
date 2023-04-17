# GANplayground
GAN projects for image generators
This project currently explores different combinations of network structure for GAN image generators.

Log -
17/04/2023: Trained the generator and discriminator for 3 epoches and it's already generating some images that resembles anime faces. 
UNet is used for both generator and discriminator in the anime face trial. 
In the CIFAR100 trial, the generator uses a UNet, and the discriminator uses a autodecoder structure. This bombination needs more fine tuning.

The anime face generator uses jpeg images of anime faces, provided by a dataset downloaded from Kaggle. Data size is about 800 mb, a total of 60000+ images.

The network structure and batch size is heavily restricted by my local computer's gpu memory size, but the hyperparameters are tuned good enough to generate reasonable images for 3 epochs, waiting for results after more epoches.

plans forward: 
1. explore more efficient network structures, compare GAN UNet with other combination. 
2. explore theoretical explanation to explain the difference in sensitivity of different combination of networks to hyperparameters. 
3. explore more complex dataset




