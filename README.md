# Player Tracking and Analysis in Football Videos

## Overview
This project focuses on detecting and tracking players, referees, and footballs in match footage using YOLO, a state-of-the-art object detection model. To enhance accuracy, the model is further trained, and K-means clustering is applied for team classification based on jersey colors. The system analyzes ball possession percentages and utilizes optical flow to measure camera movement, ensuring precise player tracking. Perspective transformation is implemented to convert pixel-based movement into real-world distances, enabling accurate calculations of player speed and distance covered. This project integrates multiple computer vision techniques, making it a valuable solution for sports analytics.

## Features
- **Object Detection**: Detects players, referees, and the football using YOLO.
- **Team Classification**: Uses K-means clustering to assign players to teams based on jersey colors.
- **Ball Possession Analysis**: Measures the percentage of time each team has possession of the ball.
- **Player Movement Tracking**: Uses optical flow to track player movement frame by frame.
- **Perspective Transformation**: Converts pixel-based measurements into real-world distances.
- **Speed and Distance Calculation**: Computes player speed and distance covered in meters.

## Technologies Used
- **Python**
- **YOLO (You Only Look Once) Object Detection**
- **OpenCV**
- **K-means Clustering**
- **Optical Flow**
- **Perspective Transformation**
- **NumPy & Pandas**
- **Matplotlib for Visualization**


## Contributing
Contributions are welcome! Feel free to fork the repository, submit issues, or make pull requests.

## License
This project is licensed under the MIT License. See `LICENSE` for details.

## Contact
For any inquiries, reach out via email at **auraelisha786@gmail.com**.
