# AI Personal Interviewer

This project implements a real-time AI personal interviewer using AssemblyAI for transcription, OpenAI for generating responses, and ElevenLabs for streaming audio responses.

## Table of Contents

1. [Installation](#step-1-install)
2. [Real-Time Transcription](#step-2-real-time-transcription-with-assemblyai)
3. [Pass Real-Time Transcript to OpenAI](#step-3-pass-real-time-transcript-to-openai)
4. [Live Audio Stream from ElevenLabs](#step-4-live-audio-stream-from-elevenlabs)
5. [Usage](#usage)
6. [License](#license)

## Step 1: Install Python Libraries

Before running the application, you need to install the required Python libraries. You can do this by using the following command:

```bash
pip install assemblyai openai elevenlabs mpv portaudio
Required Libraries
assemblyai: For real-time speech-to-text transcription.
openai: For generating AI responses based on the transcribed text.
elevenlabs: For streaming audio responses to the user.
mpv: A media player for playing audio streams.
portaudio: A cross-platform audio I/O library.
Step 2: Real-Time Transcription with AssemblyAI
AssemblyAI performs real-time speech-to-text transcription. It listens to audio input and converts it into text, which can then be used for generating responses.

Step 3: Pass Real-Time Transcript to OpenAI
The transcribed text is then sent to OpenAI, which generates a response based on the user's input. This allows for interactive conversations with the AI.

Step 4: Live Audio Stream from ElevenLabs
Finally, the generated response is streamed as live audio to the user through ElevenLabs, providing a seamless auditory experience.

Usage
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/AI-Personal-Interviewer.git
cd AI-Personal-Interviewer
Run the application:

bash
Copy code
python app.py
Follow the on-screen instructions to interact with the AI personal interviewer.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

sql
Copy code

### Notes:

- **Customization**: Replace the placeholder GitHub URL in the usage section with your actual repository URL.
- **Installation Instructions**: Ensure that the installation commands match your project’s requirements and that the listed libraries are indeed required.
- **Add Sections**: Feel free to add more sections, such as "Contributing," "Features," or "Contact," depending on your project's scope and audience.

## Acknowledgments:

This project builds upon the original concept presented in the [AssemblyAI-AI-Voice-Bot](https://github.com/smithakolan/AssemblyAI-AI-Voice-Bot/tree/main) repository. It guides you through creating a real-time AI voice bot using Python, AssemblyAI, and ElevenLabs. 




