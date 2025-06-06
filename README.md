
# 📄 Audio Transcription Using OpenAI Whisper

## 🎯 Description

This project demonstrates how to transcribe audio files into text using [OpenAI's Whisper](https://openai.com/research/whisper), a state-of-the-art speech recognition model. The notebook leverages the `whisper` Python library to process audio files and generate accurate transcriptions, making it useful for various natural language processing tasks such as subtitle generation, voice note analysis, and accessibility applications.

## 📁 Project Structure

```
📦 Audio_Transcription_With_OpenAI_Whisper
 ┣ 📜 Audio_Transcription_With_OpenAI_Whisper.ipynb
 ┗ 📄 README.md
```

## 🚀 Features

- 🔊 Accepts `.mp3`, `.wav`, `.m4a`, and other audio formats
- 🧠 Utilizes OpenAI Whisper for transcription
- 🌐 Supports multilingual transcription (if configured)
- 📃 Outputs raw and formatted transcripts
- 🧪 Easy to test and modify in Jupyter Notebook

## 🛠️ Requirements

Install dependencies with:

```bash
pip install openai-whisper
pip install torch
```

> Make sure you have Python 3.7+ and a working installation of `ffmpeg`.

## 🧪 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/AkagamiShnaks/Audio_Transcription_With_OpenAI_Whisper.git
   cd Audio_Transcription_With_OpenAI_Whisper
   ```

2. Open the notebook:
   ```bash
   jupyter notebook Audio_Transcription_With_OpenAI_Whisper.ipynb
   ```

3. Run the cells step-by-step to load audio, transcribe it, and output the results.

## 🖼️ Example Output

```
Transcribing...
Transcription:
"Welcome to OpenAI Whisper audio transcription demo..."
```

## 📌 Notes

- For GPU acceleration, ensure that `torch` is installed with CUDA support.
- You can change the Whisper model variant (e.g., `base`, `small`, `medium`, `large`) for better speed or accuracy.

## 📜 License

This project is licensed under the MIT License.

