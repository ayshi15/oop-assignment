# oop-assignment
# Word Cloud Generator with Mask Image 
This project generates a word cloud based on given text input and mask image, creating a visually customized output.

# Features
Generates a word cloud shaped as per the given mask image.
Automatically removes common stop words using the STOPWORDS library.
Customizable options for background color, contour width, font size, and more.
Visualizes the output using Matplotlib.

# Steps
Step 1: Import Libraries
Install and import the following libraries:
wordcloud
numpy
Pillow
matplotlib
 
Step 2: Load Mask Image
Use the given mask image (e.g., Ayshi.png) and convert it into a NumPy array.

Step 3: Provide Text Input
Load the given text from a file (names.txt) or use a custom string.

Step 4: Generate Word Cloud
Apply the given input text and mask to create the word cloud using the WordCloud class. Customizations include:
  Background color: white
  Contour color and width: green with width 13
  Maximum words: 50
  
Step 5: Display and Save Output
  Display the generated word cloud using Matplotlib. Optionally save the result to an image file.

# Output
The word cloud will be shaped as per the given mask image (Ayshi.png) and visualized with the specified customizations.








