# Welcome

### About Me
I am currenlty a PhD student at the University of Bath and part of the [CAMERA](https://www.camera.ac.uk/) research group. My reserch  involves computer vision for animal body analysis with a focus upon canines. My research interests include: 

1. Pose Estimation 
2. Part Segmentation 
3. Synthetic Data
4. Domain Adaptation
5. Generative Adversarial Networks (GANs)



My initial work at the University of Bath concerned the area of human pose estiamtion and multi task learning. Early in my research my interest began to shift towatds the animal domain ans how we could apply techniques and models that had been used on human subjects to animals. Such a research area has provided my with a plethora of interesting projects as there is very little work in this area when comparing to humans, 

### X-Dog

One of my first projects as part of this research considered a simplistic canine skelton model made up of 43 joints which we called X-Dog (eXpressive Dog). Inspired by the work of [Kanazawa et.al.](https://akanazawa.github.io/hmr/) we used this model to generate syntehtic data using a set of 2D keypoints ofr images we had labelled ourselves. Please see [Canine Skeleton Reconstruction](/CSR.md) for more details. 


### DynaDog+T

While the inital results of this work were encouraging, by the time these results were generated we had imrpoved this skeleton model toa  fully fledged articulated parametric model. This iteration of the model was called DynaDog+T (Dynamic Dog plus Texture). Please see [DynaDog](/DynaDog.md) for further details on this model and examples of the data produced by it. 



### RGBT-Dog

DynaDog+T while capable of generating data was, at the time, only capable of generating synthetic data. This provided some limitations in part due to the domain gap ([see here for more details](https://machinelearning.apple.com/research/bridging-the-domain-gap-for-neural-models)). To correct this we introcuded a propcedure for fitting our parametric model to images of real dogs using a subset of labelled keypoints. See [RGBT-Dog](/RGBT.md) for further details. 


### Generating better synthetic data

The synthetic data produced in previous projects can be improved upon. As can be seen in the relevant project pages, the meshes in our synthetic images lacked smooth surfaces. In addition these meshes were often in unreealsitic positions in the images with inconsistent lighting when compared to the background. 
