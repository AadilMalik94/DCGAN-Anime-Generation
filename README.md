# DCGAN-Anime-Generation
Generate Anime Style Face Using DCGAN and Explore Its Latent Feature Representation

## Full Dataset can be found at this link below:
https://www.kaggle.com/aadilmalik94/animecharacterfaces

The Purpose of this project is to be able to use DCGANs for anime character generation. This project will take a dataset of anime faces that are cropped and attempt to create similar to what the dataset holds. I trained this for 50 epochs on this platform for demonstration purposes. Train more for better results.

## What are GAN's?


It is one of the Deep Learning technique used to generate some new data from scratch. It runs in unsupervised way meaning that it can run without labelled by human. It will make the data based on the pattern that it learns.
There are some characteristics aspects on GAN who is a generative model, which is:
-> Learns joint probability P(x,y) where x is the input and y the output. It will do inference based on P(x|y) , given output y, it will infer the x. You can say that y is the the real data in GAN.
-> When the model is given the training real data y, it will learn the characteristic of the real data. It will learn by identifying the real data latent feature representation variable. To make it simpler, it learns the base constructor feature of the images in the real data. For example, the model can learn that faces constructed by the color of the eyes and hair. These two will be one of the base which will be used on generating the faces. By tweaking its variable, it can also alter the generated faces. For example, by raising the variable of the eyes, the eyes will be blacker. Lowering it will make the opposite otherwise.
-> It can build a probability distribution such as normal distribution which can be used on avoiding the outlier. Since outlier usually very rare in the distribution, it will be very rare to generate it. So GAN functions well on real data that has outlier.

This Project was originally done in 2019. I intend to build on and improve the structure of the model
