# Ex.No.-1.2-Design and Draft the given 2D Sketches in modelling software.

## AIM
 To sketch the given drawing with dimensions using fusion 360 tool.
 
## REQUIREMENTS
 1. Autodesk fusion 360
 2. Windows 10
 3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
 4. 2.5 Mbps or faster download; 500 Kbps or faster upload 
 
 ## PROCEDURE

# Detailed Procedure for Creating the Part and Its Drawing in Fusion 360

## A. Create the sketch

1. Open **Fusion 360** and create a new design. Save the file with an appropriate name.
2. Select **Create Sketch** and choose the plane you want to use for the part. The **XY plane** is suitable for a flat plate.
<img width="1920" height="1010" alt="Screenshot (146)" src="https://github.com/user-attachments/assets/011ab362-f2e7-4cd5-b24b-ac3bfcc438d5" />

## B. Draw the central circles and pattern

3. Select **Circle > Center Diameter Circle**. Click the origin to set the center, then draw a circle with a **16 mm radius**. Since Fusion’s circle tool usually asks for diameter, enter **32 mm**.
4. Repeat from the same origin to draw concentric circles with radii **21 mm, 32 mm, and 40 mm**. Enter diameters of **42 mm, 64 mm, and 80 mm**, respectively. Make sure all four circles share the same center.
   <img width="1920" height="1007" alt="Screenshot (189)" src="https://github.com/user-attachments/assets/812148a8-d956-42e1-8fab-ad4f2976653c" />

5. Select **Line** and draw two vertical lines through the origin, across the circular area between the circles with radii **21 mm and 32 mm**. Apply the **Vertical** constraint if the lines do not automatically align vertically.
   <img width="1920" height="1000" alt="Screenshot (190)" src="https://github.com/user-attachments/assets/27aae8dd-5000-4741-b6ed-dbfa8787fbff" />

6. Select **Sketch > Circular Pattern**. For **Objects**, select the two lines. For **Center Point**, select the origin. Set the quantity and angular spacing to match the reference drawing, then confirm the pattern.
    <img width="1920" height="1011" alt="Screenshot (193)" src="https://github.com/user-attachments/assets/0a2b221f-ab91-42e6-9eed-248a207c91ca" />

7. Select **Trim** and remove the circle and line portions that are not part of the central feature. Keep the arcs and boundaries that form the required segmented shape. Zoom in as needed to avoid trimming the wrong section.
    <img width="1920" height="997" alt="Screenshot (195)" src="https://github.com/user-attachments/assets/3077de51-b43a-4ce4-a690-56b217cc329d" />


## C. Draw the upper-left and lower-left features

8. Use **Center Diameter Circle** to draw the upper-left circles with radii **21 mm and 15 mm** (diameters **42 mm and 30 mm**). Position their centers to match the reference drawing.
9. Add dimensions to locate the circle centers.
10. Draw another circle with a **20 mm radius** (diameter **40 mm**) beside the upper-left circles to form the curved transition. Position it so the curve meets the neighboring geometry as shown.
11. Select **Trim** and remove the unwanted portions of the circles, leaving the arcs needed for the outer shape and the adjoining curve.
12. Select the upper-left circles and curved section. Choose **Sketch > Mirror**. Select the horizontal centerline as the mirror line and confirm. This creates the matching lower-left features.
    <img width="1920" height="1000" alt="Screenshot (197)" src="https://github.com/user-attachments/assets/3248ff98-fdbe-49e6-b2a7-ab2001a9f202" />


## D. Finish the left-side outline and mirror it

13. Draw the additional circles with radii **15 mm and 20 mm** in the center-left area, following their positions in the reference drawing.
14. Select **Line** and connect the upper and lower left-side features to form the straight sections of the outline. Apply **Coincident** constraints where line endpoints meet arcs, and **Tangent** constraints where a straight segment should flow smoothly into a curve.
    <img width="1920" height="1011" alt="Screenshot (198)" src="https://github.com/user-attachments/assets/c6e1c05f-3619-43db-86f4-2d33705f573e" />

15. Use **Trim** to remove any remaining circle or line sections that extend beyond the intended outline. Check that the left-side boundary forms a continuous, closed profile where the plate body should be.
16. Select the completed left-side geometry, choose **Sketch > Mirror**, and select the vertical centerline as the mirror line. Confirm to create the right-side features.
    <img width="1920" height="1021" alt="Screenshot (202)" src="https://github.com/user-attachments/assets/b8caa08c-85e6-4fdb-8235-db8b50f83761" />


## E. Check and finish the sketch

17. Compare the sketch with the reference drawing. Check the central segmented feature, six outer circles, curved transitions, and overall symmetry.
18. Make sure there are no unintended gaps or overlapping segments. Select **Finish Sketch** when the profiles are ready.
<img width="1920" height="1007" alt="Screenshot (205)" src="https://github.com/user-attachments/assets/6ca66c17-6c2f-4f2b-913e-f207019d3bb5" />

## F. Extrude the part

19. Select **Create > Extrude**.
20. Click the closed profile that represents the plate. If holes and openings are already cut out in the sketch, Fusion should show them as empty regions within the selected profile.
21. Enter the part thickness specified by your assignment. Choose the appropriate operation, usually **New Body** for a standalone part, and confirm the extrusion.
    <img width="1920" height="1007" alt="Screenshot (206)" src="https://github.com/user-attachments/assets/587a7e3b-e1b7-41e9-a75e-4fe5dc2909e3" />
Now the 2D projection to 3D projection.
<img width="1920" height="1000" alt="Screenshot (185)" src="https://github.com/user-attachments/assets/a4de1402-27fb-47f2-94cb-ac5d6521455a" />


## G. Create and dimension the drawing

22. Select **Design > Drawing > From Design**.
23. Choose the sheet size, units, and drawing standard required by your assignment. Confirm to create the drawing.
24. Place the base view on the sheet, then add projected views if required to show the part’s thickness and shape clearly.
25. Add dimensions for the radii, hole locations, center feature, and other sizes indicated in the reference drawing. Avoid adding guessed dimensions; use values from the assignment or original drawing.
26. Review the drawing for readable dimensions, correct views, and a suitable scale. Save the drawing.


 ## OUTPUT
 <img width="1920" height="1000" alt="Screenshot (186)" src="https://github.com/user-attachments/assets/0320ec75-2b8f-4b06-88a8-fdf7b7cc001e" />

 
 ## RESULT
 Thus the given sketch is drawn and drafted using fusion 360 tool.
