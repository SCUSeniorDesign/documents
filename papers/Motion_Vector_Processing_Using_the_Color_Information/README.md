## Motion vector processing using the color information

#### Summary: 

* This paper demonstrates how using the chrominance and luminance components of an image
increases performance in estimating the next frame in a video sequence

* The authors argue that by considering the chrominance component in addition to the traditional
luminance component, more accurate frame estimation can be achieved. Their findings
specifically highlight that chrominance is useful when the intensity values are the same in
luminance but the colors are different.

* The authors present clear evidence as demonstrated in Figure 5 that using chrominance in
addition to luminance creates better frame estimation. 
  * Specficially the white lines in figure 5 get messed up when not taking chrominance into consideration.


[Source](http://ieeexplore.ieee.org.libproxy.scu.edu/stamp/stamp.jsp?tp=&arnumber=5413657&isnumber=5413332)