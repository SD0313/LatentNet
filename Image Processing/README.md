# Fitzpatrick Scale ID & Hair Density Detection

A key portion of this project was evaluating the performance of the 
models in multiple categories based on a specific feature. Categories
used included the following:
* Type I Fitzpatrick Scale
* Type II Fitzpatrick Scale
* Type III Fitzpatrick Scale
* High Hair Density

The ISIC dataset does not provide Fitzpatrick or Hair Density labels
for all images, so I designed two algorithms, one to approximate the 
shade of skin color (```Skin_Color.ipynb```), and another to quantify the amount of hair 
(```Detect Hair.ipynb```). 