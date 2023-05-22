# Curved Lane Detection
Detection of curved lanes is a more difficult task compared to detection of straight lanes. In straight lane detection, hough transform can be used to detect the straight lanes. However, hough transform can only be used for detecting straight lines and cannot be used to detect curved lines. Therefore, it is not an optimal method to be used in curved lane detection.<br>
In this project, curved lanes are detected using sliding window approach and polynomial curve fitting. Using the slope derived from each lane, the turn can be predicted (whether right turn or left turn) even if one of the lanes is occluded.

## Steps:
1. Detect the lane markings by detecting white line and yellow line
2. Mask the region of interest i.e., the lane region
3. Apply homography to get bird's eye view of the lane
4. Fit a polynomial to the left lane and right line separately
5. Predict the lane points based on the fitted model
6. Fill the lane area with colour for visualisation

![](https://github.com/Ank-G/Curved-Lane-Detection/blob/main/output/curved_lane_detection.gif)

    

