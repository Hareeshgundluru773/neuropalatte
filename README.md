# neuropalatte
# Neuro Artify – AI-Powered Image Processing Platform

## Project Overview

Neuro Artify is an AI-powered image processing web application developed to transform, enhance, and edit images using Artificial Intelligence and Deep Learning technologies.

The application integrates a React.js frontend with a Python Flask backend to provide intelligent image processing capabilities. It uses TensorFlow-based models to perform image transformations and deliver processed results through an interactive web interface.

## Key Features

1. Neural Style Transfer

   Applies artistic styles to input images using deep learning techniques, transforming ordinary photographs into artistic representations.

2. Background Removal

   Removes unwanted backgrounds from images using AI-based image processing techniques.

3. Image Enhancement

   Improves the visual quality and appearance of images through image processing techniques.

4. Image Upscaling

   Increases image resolution while aiming to preserve important visual details.

5. Text Removal

   Removes unwanted text from images using image processing techniques.

## Technology Stack

Frontend:
- React.js
- JavaScript
- HTML5
- CSS3
- Vite

Backend:
- Python
- Flask

Artificial Intelligence and Machine Learning:
- TensorFlow
- Deep Learning
- Neural Style Transfer

Image Processing:
- NumPy
- Pillow

API Integration:
- REST APIs
- Axios

Development Tools:
- Visual Studio Code
- Git
- GitHub

## System Architecture

The application follows a client-server architecture.

1. The user uploads an image through the React.js frontend.
2. The frontend sends the image to the Flask backend using API requests.
3. The backend receives and processes the uploaded image.
4. TensorFlow-based models perform the required image transformation.
5. The processed image is returned to the frontend.
6. The user can preview and download the generated output.

## Project Structure

```text
Neuro_Artify/
|
|-- StyleTransfer/
|   |
|   |-- app.py
|   |-- savedDirectory/
|   |
|   |-- frontend/
|       |
|       |-- src/
|       |   |-- Components/
|       |   |   |-- StyleTransfer.jsx
|       |   |
|       |   |-- ...
|       |
|       |-- public/
|       |-- package.json
|       |-- vite.config.js
|
|-- README.md
```

## Installation and Setup

### Prerequisites

- Python 3.x
- Node.js and npm
- Git
- Visual Studio Code

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/Neuro-Artify.git
```

Navigate to the project directory.

```bash
cd Neuro-Artify
```

### Step 2: Configure the Backend

Navigate to the backend directory.

```bash
cd StyleTransfer
```

Create a Python virtual environment.

```bash
python -m venv venv
```

Activate the virtual environment on Windows.

```bash
venv\Scripts\activate
```

Install the required dependencies.

```bash
pip install flask tensorflow numpy pillow flask-cors
```

Start the Flask backend server.

```bash
python app.py
```

### Step 3: Configure the Frontend

Open another terminal and navigate to the frontend directory.

```bash
cd StyleTransfer/frontend
```

Install the frontend dependencies.

```bash
npm install
```

Start the React development server.

```bash
npm run dev
```

Open the local development URL displayed in the terminal to access the application.

## Project Objectives

- Develop an AI-powered image processing application.
- Understand the practical implementation of Deep Learning models.
- Integrate machine learning models with web technologies.
- Implement communication between frontend and backend using REST APIs.
- Gain practical experience with Python, Flask, React.js, and TensorFlow.

## Future Enhancements

- Integrate additional neural style transfer models.
- Improve image processing performance.
- Implement user authentication and account management.
- Introduce batch image processing functionality.
- Implement cloud-based image storage.
- Deploy the application for public access.

## Learning Outcomes

- Understanding AI and Deep Learning applications.
- Practical implementation of image processing techniques.
- Backend development using Python and Flask.
- Frontend development using React.js.
- Integration of machine learning models with web applications.
- Working with REST APIs and third-party libraries.

## Developer Information

Name: Gundluru Hareesh

Education: Bachelor of Technology in Computer Science and Engineering

Graduation Year: 2026

## License

This project is developed for educational and learning purposes. Add an appropriate open-source license if you intend to distribute the project for public use.
