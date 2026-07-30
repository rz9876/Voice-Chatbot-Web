# 🎙️ Voice-Chatbot-Web

A web-based voice chatbot that allows users to speak through the microphone, communicate with Google Gemini, and hear the response aloud.

---

## 🌐 Visit the Website

[🎤 Visit using InfinityFree](https://my-little-universe.page.gd/voicebot/)

> ⚠️ Please open the website using **Google Chrome** and allow microphone access.

[🟥 I added a file called "ملاحظات تفصيلية لنفسي (مشروع3)" where I wrote personal notes for myself in colloquial Arabic, in case you would like to read it.](ملاحظات%20تفصيلية%20لنفسي%20%28مشروع3%29.pdf)

---

## 🎥 Result Video

[▶️ Watch the Voice Chatbot Demonstration](video.mp4)

The video shows the final result when I spoke to the chatbot and received a spoken response.

---

## 💫 About the Project

**Voice Chatbot Web** is an interactive webpage that converts the user's voice into text, sends it to Google Gemini through PHP, displays the response, and reads it aloud.

The provided project files contained several errors that needed to be found and corrected before uploading the website to InfinityFree.

---

## 🐞 Errors Fixed

1. Renamed `chat.php` to `gemini.php` because the word `chat` caused a 403 Forbidden error on InfinityFree.

2. Corrected the PHP file path in `app.js`:

```javascript
const BACKEND_URL = "gemini.php";
```

3. Corrected the `config.php` path inside `gemini.php`:

```php
require __DIR__ . '/config.php';
```

4. Added the Gemini API key to the server version of `config.php`.

5. Updated the outdated Gemini model to a working model.

---

## 🔄 How It Works

`Microphone` → `Speech Recognition` → `app.js` → `gemini.php` → `Google Gemini API` → Displayed and Spoken Response

---

## 🛠️ Technologies Used

- HTML
- CSS
- JavaScript
- Fetch API
- PHP
- Google Gemini API
- Web Speech API
- InfinityFree

No external framework was used.

---

## 🔐 Security Note

The real Gemini API key is not included in the public GitHub repository.
