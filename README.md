# CVPR-2011-what-you-saw-is-not-what-you-get
What you saw is not what you get : domain adaptation using asymmetric kernel transforms 

Authors: Brian Kulis, Kate Saenko, Trevor Darrell

Summary：  
This paper proposes a supervised domain adaptation model. This method Learns an asymmetric non-linear transformation for domain adaptation. It does not require the two domains utilize same features or coodebooks. What's more, a general formulation is proposed for applying the transformation learning problem in kernel space, resulting in non-linear transformations. The corresponding algorithm is based on squared Frobenius regularization and similarity constraints.

Advantages:  
1. It could handle the case when the source and target domain have different dimansional features.  
2. It could be applied in kernel space to obtain a non-linear transformation with general formulation.

Disadvantages:   
1. Using shallow features.  
2. Supervised method.
