1A

print('welcome')
for i in range(10):
    print(i)
print("end of program")


1B
import cv2
abc= cv2.imread("E:\IPMV images\light1.jpg",1)
cv2.imshow('cameraman',abc)
print("size of the image:",abc.size)
print("shape of image:", abc.shape)
print("type of the image:", abc.dtype)
print('brightness:',abc[100,100,0])
print(abc)
cv2.waitKey(0)
cv2.destroyAllWindows()

imgcrop


import cv2
abc= cv2.imread("E:\IPMV images\light1.jpg",1)
cv2.imshow('cameraman',abc)
print("size of the image:",abc.size)
print("shape of image:", abc.shape)
a=abc[200:,150:]
cv2.imshow("crop",a)
cv2.waitKey(0)
cv2.destroyAllWindows()


