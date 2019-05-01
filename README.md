### deepmhd

These notebooks are provided to reproduce all data-containing figures and all results from 

```Do Androids Dream of Magnetic Fields? Using Neural Networks to Interpret the Turbulent Interstellar Medium```

by J. E. G. Peek and Blakesley Burkhart, currently _in prep_, to be submitted to AAS Journals

With these notebooks, and the associated data found in Harvard Dataverse, you should be able to 

- extract normal and Fixed Fourier images from the turbulent simulations and save them as numpy files for training and test data
- train networks to classify these images
- evaluate the networks (either your own trained networks, or the ones provided by us at Harvard Dataverse)
- run the saliency map analysis
- make figures 1 and 3 (sans annotation)

### Software Requirements

The code requires a few dependencies

- Python 3
- numpy 1.14.5
- tensorflow 1.6
- keras 2.2.4
- sci-kit-image 0.13
- matplotlib 2.1.2
- tdqm
