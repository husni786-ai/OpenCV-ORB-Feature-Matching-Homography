# 🌟 ORB Feature Matching and Image Registration (OpenCV)

This project provides a Jupyter Notebook focused on the essential Computer Vision task of **Image Registration** using the **ORB (Oriented FAST and Rotated BRIEF)** algorithm within the **OpenCV (cv2)** library. The notebook is designed to find correspondence between two different images and calculate the geometric transformation required to align them.

---

## 🎯 Project Goals

The objective is to implement a feature-based image alignment pipeline, which includes:

1.  **Feature Detection:** Utilize the ORB algorithm to efficiently detect keypoints and compute unique descriptors in two separate input images.
2.  **Feature Matching:** Use a brute-force or similar matcher to find the best corresponding features between the two images based on descriptor similarity.
3.  **Geometric Calculation:** Calculate the **Homography Matrix** (H) that maps points from one image plane to the other.
4.  **Transformation Analysis:** Extract and display the **Rotation Matrix** and **Homography Matrix**, which define the spatial relationship between the images.

## ⚙️ Technology Stack and Dependencies

The project relies on the core components of the Python Computer Vision ecosystem.

| Library | Role |
| :--- | :--- |
| **`opencv-python (cv2)`** | Core library for image processing, feature detection, and matrix calculations. |
| **ORB (`cv2.ORB_create`)** | The algorithm used for fast and rotation-invariant keypoint detection and descriptor computation. |
| **`cv2.BFMatcher`** | Used to find the best matches between the descriptors of the two images. |

### Installation

```bash
pip install opencv-python
