# NSFW_DETECTION

# ABOUT:

To check if the input video contains Nudity or any other NSFW content and label them.


# DEPENDENCIES:

Tensorflow,Python,Numpy,Opencv


# Model:

Small Alex net.


# Usage:

1.Unzip model8

2.Open constants.py

3.Change the MODEL_SAVE_PATH to /path/to/model8/NSFWmodel-8

4.Change the VIDEO_SAVE_PATH to /path/to/your/video/folder

5.Open terminal

6.RUN: python NSFW_Predictor.py 


# OUTPUT:

1.The model checks every 50 frames for NSFW content.

2.Shows the processed frame with its label. # LABELS = [NOT NUDE, NUDE, UNKNOWN]

3.Prints video summary showing VIDEO_NUMBER,NAME,NUMBER_OF_PROCESSED_FRAMES,NSFW_SCORE

4.The NSFW Score calculated using (NSFW_Count/Total_frames). # 1.0 MEANS 100% Nudity, 0.0 MEANS 0% Nudity


# References:

http://blog.clarifai.com/what-convolutional-neural-networks-see-at-when-they-see-nudity/

https://blog.algorithmia.com/improving-nudity-detection-nsfw-image-recognition/


### Support:

If you want the good work to continue please support us on

* [PAYPAL](https://www.paypal.me/ishandutta2007)
* [BITCOIN ADDRESS: 3LZazKXG18Hxa3LLNAeKYZNtLzCxpv1LyD](https://www.coinbase.com/join/5a8e4a045b02c403bc3a9c0c)
