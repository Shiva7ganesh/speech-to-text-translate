# Whisper GPT Translator 🌍🎙️

An AI-powered web app that transcribes audio using OpenAI's Whisper model and translates the transcript into any language using GPT-3.5/4.

## 🔥 Features

- 🎧 Upload audio (e.g., `.mp3`)
- ✍️ Transcribe audio using OpenAI Whisper
- 🌐 Translate transcript into any language using GPT
- 🖥️ Simple web interface built with Flask & Bootstrap

---

## 📸 Screenshots

### 🖼️ Upload Page
<img width="3199" height="1692" alt="Screenshot 2025-07-19 190806" src="https://github.com/user-attachments/assets/68f59aa8-6b7a-4c9a-a8fa-4e72e2269773" />


### 🌐 Translation Output
![WhatsApp Image 2025-07-19 at 19 41 56_95ab8f47](https://github.com/user-attachments/assets/20a99417-bcce-4c0f-a893-3bc671b444b6)


---

## 🛠️ Tech Stack

- **Python**
- **Flask**
- **OpenAI Whisper**
- **OpenAI GPT-3.5 / GPT-4**
- **HTML/CSS (Bootstrap)**
- **dotenv** for managing API keys

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Shiva7ganesh/whisper-gpt-translator.git
cd whisper-gpt-translator
````

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Add your OpenAI API key

Create a `.env` file in the root directory:

```
OPENAI_API_KEY=your_openai_api_key_here
```

### 4. Run the app

```bash
python app.py
```

Visit [http://localhost:8080](http://localhost:8080) to use the app.

---

## 📂 Project Structure

```
.
├── app.py               # Main Flask application
├── requirements.txt     # Python dependencies
├── .env                 # API key (not committed)
├── static/              # Uploaded audio files
├── templates/
│   └── index.html       # Frontend UI
```

## 📌 Example Use Case

1. Upload a `.mp3` file.
2. Enter a target language (e.g., `French`, `Hindi`, `Bengali`).
3. Submit and receive translated text instantly.

---

## 🌱 Future Enhancements

* 🔁 Add TTS (text-to-speech) for translated output
* 🎛️ Language dropdown with ISO codes
* 🌐 Deploy on Render/Streamlit/Hugging Face Spaces
