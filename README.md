 Cybersecurity Awareness Bot

Description
A C# console-based chatbot called MAX that helps users learn about cybersecurity topics. The bot plays a voice greeting when the application launches, displays an ASCII art header, asks the user for their name, and then responds to cybersecurity-related questions.

---

Project Structure

| File | Description |
|------|-------------|
| `Program.cs` | Main entry point. Creates instances of all classes and runs the app |
| `Display.cs` | Handles audio playback and ASCII art display |
| `Greeting.cs` | Asks for the user's name and validates the input |
| `Chatbot.cs` | Contains the keyword-response system for cybersecurity topics |

---

Features

- **Voice Greeting** — plays a WAV audio file when the app starts
- **ASCII Art Header** — displays a cybersecurity themed logo on launch
- **Name Input with Validation** — accepts only letters, minimum 3 characters
- **Time-Based Greeting** — greets the user with good morning, afternoon or evening
- **Chatbot Response System** — responds to cybersecurity questions using keyword matching
- **Input Validation** — handles empty or unrecognised inputs with a helpful message
- **Coloured Console UI** — uses different colours for the bot, user and errors

---

 Topics the Bot Can Answer

- How are you
- Purpose
- What can I ask
- Password safety
- Phishing
- Safe browsing

---

 How to Run

1. Open the project in Visual Studio
2. Make sure `Voice_Greeting.wav` is placed in the project root folder
3. Set the WAV file property to **Copy to Output Directory**
4. Press **F5** or click **Start** to run

---

 Requirements

- Visual Studio 2019 or later
- .NET Framework 4.7.2 or later
- A `Voice_Greeting.wav` file in the project root folder

---

 CI Workflow

This project uses GitHub Actions for Continuous Integration. The workflow checks that the project builds successfully on every push and pull request.

 CI Workflow File location
`.github/workflows/build.yml`

 CI Status
![CI Build](https://github.com/YOUR_USERNAME/CybersecurityAwarenessBot/actions/workflows/build.yml/badge.svg)

> Replace `YOUR_USERNAME` with your actual GitHub username.

---

 Author
Developed as Part 1 of the Programming assignment — Basic Chatbot Interaction with Voice Greeting and Image Display.