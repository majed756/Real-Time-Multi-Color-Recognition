# Real-Time-Multi-Color-Recognition

Python-based computer vision application utilizing OpenCV. It is designed to detect and track the colors red, green, and blue simultaneously in a live video feed.

---

## 💡 Project Concept

The core idea behind this project is to give a machine the ability to "see" and differentiate between distinct colors in real-time. By leveraging computer vision, the system actively scans a live camera feed, isolates specific color signatures, and dynamically maps bounding boxes around objects that match the targeted colors (Red, Green, and Blue). 

Instead of relying on standard RGB visual data—which is highly sensitive to shadows and changes in environmental lighting—this project evaluates frames using the **HSV (Hue, Saturation, Value)** color space. This approach allows the system to analyze the actual "colorfulness" of an object independently of how bright or dark the room is, resulting in robust and accurate object tracking.

## 🎯 Key Capabilities

*   **Simultaneous Tracking:** Continuously monitors and identifies multiple distinct colors within the exact same frame without processing lag.
*   **Dynamic Noise Filtering:** Applies mathematical masking to filter out random background static, ensuring that only solid, prominent objects are tracked while ignoring tiny specks of color.
*   **Live Visual Feedback:** Provides an immediate, augmented reality-style overlay on the video feed, tagging detected objects with their respective bounding frames and labels.

  ## 🧪 Color Testing Results

The system was tested using differently colored objects to verify the accuracy of the HSV masking and bounding box logic. 

### Red Recognition Test
<img width="871" height="661" alt="image" src="https://github.com/user-attachments/assets/5f21a2b3-ee40-40c5-a3a4-ec771d3c6631" />


### Green Recognition Test
<img width="877" height="671" alt="image" src="https://github.com/user-attachments/assets/70e9e113-23d3-4329-89ae-de1f1135a96f" />


### Blue Recognition Test
<img width="842" height="662" alt="image" src="https://github.com/user-attachments/assets/226112f1-2562-4361-a4d5-ac8ea7e1bd68" />


## 🚀 Practical Applications

Because this concept translates raw visual data into actionable tracking coordinates, the foundation of this project can be integrated into broader hardware or software environments:
*   **Robotics & Hardware Automation:** Guiding motorized systems or robotic arms to sort physical items based on their color.
*   **Interactive Interfaces:** Triggering specific software events or UI changes when a user presents a uniquely colored object to a camera.
*   **Spatial Tracking:** Generating foundational positional data for moving targets within a physical space.
