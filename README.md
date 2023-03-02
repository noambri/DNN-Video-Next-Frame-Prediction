# DNN-Video-Next-Frame-Prediction

In this project we wish to give the network a sequence of frames and expect the model to predict the next frame based on the given sequence of frames. We do that using a combination of two common networks : AutoEncoders and Latent Predictor. The concept is encoding each frame to it's latent representation, then predicting the next latent using the latent predictor and finally, decoding the predicted latent into a predicted frame.

The project is presented in the attached Google Colab notebook.
