# Vehicle_no_plate_detection
Number Plate Recognition System is car license plate identification system made using OpenCV , EasyOCR , imutils ,numpy , matplotlib in python. It can be used to detect number plate from image.                                                                                                                                                     
Number Plate recognition, also called License Plate realization or recognition using image processing methods is a potential research area in smart cities and the Internet of Things. An exponential increase in the number of vehicles necessitates the use of automated systems to maintain vehicle information for various purposes       
# Approach                                                                                                                                                                
Find all the contours in the image.                                                                                                                                                                                     
Find the bounding rectangle of every contour.                                                                                                                                     
Compare and validate the sides ratio and area of every bounding rectangle with an average license plate.                                                                  
Apply image segmentation in the image inside the validated contour to find characters in it.                                                                                
Recognize characters using an OCR.
