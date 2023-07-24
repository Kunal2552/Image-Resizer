import cv2

source = "enter image path"
new_img = "newimage.png "

scale = 50

src = cv2.imread(source, cv2.IMREAD_UNCHANGED)
#cv2.imshow("title", src)
neww = int(src.shape[1] * scale / 150)
newh = int(src.shape[0] * scale / 150)

output = cv2.resize(src, (neww, newh))

cv2.imwrite(new_img, output)
