# Attendify Face App

![attend](https://github.com/YaraElBassaal/Attendify-Recognition-App/assets/124288726/2508a70d-21ff-442a-97da-b3c4ebefa38c)
![attens2](https://github.com/YaraElBassaal/Attendify-Recognition-App/assets/124288726/24b1a8b2-defd-424f-a4b2-179031026976)

## Overview

Attendify Face App is an innovative application designed to streamline the attendance process for college students by utilizing face recognition technology. The app identifies students by their ID numbers from photos and generates an Excel file, making it convenient for professors to manage attendance records.

## Features

- **Student Identification**: Identifies students by their ID numbers through face recognition from photos.
- **Excel Generation**: Automatically generates an Excel file with detected student IDs for easy attendance tracking.
- **User-Friendly GUI**: Features a simple and intuitive graphical user interface built with the Tkinter library.

## Technologies Used

- **Python**: The core programming language used for developing the application.
- **Face-Recognition Library**: Utilized for detecting and recognizing student faces.
- **Tkinter**: Employed to create the user-friendly graphical user interface.
- **OpenCV**: Used for handling image processing tasks.
- **XlsxWriter**: Used for creating and writing data to Excel files.

## How It Works

1. **Student Frame Input**: Provide the application with images of students along with their ID numbers.
2. **Photo Detection**: Insert a photo of a student into the app.
3. **ID Detection**: The app detects the student ID from the photo.
4. **Excel File Generation**: An Excel file is generated containing the detected IDs, facilitating easy attendance management for professors.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/YaraElBassaal/Attendify-Face-App.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Attendify-Face-App
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Run the application:
    ```sh
    python main.py
    ```
2. Use the GUI to upload student images and photos for attendance detection.
3. View and download the generated Excel file containing attendance records.

## Contributing

We welcome contributions! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License.

---

For any questions or support, please open an issue in the repository.

Happy Attendance Tracking!
