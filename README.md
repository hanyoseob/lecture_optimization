# Author

Hello, I'm `Yoseob Han` who is postdoctoral researcher in Harvard medical school and Massachusetts general hospital.

I am running [YouTube channel](https://www.youtube.com/channel/UCpujNlw4SUpgTU5rrDXH0Jw) to address `deep learning`, `signal processing`, and `optimization`.
You can easily learn above topics through practice, and all the source codes are uploaded [HERE](https://github.com/hanyoseob).

I am also preparing `a simple parallel computing course using CUDA`.

In addition, I have a plan to make a lecture according to `an advanced medical imaging processing` related to computed tomography (CT) and magnetic resonance imaging (MRI), and will upload the lecture in a new repository.

Since all the lectures were written by myself, there may be erroneous explanations.
If you find wrong parts, please let me know.

___If you like the lectures, please `click on the star` and `follow` [GitHub](https://github.com/hanyoseob), and `subscribe` to my [YouTube](https://www.youtube.com/channel/UCpujNlw4SUpgTU5rrDXH0Jw).___

---
# Optimization by example 

Here, I will explain the basic concept of the optimization and address how to solve the real world problems like vision- and medical-imaging tasks using the optimization methods.

## Contents

### [1. Inverse problem](https://github.com/hanyoseob/lecture_optimization/blob/main/chapter01_Inverse_problem.ipynb)
We learn a concept of `the inverse problem` and explain how to solve the inverse problems depending on a system condition.

### [2. Optimiziation problem](https://github.com/hanyoseob/lecture_optimization/blob/main/chapter02_Optimization_problem.ipynb)
We learn a concept of `the optimization problem` to solve the inverse problem.

### [3. Gradient descent method](https://github.com/hanyoseob/lecture_optimization/blob/main/chapter03_Gradient_descent_method.ipynb)
We learn `a gradient descent method` and implement `the gradient descent method` to solve the inversion problem of 1D toy-example.

> ### [3-1. Gradient descent method for 2D matrix multiplication](https://github.com/hanyoseob/lecture_optimization/blob/main/chapter04_Gradient_descent_method_for_matrix_multiplication.ipynb)
> We implement `the gradient descent method` to solve the inversion problem of 2D matrix multiplication.
>
> ### [3-2. Gradient descent method for natural image processing](https://github.com/hanyoseob/lecture_optimization/blob/main/chapter05_Gradient_descent_method_for_natural_image_processing.ipynb)
> We implement `the gradient descent method` to deblur the blurred image by the known 2D Gaussain kernel.
>
> ### [3-3. Gradient descent method for medical image processing](https://github.com/hanyoseob/lecture_optimization/blob/main/chapter06_Gradient_descent_method_for_medical_image_processing.ipynb)
> We implement `the gradient descent method` to reconstruct computed tomography (CT) image using [Radon transform](https://en.wikipedia.org/wiki/Radon_transform).

### [4. Newton's method](https://github.com/hanyoseob/lecture_optimization/blob/main/chapter07_Newton's_method.ipynb)
We learn `a newton's method` and  implement ` the newton's method` which is one of the optimization methods.

> ### [4-1. Newton's method for natural image processing](https://github.com/hanyoseob/lecture_optimization/blob/main/chapter08_Newton's_method_for_natural_image_processing.ipynb)
> We implement `the newton's method` to deblur the blurred image by the known 2D Gaussain kernel.
>
> ### [4-2. Newton's method for medical image processing](https://github.com/hanyoseob/lecture_optimization/blob/main/chapter09_Newton's_method_for_medical_image_processing.ipynb)
> We implement `the newton's method` to reconstruct computed tomography (CT) image using [Radon transform](https://en.wikipedia.org/wiki/Radon_transform).

### [5. Conjugate gradient method](https://github.com/hanyoseob/lecture_optimization/blob/main/chapter10_Conjugate_gradient_method.ipynb)
We learn `a conjugate graident method` and implement ` the conjugate graident method` to solve linear equations.

> ### [5-1. Conjugate gradient method for natural image processing](https://github.com/hanyoseob/lecture_optimization/blob/main/chapter11_Conjugate_gradient_method_for_natural_image_processing.ipynb)
> We implement `the conjugate gradient method` to deblur the blurred image by the known 2D Gaussain kernel.
>
> ### [5-2. Conjugate gradient method for medical image processing](https://github.com/hanyoseob/lecture_optimization/blob/main/chapter12_Conjugate_gradient_method_for_medical_image_processing.ipynb)
> We implement `the conjugate gradient method` to reconstruct computed tomography (CT) image using [Radon transform](https://en.wikipedia.org/wiki/Radon_transform).

### 6. Performance evaluation
We summarize the optimization methods such as `a gradient descent method`, `a newton's method`, and `a conjugate gradient method`.

> ### [6-1. Performance evaluation for natural image processing](https://github.com/hanyoseob/lecture_optimization/blob/main/chapter13_Performance_evaluation_for_natural_image_processing.ipynb)
> We summarize `the deblurring performace` from optimization methods.
>
> ### [6-2. Performance evaluation for medical image processing](https://github.com/hanyoseob/lecture_optimization/blob/main/chapter14_Performance_evaluation_for_medical_image_processing.ipynb)
> We summarize `the CT reconstruction performace` from optimization methods.
