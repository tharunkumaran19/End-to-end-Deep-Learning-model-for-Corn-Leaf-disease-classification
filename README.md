# End-to-end-Deep-Learning-model-for-Corn-Leaf-disease-classification
  This project is an partial implementation of the base paper "End-to-end deep learning model for corn leaf disease classification" from IEEE Access.

# Purpose of the project:
Global food security is seriously threatened by plant diseases. However, it is still difficult and time-consuming to quickly identify plant diseases. Experts are 
needed to correctly determine the type of illness and whether the plant is healthy or not. Recent times have seen the development of deep learning algorithms. It helps to recognize and classify ill plants from digital photos in order to automate the diagnosis of plant diseases and make diseased plant identification easier for amateurs. This study develops an end-to-end deep learning model to distinguish between healthy and unhealthy maize plant leaves while accounting for a variety of characteristics. To extract deep characteristics from the photos of corn plants, the suggested model uses two pre-trained convolutional neural networks , EffcientNetB0 and  DenseNet121.In order to create a more complex feature set from which the model may better understand the dataset, the deep features derived from each CNN are then combined using the concatenation technique. The outcome of this study is compared to existing pre-trained CNN models, which have more parameters and demand more processing resources than the suggested model.

The significant contributions made by our work are summarized as follows:
● Apply feature fusion to features from two different CNNs in an end-to-end learning
model.
● A categorization that is more precise and has more manageable criteria.
● Extensive testing and comparison of the proposed classification model with current
models and other models developed by other authors using the same dataset.

# MERITS OF THE FEATURE FUSION MODEL :
⮚ Potentially producing a high-performing deep neural network with effective memory and computational resource utilisation is the feature fusion of EfficientNet and DenseNet. Two well-liked deep learning architectures with complementary strengths are EfficientNet and DenseNet. While DenseNet is renowned for its densely linked layers that allow for feature reuse and lessen the vanishing gradient problem, EfficientNet is renowned for its effective scaling and parameter optimisation.
⮚ These two architectures' combined features can take advantage of one other's advantages to produce a network that is more efficient. Combining the efficient scaling of EfficientNet with the connection patterns of DenseNet is one feasible strategy, which might allow the network to take use of the power of feature reuse through densely linked layers while simultaneously optimising memory utilisation through the scaling principles of EfficientNet.
⮚ Additionally, combining the feature concatenation strategy of DenseNet with the skip connection and convolutional layer optimisation strategies of EfficientNet may result in a more effective and reliable network. This may lead to a network that delivers excellent performance while paying less for processing and memory.
⮚ Overall, the combination of EfficientNet and DenseNet's features has the potential to provide a strong deep learning architecture that gets around some of the drawbacks of current designs.

# DEMERITS OF THE FEATURE FUSION MODEL :
⮚ One disadvantage of combining DenseNet121 with EfficientNet is the increased model complexity. Additionally, it might lead to an increase in computing requirements. Combining features from various architectures may lead to more intricate models with longer training cycles and a higher risk of overfitting.
⮚ It is crucial to watch out that the fusion process does not unnecessarily favor the majority classes when combining DenseNet and EfficientNet data because doing so
could lead to inaccurate or misleading predictions for the minority classes.
⮚ It's possible that the large image data used to create and train DenseNet and EfficientNet, such as ImageNets, won't accurately capture the traits of corn leaves in disease. Different network topologies, layer placement, and feature representations are used by DenseNet and EfficientNet. Additional modifications or adaptations may be required to ensure compatibility as components of various networks are integrated and combined


# DETAILS OF THE BASE PAPER :
Base Paper URL : https://ieeexplore.ieee.org/document/9734016
Title of the Base Paper : End-to-End Deep Learning Model for Corn Leaf Disease Classification
Title of the Base Paper : End-to-End Deep Learning Model for Corn Leaf Disease Classification
Authors : Hassan Amin, Ashraf Darwish, Aboul Ella Hassanien, Mona Soliman
Journal published : IEEE Access
Year of Publication : 2022
Volume : 10
Indexed in : Scopus and Science Citation Index Expanded
Publisher : IEEE


