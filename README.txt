
Inside the code folder, there are separate codes for the 1st and 2nd parts of the assignment.

To use Part-1, you need to write the path of the images in the image_path section on the 10th line. 
If you only want to see a sample of them, do not change the code on line 63, 
but if you want to find the hough circle transform of all images in the dataset, 
replace the code on line 63 with the code on line 62. 
You can set the radius sizes of the circles you want to find from lines 69 and 70, 
and you can enter the minimum number of votes as a parameter when calling the function on line 71. 
It is defined as 150.

To use Part-2, you need to enter the path for images and templates on lines 22 and 23, 
then you need to create an object from the class and search for the template in the image, 
all you have to do is create an object as "object = OffsetDetector(image, template)" 
and "object.plot_offset(output)" to output a picture. If you want to find out which image the 
templates will automatically match, run code block 99-113. 
To run directly with the image the template is in, run code block 119-128.

The reason for these different codes in part-1 and part-2 is to make it easier to check the assignment. 
You can find the reasons in detail in the "Notes" section of the report.

The explanation of the codes is included in the report in more detail.