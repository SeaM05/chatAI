# ChatAI

ChatAI is a voice-enabled chat application that uses OpenAI's GPT-3 for conversational AI. Users can interact with the AI by speaking into their microphone or by typing their queries.

## Features

- Voice input: Speak to the AI using your microphone.
- Text input: Type your queries to the AI.
- Conversational AI: Powered by OpenAI's GPT-3.
- Interactive GUI: User-friendly interface built with CustomTkinter.
- Light and Dark Modes: Choose your preferred theme.

## Technologies Used

- Python
- SpeechRecognition
- OpenAI API
- pyttsx3
- CustomTkinter
- Pillow

## Setup

1. **Clone the repository:**
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```
2. **Create a virtual environment and activate it:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   *(Note: You'll need to create a `requirements.txt` file if one doesn't exist yet. It should include libraries like `speechrecognition`, `openai`, `pyttsx3`, `customtkinter`, `Pillow`, `python-dotenv`)*
4. **Set up environment variables:**
   - Create a `.env` file in the root directory.
   - Add your OpenAI API key to the `.env` file:
     ```
     GPT=your_openai_api_key
     ```
5. **Run the application:**
   ```bash
   python main.py
   ```

## How to Use

1. Launch the application.
2. Click the microphone button to speak your query, or type your query into the text box and press Enter.
3. The AI's response will be displayed and spoken aloud.
4. Use the reset button to clear the conversation history.
5. Change the theme (Dark/Light) using the dropdown menu.
6. Click the info button for a brief description of the application.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug fixes, please open an issue or submit a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
