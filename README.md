# Smart Voting System

## Overview

The **Smart Voting System** is an innovative application that leverages face detection technology to enhance the voting process. This system aims to improve the reliability and security of elections by ensuring that only registered voters can cast their votes. Utilizing Python and various machine learning techniques, this project demonstrates how technology can streamline and secure the democratic process.

## Features

- **Face Detection**: Utilizes OpenCV to detect faces in real-time.
- **Registered Voter Identification**: Implements a K-Nearest Neighbors (KNN) classifier to verify the identity of registered voters with a 95% accuracy.
- **User-Friendly Interface**: Designed to provide an intuitive user experience for both voters and election officials.
- **Data Management**: Efficiently handles voter data using JSON for storage and retrieval.

## Technologies Used

- Python
- OpenCV
- NumPy
- pandas
- joblib
- Flask (for web framework)
- KNeighborsClassifier (from scikit-learn)
- JSON (for database)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/smart-voting-system.git
   cd smart-voting-system
2. Install the required dependencies:
   pip install -r requirements.txt
3. Run the application:
   python app.py


Open your web browser and navigate to http://localhost:5000 to access the voting system.
