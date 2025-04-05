# RANSAC-Feature-Matching

This project demonstrates how to detect and match keypoints between two images using the **SIFT** algorithm and refine the matches using **RANSAC** to estimate a **homography transformation**. This process helps filter out outliers and visualize robust keypoint matches between images.
## 🎯 Objective
- Detect keypoints and descriptors using SIFT
- Match them using FLANN
- Apply Lowe’s ratio test
- Use RANSAC to filter out bad matches
- Visualize the inlier matches and compute the transformation matrix
## Output
- Image showing keypoint matches after RANSAC
- Printed Homography matrix (transformation model)
