Image taking a picture of your notes, or the whiteboard during lecture on your phone, and having it fed into an algorithm that converts the handwritten digits into text?

Make it a web app first




Converts a picture of text into digital text.
Uses a pretrained model from machine learning.
This is just for practice.
Future approaches: recognizing a specific person's handwriting


Process
=======
Takes image of handwriting from images directory
Uses segmentation to find idividual characters
Finds closest match to each character with classifier
Generates csv to keep track of each character
Outputs converted text