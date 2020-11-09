For detection,I use the YOLO algorithm which scans the image all at once using a convolution implementation of the fully connected layer and so faster than region based
CNNs.Non-max suppression is used to eliminate the less accurate bounding boxes.For tracking,along with YOLO, I use Kalman filter
