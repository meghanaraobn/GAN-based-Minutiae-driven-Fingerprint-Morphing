# GAN-based Minutiae-driven Fingerprint Morphing

Fingerprint morphing is the process of combining two or more distinct fingerprints to create a new, morphed fingerprint that includes identity-related characteristics of all constituent fingerprints. Previously, this was done by eithervapplying a model-based minutiaeoriented approach or a data-driven approach based on a GenerativevAdversarial Network (GAN). The model-based approach provides the ability to manage the number of minutiae coming from the fingerprints, but the resulting fingerprint often appears unrealistic. On the other hand, the data-driven approach produces realistic fingerprints, but it does not guarantee that the resulting fingerprint matches the original fingerprints. In this work, we introduce an algorithm that combines minutiae-oriented and GAN-based approaches to generate morphed fingerprints that look realistic and match their original fingerprints. The algorithm is initially designed
to generate double-identity fingerprints and is further extended to generate triple-identity fingerprints. The results of our experiments indicate that the generated fingerprints appear realistic and the majority of them can be seen as double-identity fingerprints. The fingerprints resulting from morphing three fingerprints are unlikely to be triple-identity fingerprints, but rather anonymous ones matching none of the constituent original fingerprints.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## How to use?

- Coming soon

## Prerequisites

* How to setup Python environment

## Installing

* Clone the repository or download and unzip it.    
* Install the packages mentioned in `environment.yml`
   ```
    #Do this in the project folder console.
    conda env create -f env.yml
    # To Update
    conda env update -f env.yml --prune
  ```

## Usage
 *Coming soon

## Code Style Enforcements
  
* Coming soon

## Code structure
- Coming soon

## Pull Request
- You are always welcome to contribute to this repository by sending a [pull request](https://help.github.com/articles/about-pull-requests/).
- Please also add the documentation for the implementations/corrections.

## Citation
Coming soon
