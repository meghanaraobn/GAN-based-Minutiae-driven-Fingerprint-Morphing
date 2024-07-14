# GAN-based Minutiae-driven Fingerprint Morphing

Fingerprint morphing is the process of combining two or more distinct fingerprints to create a new, morphed fingerprint that includes identity-related characteristics of all constituent fingerprints. Previously, this was done by either applying a model-based minutiae oriented approach or a data-driven approach based on a Generative Adversarial Network (GAN). The model-based approach provides the ability to manage the number of minutiae coming from the fingerprints, but the resulting fingerprint often appears unrealistic. On the other hand, the data-driven approach produces realistic fingerprints, but it does not guarantee that the resulting fingerprint matches the original fingerprints. In this work, we introduce an algorithm that combines minutiae-oriented and GAN-based approaches to generate morphed fingerprints that look realistic and match their original fingerprints. The algorithm is initially designed to generate double identity fingerprints and is further extended to generate triple-identity fingerprints. The results of our experiments indicate that the generated fingerprints appear realistic and the majority of them can be seen as double-identity fingerprints. The fingerprints resulting from morphing three fingerprints are unlikely to be triple-identity fingerprints, but rather anonymous ones matching none of the constituent original fingerprints.

This is the implementation of the paper - [GAN-based Minutiae-driven Fingerprint Morphing](https://dl.acm.org/doi/pdf/10.1145/3658664.3659632).

## Method
* 1a & 1b - Finding the Best Alignment.
* 2a & 2b - Sub-optimal Selection of Distinct Regions.
* 3a & 3b - Creation of Minutiae Map.
* 4a & 4b - Generation of Morphed Fingerprint from trained [Pix2pix model](https://gitti.cs.uni-magdeburg.de/Andrey/gensynth-pix2pix).

![image](https://github.com/user-attachments/assets/51146f8f-23ea-4540-8045-c425c729d961)


## Installing

* Clone the repository or download and unzip it.    
* Install the packages mentioned in `env.yml`
   ```
    #Do this in the project folder console.
    conda env create -f env.yml
    # To Update
    conda env update -f env.yml --prune
  ```

## Citation
```
@inproceedings{bangalore2024gan,
  title={GAN-based Minutiae-driven Fingerprint Morphing},
  author={Bangalore Narasimha Prasad, Meghana Rao and Makrushin, Andrey and Ferrara, Matteo and Kraetzer, Christian and Dittmann, Jana},
  booktitle={Proceedings of the 2024 ACM Workshop on Information Hiding and Multimedia Security},
  pages={175--186},
  year={2024}
}
```
