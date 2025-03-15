# assignment-AI-Developer-Exercise
Summary of Verbal Communication Skills Trainer
This project is a CLI-based Verbal Communication Skills Trainer that utilizes the OpenRouter API to help users enhance their speaking abilities through AI-driven interactions. It provides real-time conversation practice, voice input processing, structured skill-building exercises, and automated presentation evaluations.

Technologies & Libraries Used
LLM API: OpenRouter API (using Mistral 7B model) for AI-generated responses.
Speech Recognition: speech_recognition for converting spoken input into text.
Text-to-Speech: gTTS (Google Text-to-Speech) to generate AI voice responses.
Audio Playback: pydub for handling audio playback instead of playsound.
API Communication: requests library for making API calls.
Error Handling & Logging: Built-in retry mechanisms for API failures and handling unexpected errors.
Data Storage: User progress and responses are stored in a JSON file.
Core Features


AI Chat Interaction: Users can engage in text-based conversations with AI to practice verbal communication.
Voice Input Processing: Converts spoken words into text using speech_recognition.
Text-to-Speech Output: AI responses can be played as audio output using gTTS and pydub.

Training Modules:
Impromptu Speaking: AI evaluates user responses to random speaking topics.
Storytelling: AI analyzes narrative structure and vocabulary usage.
Conflict Resolution: AI helps users improve diplomatic and assertive communication.

Presentation Feedback System:
Evaluates speech structure, clarity, tone, and engagement.
Provides scores and improvement suggestions.

Error Handling & API Retry Logic:
If the API request fails, the system retries with exponential backoff.
User-friendly messages handle unexpected failures.
Progress Tracking: User responses and AI feedback are saved in a JSON file for future reference.
Future Enhancements
Developing a web-based or mobile application interface for better accessibility.
Multi-language support for non-English speakers.
Advanced speech analysis to assess tone, pitch, and pacing.
Visual progress tracking through graphs and insights.
