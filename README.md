# WS-FaceMask

Face Mask Detection project

## Use Case

Detect poeple wearing face mask when entering into a facility. This is to protect humans from various virus, checmicals and other airborne particles.

## Steps

Download images from source or collect images from a facility by taking pictures or run a video camera and then pick pictures.

for this project i am using images form google images since it is available for public.

Intent of the project is use this and built your own with your own images

My goal is to show you a simple and easy way to get this moving using Azure cognitive custom vision

- Create a Cognitive resource in the Azure Portal
- log into customvision.ai
- Create a new project 
- Select object detection with Compact S2 (newer version at the time of this article)
- Upload the images
- Create a tag called FaceMask
- Go over each image and draw bounding box and assign tags
- Train the model - select quick training
- Analyze model output for accuracy
- Click Quick Test 

## Upload images

Sample images are available: https://github.com/balakreshnan/WS-FaceMask/tree/master/samplesimages

![alt text](https://github.com/balakreshnan/WS-FaceMask/blob/master/images/Capture.JPG "list of images")

## Drawing bounding box samples

![alt text](https://github.com/balakreshnan/WS-FaceMask/blob/master/images/fm1.jpg "Face Mask")

![alt text](https://github.com/balakreshnan/WS-FaceMask/blob/master/images/fm2.jpg "Face Mask")

## Training output

![alt text](https://github.com/balakreshnan/WS-FaceMask/blob/master/images/output1.jpg "Training Accuracy")

## Validate and Test Models:

I downloaded new images that model hasn't seen

![alt text](https://github.com/balakreshnan/WS-FaceMask/blob/master/images/validation.jpg "Test")

![alt text](https://github.com/balakreshnan/WS-FaceMask/blob/master/images/validation1.jpg "Vaidation")

## Export models and consume in other AI@Edge Devices.