# pip install numpy
import numpy as np
import imageio as img
import matplotlib.pyplot as plt

image = img.imread("D:/source.JPG")

red = image[:, :, 0]
green = image[:, :, 1]
blue = image[:, :, 2]

# merah

imgRed = np.zeros_like(image)

imgRed[:, :, 0] = red

plt.figure(figsize=(10, 10))
plt.subplot(4, 1, 1)
plt.imshow(image)

plt.subplot(4, 1, 2)
plt.imshow(imgRed)

# hijau

imgGreen = np.zeros_like(image)

imgGreen[:, :, 1] = green

plt.subplot(4, 1, 3)
plt.imshow(imgGreen)

# biru

imgBlue = np.zeros_like(image)

imgBlue[:, :, 2] = blue

plt.subplot(4, 1, 4)
plt.imshow(imgBlue)

plt.tight_layout()
plt.show()
