# Deep-Learning-Based-Analysis-of-MRI-Images-for-Brain-Tumor-Segmentation
Brain Tumor Detection and the Role of Artificial Intelligence

Brain tumor detection plays a critical role in neuroimaging and medical image analysis, focusing on identifying abnormal tissue growth in MRI scans. 
The integration of artificial intelligence (AI), particularly deep learning, has revolutionized brain tumor detection. Modern hardware, such as GPUs, combined with advanced algorithms like Convolutional Neural Networks (CNNs), now facilitate the analysis of large datasets. These innovations have reduced processing times, enhanced scalability, and transformed how tumors are identified and segmented.

Main aim:

This Prject explores the segmentation of 3D brain MRI images using various CNN architectures: SegNet, V-Net, and U-Net. Additionally, a novel U-Net architecture was implemented, incorporating the following key enhancements:

    Symmetrical encoder-decoder design.
    Leaky ReLU activation for improved gradient flow.
    Dropout and batch normalization layers for effective regularization.
    GELU activation to preserve spatial information.

The study employed datasets from the Medical Segmentation Decathlon for training and testing. The models were evaluated on criteria such as complexity, training time, and segmentation accuracy

Results

Among the architectures tested, U-Net emerged as the most effective model with a Dice Similarity Coefficient (DSC) of 88.5%, outperforming:

    V-Net with a DSC of 86.4%, and
    SegNet with a DSC of 84.8%.

These findings underscore U-Net's superiority in terms of segmentation accuracy and its potential for clinical applications in brain tumor detection

Dataset - https://drive.google.com/drive/folders/1HqEgzS8BV2c7xYNrZdEAnrHk7osJJ--2
