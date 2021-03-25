# Near-Future-Weather-Prediction

This research proposed a model for image-based near future weather prediction which will predict the next hour weather based on two images that are captured in the past two hours in the same day (with one-hour interval). Basically, the proposed model consists of 2 parts, which it will first predict the next hour temperature of the images in the image sequence and then classify the predicted temperature into either rainy or sunny day.

As conclusion, this research has:
- Proposed an image-based near future weather prediction model which can predict the next hour weather type, in sunny or rainy, based on a series of images that is captured in the past two hours in the same day.
- Improved the accuracy of the image-based future temperature prediction model that is proposed by Chu, Ho and Borji (2018) by replacing the CNN image features extraction model with VGG-16 model and replacing the embedding layer to three fully connected layers. 
- This research also found that Random Forests is good for classifying the weather types based on temperature.
