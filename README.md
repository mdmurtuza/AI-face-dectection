# AI-face-dectection
#AI face detection with python
import cv2
trained_face_data = cv2.CasecadeClasifier('haarcascade_frontalface_default.xml')
img = cv2.imread('robert-downey-jr-95')


cv2.imshow('Desktop', img)


cv2.waitKey()

print("code complited")
