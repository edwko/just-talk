**Just Talk**
================

Real-time Voice Conversation Interface with LLM

**Overview**
------------

Just Talk is a Python library that enables real-time voice conversations with Language Models. It provides a seamless interface for users to engage in natural-sounding conversations with LLMs, using a combination of Speech-to-Text (STT) and Text-to-Speech (TTS).

**Features**
------------

* **Real-time Speech Recognition**: Listens to the user's microphone input and detects speech in real-time.
* **Whisper-based Transcription**: Transcribes the recorded audio using the Whisper STT model.
* **LLM Integration**: Passes the transcribed text to a Large Language Model (LLM) for response generation.
* **Sentence-by-Sentence TTS**: Converts each sentence of the LLM's response into audio using a TTS engine.
* **Interruptible TTS**: Allows the user to interrupt the TTS output if they begin speaking while the LLM is generating a response, enabling a more human-like conversation experience.
