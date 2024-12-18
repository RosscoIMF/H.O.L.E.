H.O.L.E. - Hole Optimization and Layout Engine v1.00

Overview

H.O.L.E. (Hole Optimization and Layout Engine) is a desktop application designed to help DIY enthusiasts calculate and visualize hole layouts on cylindrical objects. By generating an accurate A4 template, users can drill precision holes for material removal or optimization purposes without requiring advanced tools like indexing heads or dividing heads.

Whether you're working on a piston, a custom cylinder, or any other cylindrical object, H.O.L.E. provides you with the tools to accurately design and plot your layout with ease.

You will need to install Adobe Reader and use Adobe's print scaling function to fine-tune the metric accuracy of the template. Achieving accuracy within ±0.3 mm is achievable with some adjustments to the scaling function in Adobe Raeder.

Features

Mass Calculation: Compute the total material removed based on cylinder dimensions, material density, and hole layout.

Material Selection: Choose from Steel, Aluminum, Delrin, or other materials for accurate density-based mass removal calculations.

Hole Layout Visualization: Design layouts with adjustable hole diameters, rows, and columns.

A4 Template Generation: Create an unwrapped, scaled cylinder template with labeled dimensions and hole positions:
    
Automatically saves as both PNG and PDF formats for easy printing.

User-Friendly GUI: Simple and intuitive interface designed for hobbyists.

About Section: Learn about the origins of the app and its purpose.

System Requirements

Operating System: Windows

Standalone executable, no installation required.

User Instructions

Overview:
This application calculates the mass of material removed from a cylindrical object with drilled holes and generates a visual A4-sized template showing the hole layout. The app allows you to input the cylinder dimensions, hole sizes, material type, and the number of holes to calculate the mass removed and generate a template for printing.
Step-by-Step Instructions:

1. Enter Cylinder Dimensions

    Cylinder Length (mm):
    Enter the length of the cylinder in millimeters.

    Cylinder Diameter (mm):
    Enter the diameter of the cylinder in millimeters.

    Cylinder Thickness (mm):
    Enter the thickness of the cylinder in millimeters (i.e., the wall thickness).

2. Set Hole Specifications

    Drill Size (Hole Diameter in mm):
    Use the slider to select the diameter of the drill hole in millimeters. You can adjust it between 1 mm and 20 mm.

    Holes per Row:
    Use the slider to choose how many holes will be placed per row. The range is from 1 to 20.

    Number of Rows:
    Use the slider to set the number of rows in which holes will be arranged. This can be between 1 and 20.

3. Select Material Type

    Material: Choose the material of the cylinder from the dropdown menu. Options include:
        Steel (Density: 7850 kg/m³)
        Aluminum (Density: 2700 kg/m³)
        Delrin (Density: 1410 kg/m³)
        Custom (Allows you to specify a custom material with a user-defined density)
        (Note: For "Custom" material, you will need to specify a density value in future versions of the app.)

4. Perform Calculation

Click the "Calculate" button to compute the mass of material removed due to the drilled holes. The app will display the result on the screen, showing the total mass removed in grams and the number of holes and rows.

5. Generate A4 Template

    Once the calculation is done, you can generate a visual A4-sized layout for printing by clicking the "Generate A4 Template" button.
        The A4 template will be created based on the hole layout, and the following will be shown:
        A dashed rectangle representing the cylinder with labeled dimensions.
        A grid with crosshairs and circles marking the hole positions.
        This visual can be exported as a PNG image and PDF file for printing.

6. Saving the Template

    The generated A4 template is automatically saved as two files:
        A4_Template.png
        A4_Template.pdf
        The template is saved in the app's current working directory. To ensure new templates appear in the app's home directory, you may need to delete any previously generated templates.

   The exported template will need to be scaled in Adobe Reader, Scaling a print by percentage in Adobe Reader is straightforward. Here's how you can do it:
    
    6.1. Open Your PDF

    Launch Adobe Reader and open the PDF you want to print.

    6.2. Access the Print Dialog

    Go to the File menu and select Print, or press Ctrl + P (Windows) to open the print dialog.

    6.3. Adjust the Scaling Percentage (74.5% worked for me) until the measurements given on the template are correct.

    In the print dialog, locate the Page Sizing & Handling section.
    Select the Custom Scale option.
    Enter the percentage by which you want to scale the print. For example:
        100% prints at the original size.
        50% reduces the size by half.
        200% doubles the size.
        You can input decimal values for fine tuning.

   Feel free to share feedback or suggestions for future improvements. Happy calculating! 🚀

   -Rossco

   https://airgunforums.co.uk/members/rossco.14917/

   https://airgunforums.co.uk/threads/budget-dividing-head.123923/
