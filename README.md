# Video-to-Audio Converter and Transcription Tool

This practical project, created as part of a course, demonstrates the conversion of video files into audio format, transcription of the audio content using the OpenAI API, and the generation of prompts for video descriptions or titles. It's built using the following technologies:

- **Frontend**:
  - React
  - Tailwind CSS
  - Shadcn/UI (a custom UI library)

- **Backend**:
  - Node.js
  - Fastify (web framework)

- **Additional Component**:
  - WebAssembly (for optimized performance)

## Project Overview

The Video-to-Audio Converter and Transcription Tool streamlines the process of converting video files into audio and generating transcriptions, making it easier to create content for various platforms, such as YouTube.

## Features

- **Video to Audio Conversion**: Upload video files in various formats (e.g., MP4, AVI) and convert them into audio files (e.g., MP3, WAV).
- **Transcription**: Utilize the OpenAI API to transcribe the audio content, converting spoken words into text.
- **Prompt Generation**: Automatically generate prompts for YouTube video descriptions or titles based on the content of the transcribed text.
- **User-Friendly Interface**: A simple and intuitive frontend interface for easy interaction.

## Getting Started

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/VictorManoelCostaDeBarros/nwlia
   cd video-to-audio-converter
Install Dependencies:

bash
Copy code
cd frontend
npm install
cd ../backend
npm install
Set Up OpenAI API:

Sign up for an OpenAI API key if you haven't already.

Create a .env file in the backend directory and add your API key:

makefile
Copy code
OPENAI_API_KEY=your_api_key_here
Build the WebAssembly Component:

If you are using WebAssembly, follow the instructions to build and optimize the WebAssembly component.

Run the Application:

Start the frontend:

bash
Copy code
cd frontend
npm start
Start the backend:

bash
Copy code
cd backend
npm start
Access the Application:

Open your browser and navigate to http://localhost:3000 to use the application.

Usage
Uploading a Video: Use the frontend to upload your video file.
Transcription: The application will use the OpenAI API to transcribe the audio from the video.
Prompt Generation: After transcription, prompts for YouTube descriptions or video titles will be automatically generated.
Export: Save the generated prompts for your reference.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Special thanks to OpenAI for their powerful API.
Inspired by the need for efficient video content creation.
Contact
For questions or feedback, feel free to contact the project maintainers:

Victor Manoel: victor.manoel8@hotmail.com
Co-author's Name: Co-author's Email