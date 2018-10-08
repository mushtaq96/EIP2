Name - **SM MUSHTAQ BOKHARI**

Batch number - **BATCH 5**

**1. Convolution**

According to the oxford dictionary, Convolution is a coil or a twist or a thing that is complex and difficult to follow.
But according to scientists, Convolution is a process of combining 2 functions or 2 signals to generate a third function/signal that is derived from the given inputs.
Convolution is mostly used in the subject of Digital Signal Processing and in the analysis of the Cerebrum ie Human Brain.



**2. Filters/Kernels**

Filters/kernels can enhance an image by facilitating the processes of noise reduction and resizing.They do this by modifying the pixels in an image based on some function of a local
neighborhood of each pixel, for example in noise reduction - the replacement of each pixel by the average of its neighbors happens.
Filters or kernels also help in the extraction of texture information,edge information in a given image. Pattern detections can also be done with the help of filters/kernels.


**3. EPOCHS**

The Cambridge dictionary defines an "Epoch" as - a long period of time where there are new developments and great change.
Its basically a unit of time according to wikipedia.
In machine learning though, the process of passing an entire dataset through a neural network back and forth is called an epoch ie One epoch.
Very less number of epochs lead to an under-fitting neural network model.As the number of epochs increases, more number of times the weights are changed, resulting in a neural network which is at its optimum level.  



**4. 1 by 1 convolutions**

The classic convolution setting acts like a small classifier for a patch of the image.
When a 1 * 1 convolution is added, we get a mini neural network running over the patch instead of a linear classifier. Separating your convolutions with 1 * 1 convolutions is an inexpensive way to make your models deeper and have more parameters without completely changing their structure.
They are basically just matrix multiplications and have lesser number of parameters
1 * 1 convolution simply maps an input pixel with all it's channels to an output pixel, not looking at anything around itself. It is often used to reduce the number of depth channels.

**5. 3* 3 convolution**

![sample of 3 by 3 convolution](https://ujwlkarn.files.wordpress.com/2016/07/convolution_schematic.gif?w=268&h=196)

If a 3 by 3 kernel convoles over a 9 by 9 image input then we get the output as an image with 7 by 7 resolution.
A normal 3 * 3 convolution layer has 9 parameters and this number increases by a power of 2 every time we increase our kernel size.The resultant is too many parameters which is the problem with conventional traditional convolution layers.
The same 3 by 3 convolution can be computed as one 1 by 3 convolution followed by a 3 by 1 convolution, we can get the same effect as a 3 by 3 convolution. But we have now reduced the number of parameters to 6.

**6. Feature maps**


3 * 3 or 1 * 1 convolution uses respective matrix which are called as filters/kernels/feature detectors.
The resultant matrix formed by the convoluting process over the input image and computing the dot product is called as a *feature map*.
It is also called as Convolved feature or Activation map.
It is very clear that different feature maps are generated from different values of the kernel matrix even though it is applied on the same input image.


**7. Feature engineering**


A feature is usually a specific representation on top of some raw data.
Feature engineering evaluates if a model is good or unfit for use.
There is a critical need to engineer features which are relevant to the scenario, problem and domain before building a model in machine learning.
If feature engineering is successful it increases predictive power of algorithms by creating fesatures from raw data which helps in the process.


**8. Activation function**

The primary function of an activation function in CNN or any other ANN(artificial neural network) is to establish non-linear properties into a network.
It ensures that the representation in the input space is mapped to a different space in the output by calculating the ‘weighted sum’ and adds direction and decides whether to ‘fire’ a particular neuron or not. 
An activation function projects the infinite value range(+ve inf to -ve inf) to a probabilistic value range ie 0 to 1 or -1 to 1 sometimes.  
There are various types of activation functions,
1.Sigmoid
2.tanh
3.Relu
4.LeakyRelu etc


**9. Receptive field**

Receptive field is the region in the input space that affects a particular feature unit of convolution neural network.
Along with stride and padding, receptive field is also considered as one of the hyper-parameters  on a cnn filters.
Consider an example of first hidden layer, here each neuron will be connected to only a region of the input layer, that region in the input image is called the local receptive field for the hidden neuron.
Receptive field is also called as kernel/filter.





