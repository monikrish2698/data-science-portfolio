
# Semantic segmentation

Semantic Segmentation is a computer vision task in which the goal is to assign a semantic label to each pixel in an image. This process involves dividing an image into multiple segments or regions, where each segment corresponds to a different object or part of the image. This information can be used to understand the structure and content of an image, and is important for tasks such as image recognition, object detection, and scene understanding. The output of a semantic segmentation model is a pixel-wise classification of the input image, which can be represented as a grayscale or color-coded image where each label corresponds to a different semantic category.

<b>credits: coursera mini project on semantic segmentation</b>


Task: To label pixels on the image where humans are found<br>
Framework: PyTorch<br>
Dataset: @VikramShenoy97<br>
Model: UNET , Encoder : timm-efficientnet-b0, Weights : imagenet<br>

Loss: DiceLoss<br>
![image](https://user-images.githubusercontent.com/65104881/217586826-1877d68a-1c45-4494-8341-2675877d06a7.png)<br>

