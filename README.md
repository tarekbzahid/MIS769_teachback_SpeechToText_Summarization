# Speech-to-Text and Summarization for Recorded Phone Calls

This project aims to transcribe a recorded phone call from a potential customer using AssemblyAI's speech-to-text API and summarize the main points of the conversation using Hugging Face's Transformers library.
Installation

Install the required packages using pip:

bash

pip install assemblyai transformers

Usage

To use this project:

    Transcribing Audio to Text:
        Obtain an API key from AssemblyAI for accessing their speech-to-text API.
        Replace "path/to/your/audio/file.mp3" in the script with the path to your recorded phone call audio file.
        Run the script to transcribe the call.

    Summarizing Text:
        After obtaining the transcript, use Hugging Face's Transformers library for text summarization.
        Adjust parameters in the summarization pipeline (max_length and min_length) according to your preference for summary length.

Notes

    Ensure you have your AssemblyAI API key set up properly.
    Both APIs are used sequentially: first for transcription and then for summarization of the transcribed text.

License

This project is licensed under the MIT License - see the LICENSE file for details.
