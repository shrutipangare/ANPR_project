# ANPR_project

AI-powered application designed to detect and recognize vehicle number plates from multiple countries using advanced deep learning and image processing techniques. The project leverages TensorFlow Object Detection API, Optical Character Recognition (OCR), and machine learning models to provide efficient and accurate recognition of multinational license plates.

Features

Multinational License Plate Detection: Supports number plate recognition across various countries with different formats and styles.
Real-Time Processing: Detects and recognizes plates from images or live video streams.
Optical Character Recognition (OCR): Extracts text from license plates with high accuracy.
Categorization: Classifies vehicles into predefined categories (e.g., cars, trucks, motorbikes).
Speed Detection: Analyzes vehicle speed and flags violations for enforcement purposes.
Database Integration: Stores detected license plate information and timestamps for analysis

Technology Stack

- Programming Languages: Python
- Frameworks & Libraries: TensorFlow (SSD MobileNet v2 COCO)
- EasyOCR for text extraction
- Flask for backend
- OpenCV for image processing
- Deployment: AWS Cloud Services
- Database: MongoDB
- Frontend: React, HTML, CSS


System Requirements

Hardware
Functioning CCTV Camera or equivalent
Minimum 4GB RAM (8GB recommended)
NVIDIA/AMD GPU for training models
Software
Python 3.8+
TensorFlow Object Detection API
Google Colab (for training and testing)
MongoDB (for data storage)

Future Enhancements

Offline Support: Enable offline processing without cloud dependency.
Enhanced Speed Detection: Real-time vehicle speed monitoring.
Cross-Platform Support: Develop iOS and Android applications for broader usability.
Social Features: Integrate alerts and notifications for flagged violations.







