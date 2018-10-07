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


**10. Creating project and publishing first project on Github**

Follow the steps:-

1.Create an account on github, then go to terminal and type
```
git config --global user.name "YOUR USERNAME"
git config --global user.password "YOUR PASSWORD"
```

2.Go to your project's folder/directory on the CLI(command line interface) and type
```
git init
```
This initializes the local folder as a git repository, so that the folder is version controlled.

3.Consider the file "my_project.python" is my project file type
```
git add FILENAME
git add my_project.python
```
In case you have multiple files, you can also type 
```
git add . 
```

4.Its time to save all the changes for a final time before publishing your file on github this is called commiting.Type
```
git commit -m "my message"
```
you can type the details of the project here in a sentence to give the reader an idea as to what the project is about.

5.And finally
```
git push origin master
```
This code pushes the changes in your project file preject in the local repo to the remote repo ie github.





**11. Mathjax examples**

- Quadratic Formula to solve algebraic equations,
$$
x = {-b \pm \sqrt{b^2-4ac} \over 2a}
$$

- Einstein's mass energy relation,
$$
E=MC^2
$$

- Dot matrix multiplication,
$$
\begin{bmatrix}
	x1 & x2 & x3 \\
	\end{bmatrix}\cdot
\begin{bmatrix}
y1 \\
y2 \\
y3 \\
\end{bmatrix}=
\begin{bmatrix}
x1y1 + x2y2+x3y3
\end{bmatrix}
$$


- Few Trignometric concepts,
$$
\tan{(x)}=sin(x)/cos(x) \\
\sin{(-x)}=-sin(x) \\
\cos{(-x)}=cos(x) \\
$$

$$
\lim\limits_{x \to 1} \frac{x^2-1}{x-1}
$$

$$
a^2-b^2 = (a+b)(a-b) \
$$

$\sum_{i=0}^n i^2 = \frac{(n^2+n)(2n+1)}{6}$

$f(n) =
\begin{cases}
n/2,  & \text{if $n$ is even} \\
3n+1, & \text{if $n$ is odd}
\end{cases}$

