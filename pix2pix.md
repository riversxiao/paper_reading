## Image-to-Image Translation with Conditional Adversarial Networks

### hand-engineer the mapping function

### hand-engineer the loss function

One reason language translation is difficult is because
the mapping between languages is rarely one-to-one

traditional loss function will tend to give a blurring picture if loss function is naively
implemented, and it takes expert knowledge to difine a loss function to get a good quality
picture.

However with GANs, we can learn a loss funciton to classify if the image is real or fake, and
train a generative model to minimize the loss.

this paper explore GANs in the Conditional setting.
Our primary contribution is to demonstrate
that on a wide variety of problems, conditional
GANs produce reasonable results.
Our second contribution
is to present a simple framework sufficient to
achieve good results, and to analyze the effects of several
important architectural choices.

### Related work

In previously Pix2Pix transformations, each output pixel is considered conditionally independent
from all others given the input imagem, this kind of output space is called as "unstructured"
There
### Method

1. objective

2. Network architectures

3. Optimization and inference

### Experiments

1. Evaluation metrics

2. Analysis of the objective function

3. Analysis of the generator architectures

4. From PixelGANs to PatchGans to ImageANs

5. Perceptual validation

### Conclusion

The results in this paper suggest that conditional adversarial
networks are a promising approach for many imageto-
image translation tasks, especially those involving highly
structured graphical outputs. These networks learn a loss
adapted to the task and data at hand, which makes them applicable
in a wide variety of settings.
