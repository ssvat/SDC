Project: Finding Lane Lines on the Road 

Objective: Make a pipeline that finds lane lines on the road

Reflection
1. Pipeline flow: 
A. call all the functions provided (e.g., canny edge detection, hough transform) and modified slightly to construct a lane-finding pipeline   
B. Create a series of functions for a new draw_lines() function, listed as below.
* average_lines(lines)
* lines_points(y1, y2, line)
* two_lines(image, lines)
* new_draw_lines(img, lines, color=[255, 0, 0], thickness=2)
* new_hough_lines(image,lines)

Shortcomings
The new draw line functions do not work with the challenge video. It stopped with an overflow error.

Suggestion
More troubleshooting can be implemented if time is allowed to investigate if the loops are not robust enough, 
or the error is unrelated, purely from the jupyter notebook. If the latter, this can be solved when the notebook is relaunched. 