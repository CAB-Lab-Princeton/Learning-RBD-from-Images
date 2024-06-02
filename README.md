# Learning to Predict 3D Rotational Dynamics from Images of a Rigid Body with Unknown Mass Distribution
Pytorch implementation for ["Learning to Predict 3D Rotational Dynamics from Images of a Rigid Body with Unknown Mass Distribution"](https://www.mdpi.com/2226-4310/10/11/921) published in MDPI Aerospace - Machine Learning in Aeronautics Special Issue 2023. 

In many real-world settings, image observations of freely rotating 3D rigid bodies may be available when low-dimensional measurements are not. However, the high-dimensionality of image data precludes the use of classical estimation techniques to learn the dynamics. The usefulness of standard deep learning methods is also limited, because an image of a rigid body reveals nothing about the distribution of mass inside the body, which, together with initial angular velocity, is what
determines how the body will rotate. We present a physics-based neural network model to estimate and predict 3D rotational dynamics from image sequences. We achieve this using a multi-stage prediction pipeline that maps individual images to a latent representation homeomorphic to SO(3), computes angular velocities from latent pairs, and predicts future latent states using the Hamiltonian equations of motion. We demonstrate the efficacy of our approach on new rotating rigid-body datasets of sequences of synthetic images of rotating objects, including cubes, prisms and satellites, with unknown uniform and non-uniform mass distributions.

This project is available [available on PyPI](url) and can be install via:


Accepted: 10/10/2023

## Dependencies

## Example Usage

## Example GIFs
