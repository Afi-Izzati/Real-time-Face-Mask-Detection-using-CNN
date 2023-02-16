# Real-time-Face-Mask-Detection-using-CNN
real-time face mask detection using 3 different algorithms (MobileNetV2, VGG16, ResNet50V2)

Download file and extract the zip file and then copy e.g, MobileNetV2 file to Windows(C:).

1. Open terminal and type the following command:

   cd C:\MobileNetV2  

2. Create a Python virtual environment named 'test' and activate it:

   virtualenv test

3. Now, run the following command in your Terminal/Command Prompt to install the libraries required:

   pip3 install -r requirements.txt

4. To train the dataset type the following command:

   python train_mask_detector.py 

5. To detect face masks on static images type the following command:

   python detect_mask_image.py --image images/pic2.jpg 

6. To detect face masks in real-time video streams type the following command:

   python detect_mask_video.py

Do it the same for ResNet50V2 and VGG16 files with different directory, cd C:\ResNet50V2 and cd C:\VGG16.

