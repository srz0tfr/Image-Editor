# Image Processing Web Application

## Overview
This project is a Django-based web application for image processing. It provides various image transformation techniques such as compression, rotation, resizing, and filtering. The backend is implemented using Django, while the frontend is managed with HTML, CSS, and JavaScript.

## Features
- **Image Compression**: Reduces image size while maintaining quality.
- **Image Rotation & Resizing**: Allows users to modify the image dimensions.
- **Edge Detection & Blurring**: Implements filters like Gaussian Blur, Emboss, and Edge Detection.
- **Custom Filters**: Users can apply custom-defined transformations.

## Project Structure
```
Main/
│── sns_proj/          # Django project settings and configuration
│── file/              # App containing image processing logic
│── static/            # Static files including C++ implementations of some filters
│── templates/         # HTML files for the frontend
│── manage.py          # Django management script
│── media/             # (Excluded) Stores user-uploaded images
│── db.sqlite3         # (Excluded) SQLite database file
```

## Installation & Setup
### 1. Clone the Repository
```bash
git clone <repository-url>
cd Main
```
### 2. Set Up Virtual Environment
```bash
python -m venv ENV
source ENV/bin/activate  # On MacOS/Linux
ENV\Scripts\activate    # On Windows
```
### 3. Install Dependencies
```bash
pip install -r requirements.txt
```
### 4. Apply Migrations
```bash
python manage.py migrate
```
### 5. Run the Server
```bash
python manage.py runserver
```
The application will be available at `http://127.0.0.1:8000/`.

## Excluded Files & Folders
The following are ignored and should not be uploaded to GitHub:
```
db.sqlite3
.DS_Store
__pycache__/
media/
migrations/
```

## Contribution
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

## License
This project is open-source and available under the MIT License.

