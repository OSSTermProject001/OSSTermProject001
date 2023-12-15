## -Project Overview
The goal of this project is to develop software that accurately recognizes human joints in a given photograph using OpenPose. 
The code is written using the model provided at the GIT address at the top of the code, along with the OpenCV and NumPy libraries. 
When a specific image file is inputted, it visualizes approximately 17 to 19 joints.

## -Examples
![ossw1](https://github.com/OSSTermProject001/OSSTermProject001/assets/144337024/d27bbe91-e4e6-4382-91a3-bb7759d780b7)
![ossw2](https://github.com/OSSTermProject001/OSSTermProject001/assets/144337024/36fa4dac-94d8-42e6-b79b-23e832691aa4)

## -Packages used
- cv2
- numpy
- cv2_imshow

## -Execution method
1. Specify the image path in the 63rd line of the code within cv.imread().
2. After loading the basic model from git, analyze the image using the OpenCV and NumPy modules.
3. Visualize and represent around 19 joints on the image.

## -Reference material
- !git clone https://github.com/misbah4064/human-pose-estimation-opencv.git
- %cd human-pose-estimation-opencv/
