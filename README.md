# trypophobia-detector

This is a convolutional neural network which detects whether a given image contains trypophobia triggers(https://en.wikipedia.org/wiki/Trypophobia). 
This network was made during machine learning workshops in ICM UW from 2017-01-15 to 2017-01-20 with supervision of PhD Piotr Migdał (http://p.migdal.pl/).

The training and validation sets consisted of two classes - trypophobic and normal.
Using https://github.com/HoverHell/RedditImageGrab our team obtained trypophobic pictures from the tryphophobia subreddit and normal pictures from the img subreddit.
In each class there was the same ammount of pictures. The validation set contained 20% of the images.

This network obtained 88.44% accuracy on the validation set and used a pretrained vgg16 network. For more information about the vgg16 network see this paper:
Very Deep Convolutional Networks for Large-Scale Image Recognition K. Simonyan, A. Zisserman arXiv:1409.1556

The file training_process.ipynb contains detailed information about the training process.
The file load_model.ipynb contains a ready to use function to load this network.

The weights can be obtained at: https://drive.google.com/open?id=0B9fEN_YHQmF3cGJWNlE1Z1pJd1U
