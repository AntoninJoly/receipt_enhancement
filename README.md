# Receipt enhancement
Modification of the observation of a receipt using computer vision and geometric operations.

They include among other:
- Adaptative thresholding
- Contouring and filtering
- Homography
- Contour analysis and sorting
- Thin plate spline

![](./assets/image_transformation.jpg)

These operation are tuned to work on specific conditions (background mainly) and will not work if used in unrelated conditions. 
I blured some parts of the receipt data since they contain information that can be used for identification.

Click [here](https://engineering.monstar-lab.com/en/post/2021/12/20/Receipt-recognition-using-computer-vision-and-deep-learning/ ) to see the blog post I wrote about it using a combination of CV and DL.