# OrganInsight: AI-Powered 3D Medical Image Analysis

## Introduction

OrganInsight aims to democratize access to 3D medical image analysis by combining the power of artificial intelligence with a user-friendly web interface. By automating the classification of 3D organ scans and providing clear, concise explanations, OrganInsight can assist in diagnosis, education, and improved patient communication.

## Features

- **3D Medical Image Upload:** Users can easily upload 3D medical image files (support for common formats to be implemented).
- **Interactive 3D Visualization:** View uploaded 3D medical images in an interactive environment within the web browser.
- **AI-Powered Classification:** Utilizes a pre-trained PyTorch model to automatically classify the organ depicted in the 3D scan.
- **Clear Classification Results:** The identified organ is displayed prominently alongside the 3D image.
- **Plain-Language Explanations:** Integration with the ChatGPT API provides easy-to-understand descriptions of the classified organ.
- **User-Friendly Interface:** Intuitive and visually appealing design for seamless user experience.
- **Web-Based Accessibility:** Access the application through any modern web browser.

## Technologies Used

- **Frontend:**
    - HTML
    - CSS
    - JavaScript
- **Backend:**
    - Python
    - Flask (or similar web framework)
- **AI Model:**
    - PyTorch
- **Dataset:**
    - OrganMNIST3D
- **Natural Language Processing:**
    - ChatGPT API
