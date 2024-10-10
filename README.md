# BrainFlix-VideoStreaming-App
## Overview
![brainflix-responsive mockup](https://github.com/user-attachments/assets/35d24961-6009-4106-ad7a-be12d79de7cc)

BrainFlix is a full-stack video streaming platform that mimics the functionality of popular video-sharing websites like YouTube. The app allows users to view, upload, and interact with videos, providing a dynamic and engaging user experience. This project was built to showcase modern development practices and seamless front-end and back-end integration.

## Getting Started

### Prerequisites
This is an example of  how to install the prerequisite softwares.
* npm
  ```sh
  npm install npm@latest -g
  ```
  
### Installation
_Below is an example of how you can install and set up the Brainflix application._
- To start the front-end
1. Change to "frontend" folder
   ```sh
   cd client
   ```
2. Run the front-end
   ```sh
   npm run dev
   ```
- To start the back-end (Local JSON storage)
1. Change to "api" folder
   ```sh
   cd api
   ```
2. Run the back-end
   ```sh
   npm run start
   ```

## Introduction
- React.js: For building the interactive and responsive user interface.
- Node.js & Express.js: Backend server to handle API requests and routing.
- Local JSON Storage: The application uses JSON files as its backend to store video data, including video information and comments.
- RESTful APIs: For efficient data communication between the front-end and back-end.
- Sass: For styling and creating a visually appealing UI.

## Description
The BrainFlix Video Streaming App enables users to explore a variety of video content, leave comments, and upload new videos, simulating the experience of a professional video streaming platform. Key features of the app include:
- Video Upload and Management: Users can upload video files along with their titles, descriptions, and other metadata, which are stored in local JSON files within the backend folder.
- Commenting System: Integrated commenting functionality allows users to leave comments on individual videos, facilitating interaction and user engagement.
- Responsive Design: The UI, built with React.js and styled with Sass, ensures that the application is responsive and provides a consistent experience across different devices and screen sizes.
- Dynamic Video Player: The app features a custom video player that supports playback controls, displays video details, and shows a comments section.

By leveraging JSON files to manage the backend data, the BrainFlix app demonstrates how a full-stack application can be developed with local storage, providing a simplified yet effective solution for data handling and management.
