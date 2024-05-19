## **Bonus Question 1** <br>
### **Vision-Based Transformers** <br>
Transformers are models that implement a mechanism of self-attention, individually weighting the importance of each part of the input data.Vision-Based Transformers (ViTs) represent a significant advancement in the field of computer vision, diverging from traditional Convolutional Neural Networks (CNNs) in several key aspects. <br>
<br>
The architecture of Vision based Transformers[ViTs] are: 
* Split an image into patches
* Flatten the patches
* Produce lower-dimensional linear embeddings from the flattened patches
* Add positional embeddings
* Feed the sequence as an input to a standard transformer encoder
* Pretrain the model with image labels (fully supervised on a huge dataset)
* Finetune on the downstream dataset for image classification
![](https://github.com/Divyanshu0311/23B0306_AIC/blob/main/gif1.gif)

<br>
Image patches are the sequence tokens (like words). Similar to what I studied in Technical Question 3.<br>
There are multiple blocks in the ViT encoder, and each block consists of three major processing elements:<br>
1) Layer Norm<br>
2) Multi-head Attention Network (MSP)<br>
3) Multi-Layer Perceptrons (MLP)<br>
