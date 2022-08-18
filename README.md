# Image-Captioning-with-InceptionV3

The origional project is from https://github.com/aminrabinia/Image-Captioning-with-InceptionV3-

I fixed the code to fit TF 2.4 and Python 3.8 

The most import change is 
use yield ([in_img,in_seq],out_word)
instead of 
yield [[in_img, in_seq], out_word]


It worked!!
But i think the result is not good enough.
