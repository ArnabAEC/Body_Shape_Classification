# Body_Shape_Classification

This project involves classifying human body types based on pixel measurements extracted from images. Specifically, the user aims to gather information such as bust, hip, waist, and shoulder dimensions from images and classify individuals into specific body shape categories. These categories include Hourglass, Bottom Hourglass, Top Hourglass, Spoon, Pear, Inverted Triangle, and Rectangle, as defined by traditional real-world measurement criteria.

Key Objectives:
Extract Pixel Measurements:

Measurements such as hip, shoulder, waist, bust, and torso heights are recorded as pixel values from images.
Adapt Body Shape Formulas:

Traditional body shape classification is based on real-world measurements in inches. The project modifies these formulas to work with pixel values or ratios of measurements, assuming that proportions between body parts remain consistent.
Classification Logic:

The project uses Python to implement conditional logic that classifies body shapes based on pixel data. The conditions are derived from real-world body shape formulas but applied proportionally to pixel measurements.
Tools & Workflow:

An Excel file contains the pixel measurements for each individual, which is read into Python using pandas.
The classification algorithm processes the data row by row, calculating the differences and ratios between various body measurements, and assigns a body type to each individual.
The final results are either printed out or saved back into an Excel file with the added classification labels.
Challenges Addressed:
Scaling Pixel Data: Since the project works with images, it focuses on determining body shapes without direct access to real-world dimensions, requiring scaling or relative comparisons of pixel values.

Automated Classification: By implementing classification logic in Python, the process becomes automated, scalable, and easily adjustable for different image data sets or classification rules.
