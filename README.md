### deepmhd

These notebooks are provided to reproduce all data-containing figures and all results from 

```Do Androids Dream of Magnetic Fields? Using Neural Networks to Interpret the Turbulent Interstellar Medium```

by J. E. G. Peek and Blakesley Burkhart, accepted ApJL, https://arxiv.org/abs/1905.00918

With these notebooks, and the associated data [here](https://doi.org/10.7910/DVN/UKOPYP), you should be able to 

- extract normal and Fixed Fourier Power (FFP) images from the turbulent simulations and save them as numpy files for training and test data
- train networks to classify these images
- evaluate the networks (either your own trained networks, or the ones provided by us at [here](https://doi.org/10.7910/DVN/UKOPYP))
- run the saliency map analysis
- make figures 1 and 3 (without annotation)

### Software Requirements

These notebooks have a few dependencies:

- Python 3
- numpy 1.14.5
- tensorflow 1.6
- keras 2.2.4
- sci-kit-image 0.13
- matplotlib 2.1.2
- tqdm

### Hardware Requirements

There should not be strong hardware requirements to make figures and evaluate networks. To train the networks we used a NVIDIA Tesla P100 GPU, and we do suggest GPU acceleration of some kind for timely network training.
