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
> ⚠️ I spoke to the chatbot during the demonstration, but my voice was muted in the video.

The video shows the final result when I spoke to the chatbot and received a spoken response.

---

## 💫 About the Project

**Voice Chatbot Web** is an interactive webpage that converts the user's voice into text, sends it to Google Gemini through PHP, displays the response, and reads it aloud.

The provided project files contained several errors that needed to be found and corrected before uploading the website to InfinityFree.

---

## 🐞 Errors Fixed

1. Renamed `chat.php` to `gemini.php` because the word `chat` caused an error on InfinityFree.

2. Corrected the `chat.php` path in `app.js` from `const BACKEND_URL = "api/chat.php";` to `const BACKEND_URL = "gemini.php";` because there is no `api` folder, all the files are in the same folder, and `chat.php` was renamed to `gemini.php`.

3. Corrected the `config.php` path in `gemini.php` from `require __DIR__ . '/../config.php';` to `require __DIR__ . '/config.php';` because `../` refers to the parent folder, while `config.php` and `gemini.php` are located in the same folder.

4. Added the Gemini API key to the server version of the `config.php` file.

5. Updated the Gemini model from the outdated model `gemini-2.0-flash` to a working model `gemini-3.6-flash`.

---

## 🛠️ Technologies Used

- HTML
- CSS
- JavaScript
- Fetch API
- PHP
- Google Gemini API
- InfinityFree

No external framework was used.

