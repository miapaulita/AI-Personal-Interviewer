# 💬 AI Personal Interviewer
### Overview
AI-Personal-Interviewer is your virtual mock interview coach! As a new grad, you can practice with an AI that offers instant feedback, instead of scheduling with people. The goal is to make it voice-controlled for live chats, tailoring interviews based on job frameworks and assessing your responses to ensure you meet the criteria for the job!

## Prerequistes: Need Python Libraries
- assemblyai: For real-time speech-to-text transcription.
- openai: For generating AI responses based on the transcribed text.
- elevenlabs: For streaming audio responses to the user.
- mpv: A media player for playing audio streams.
- portaudio: A cross-platform audio I/O library.


## Installation:
1. Clone the repository:
  ```bash
  git clone <repository-url>
  cd <repository-directory>
  ```

2. Install Python Libraries within your Project Terminal:
  ```bash
  brew install portaudio
  pip install "assemblyai[extras]"
  pip install elevenlabs==0.3.0b0
  brew install mpv
  pip install --upgrade openai
  ```

3. Run the project: 
   Go to your project terminal and run your project file
  ```bash
  python app.py
  ```

## Code Explanation:
- Real-Time Transcription with AssemblyAI:
  AssemblyAI performs real-time speech-to-text transcription. 
It listens to audio input and converts it into text, which can then be used for generating responses.
- Pass Real-Time Transcript to OpenAI:
  The transcribed text is then sent to OpenAI, which generates a response based on the user's input.
  This allows for interactive conversations with the AI.
- Live Audio Stream from ElevenLabs:
  Finally, the generated response is streamed as live audio to the user through ElevenLabs, providing a seamless auditory experience.

## Acknowledgments:
This project builds upon [AssemblyAI-AI-Voice-Bot](https://github.com/smithakolan/AssemblyAI-AI-Voice-Bot/tree/main) repository. 
It guides you through creating a real-time AI voice bot using Python, AssemblyAI, and ElevenLabs. 




