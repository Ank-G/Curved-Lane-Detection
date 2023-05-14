# Curved Lane Detection

Steps:
1. Detect the lane markings by detecting white line and yellow line
2. Mask the region of interest i.e., the lane region
3. Apply homography to get bird's eye view of the lane
4. Fit a polynomial to the left lane and right line separately
5. Predict the lane points based on the fitted model
6. Fill the lane area with colour for visualisation

![](https://github.com/Ank-G/Curved-Lane-Detection/blob/main/output/curved_lane_detection.gif)

    

