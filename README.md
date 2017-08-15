# Shadow
In this project, we try to use different algorithm to remove shadow from an image with Java+ OpenCv

We considere to have a black & white color image as an input with shadow. We use different algorithm to remove it as Sauvalo, Niblack 
and Otsu.
To have a better improvement, before applying any of those algorithm, we try to have a pre-treatment by using different filter. 
For a particular image, a filter like Median is better than GaussianBlur and it's the opposite for an other image. We use fastNlMeansDenoising 
in pre-treatment. It improves the image so when we apply an algotithm, the result are more efficient.


