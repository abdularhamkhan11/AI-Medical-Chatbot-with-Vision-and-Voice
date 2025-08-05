# AI-Medical-Chatbot-with-Vision-and-Voice
🩺 AI Medical Chatbot with Vision & Voice
An intelligent medical chatbot that uses multimodal AI to simulate a doctor's response by analyzing patient speech and medical images (like skin conditions). Built using Gradio, GROQ’s LLaMA-4 + Whisper, and Python-based audio/image processing.

🚀 Features
🎙️ Voice Input: Patients can speak their symptoms.

🧠 Speech-to-Text (STT): Converts voice into text using Whisper v3.

🖼️ Image Analysis: Upload skin or facial images to analyze possible issues.

💬 Doctor-like Response: Uses LLaMA-4 to generate medical advice in a natural tone.

🔊 Voice Output: Final diagnosis is spoken back using text-to-speech (TTS).

🧪 Multimodal AI: Combines both vision and voice inputs to provide more accurate answers.

🧑‍⚕️ Custom Prompting: Simulates a real doctor's tone (not robotic).

🛠️ Tech Stack
🧠 LLM: meta-llama/llama-4-scout-17b-16e-instruct via GROQ

🗣️ STT: whisper-large-v3 via GROQ

📷 Image Encoding: Base64 JPEG

🗨️ Frontend: Gradio

🎧 Audio Tools: speech_recognition, pydub, gTTS

🔐 Environment: os, .env (for managing GROQ API key)
