# Dataset 
The American Sign Language letter database of hand gestures represent a multi-class problem with 24 classes of letters (excluding J and Z which require motion).

The dataset format is patterned to match closely with the classic MNIST. Each training and test case represents a label (0-25) as a one-to-one map for each alphabetic letter A-Z (and no cases for 9=J or 25=Z because of gesture motions). The training data (27,455 cases) and test data (7172 cases) are approximately half the size of the standard MNIST but otherwise similar with a header row of label, pixel1,pixel2….pixel784 which represent a single 28x28 pixel image with grayscale values between 0-255. The original hand gesture image data represented multiple users repeating the gesture against different backgrounds. The Sign Language MNIST data came from greatly extending the small number (1704) of the color images included as not cropped around the hand region of interest. To create new data, an image pipeline was used based on ImageMagick and included cropping to hands-only, gray-scaling, resizing, and then creating at least 50+ variations to enlarge the quantity. The modification and expansion strategy was filters ('Mitchell', 'Robidoux', 'Catrom', 'Spline', 'Hermite'), along with 5% random pixelation, +/- 15% brightness/contrast, and finally 3 degrees rotation. Because of the tiny size of the images, these modifications effectively alter the resolution and class separation in interesting, controllable ways.

# Hand Gestures 
<img src="./readme.img/amer_sign2.png" width=500/>

# Results 
<img src="./readme.img/B.jpg" width=400/>       <img src="./readme.img/C.jpg" width=400/>
<img src="./readme.img/D.jpg" width=400/>       <img src="./readme.img/F.jpg" width=400/>
<img src="./readme.img/G.jpg" width=400/>       <img src="./readme.img/H.jpg" width=400/>
<img src="./readme.img/L.jpg" width=400/>       <img src="./readme.img/O.jpg" width=400/>
<img src="./readme.img/Q.jpg" width=400/>       <img src="./readme.img/T.jpg" width=400/>
<img src="./readme.img/U.jpg" width=400/>       <img src="./readme.img/V.jpg" width=400/>
<img src="./readme.img/W.jpg" width=400/>       <img src="./readme.img/X.jpg" width=400/>
<img src="./readme.img/Y.jpg" width=400/>       




