# Canny-edge-detection-workshop


## Program:
``` Python
### Developed By:Loghul M
### Register No:212220230029
import cv2
import numpy as np
import matplotlib.pyplot as plt
# Load the image, Convert to grayscale and remove noise
image1=cv2.imread ('loghul.jpg') 
gray = cv2.cvtColor(image1,cv2.COLOR_BGR2GRAY)
plt.title('GRAY IMAGE')
plt.imshow(gray,cmap = 'gray')
#canny edge detection
canny_edges = cv2.Canny(gray, 120, 150)
plt.imshow(canny_edges,cmap='gray')
plt.title('canny_edges')
plt.axis("off")
plt.show()
```

## Output:
![s7](https://user-images.githubusercontent.com/78194419/175784510-fda51d48-3873-463b-a9ce-c0fd695a41e0.jpg)
![s8](https://user-images.githubusercontent.com/78194419/175784513-78589379-7309-4e39-9aac-a3e1d42341d8.jpg)
