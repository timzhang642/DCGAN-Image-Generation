# DCGAN-Image Generation
What would it be like to design a chair 20 years from now? Do we still have to bear with the complexity of the design software and spend the entire week clicking here and there? Possibly. Or, maybe we can let the computer handle the heavy lifting to generate designs that are good and we pick the ones we like!  

Researchers are working on bringing this Sci-Fi scene to reality and they named it Generative Design. In this project I took a peek into this lovely technology by having implemented DCGAN, which is a novel framework of ConvNets to generate visually realistic images (both B&W and color).

Original DCGAN paper: https://arxiv.org/pdf/1511.06434v2.pdf

More about Generative Design: https://redshift.autodesk.com/what-is-generative-design-2/

### Datasources
MNIST: http://yann.lecun.com/exdb/mnist/
<br>
CelebA: http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html

### MNIST
Original MNIST samples:
<br>
![](https://github.com/timzhang642/DCGAN-Image-Generation/blob/master/mnist_original.png)

Generated MNIST samles:
<br>
![](https://github.com/timzhang642/DCGAN-Image-Generation/blob/master/mnist.gif)

Linear Interpolation from 2 to 8
<br>
![](https://github.com/timzhang642/DCGAN-Image-Generation/blob/master/2%20to%208.png)
<br>

### CelebA
Original CelebA samples:
<br>
![](https://github.com/timzhang642/DCGAN-Image-Generation/blob/master/faces_original.png)

Generated CelebA samples:
<br>
![](https://github.com/timzhang642/DCGAN-Image-Generation/blob/master/faces.gif)

Spherical Interpolation for faces
<br>
![](https://github.com/timzhang642/DCGAN-Image-Generation/blob/master/CelebA%20interpolation.png)
![](https://github.com/timzhang642/DCGAN-Image-Generation/blob/master/right%20to%20left.gif)
![](https://github.com/timzhang642/DCGAN-Image-Generation/blob/master/woman%20to%20man.gif)
