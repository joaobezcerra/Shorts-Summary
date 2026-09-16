<h1 align="center">
  <img src="https://github.com/guisant/nlwia/assets/37338838/28640e18-c592-4495-b810-df387c6c52aa" alt="Logo" />
</h1>

<p align="center">
  <a href="#about">About</a> •
  <a href="#how-to-run-the-project">How to Run</a> • 
  <a href="#technologies">Technologies</a> 
</p>

<br>

# Shorts Summary

Shorts Summary is a web application designed to generate summaries of YouTube Shorts. It leverages Artificial Intelligence to transcribe the video content and subsequently generate a concise summary. 

This project was developed during the Foundations track of the NLW IA edition.

<br><br>

## How to Run the Project

This project is divided into three main components:

1. **Backend**
2. **Frontend**
3. **Artificial Intelligence:** Utilizes the Whisper model for Automatic Speech Recognition (ASR) and the Bart model for text summarization.

### Prerequisites

Before starting, ensure you have the following tools installed on your system:
* [Git](https://git-scm.com)
* [Node.js](https://nodejs.org/en/)

Additionally, a code editor such as [VSCode](https://code.visualstudio.com/) is recommended.

### Running the Backend (Server)

```bash
# Clone this repository
$ git clone [https://github.com/guisant/nlwia.git](https://github.com/guisant/nlwia.git)

# Navigate to the project directory in your terminal
$ cd nlwia

# Install the dependencies
$ npm install

# Run the application in development mode
$ npm run server

# The server will start on port 3333. 
# Access it via: http://localhost:3333/summary/<video_id> (the ID found after /shorts/ in the URL)
