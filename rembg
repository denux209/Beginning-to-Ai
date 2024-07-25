from google.colab.patches import cv2_imshow
import cv2
from rembg import remove
img = cv2.imread("/content/infografik template.jpg")
cv2_imshow(img)
image = cv2.imread("/content/infografik template.jpg")

height, width, channels = image.shape
print("Width of image:", width)
print("Height of image:", height)
print("Number of color channels(RGB):", channels)

input_path = '/content/infografik template.jpg'
output_path = 'output.png'

with open(input_path, 'rb') as i:
    with open(output_path, 'wb') as o:
        input = i.read()
        output = remove(input)
        o.write(output)
