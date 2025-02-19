# Voice-Assistant-Friday
# Friday AI Assistant

Friday is an advanced AI-powered voice assistant capable of performing various tasks such as web searching, providing real-time weather updates, delivering the latest news, sending emails, messaging via WhatsApp, integrating AI capabilities, and much more.

## Features
- **Voice Commands**: Control Friday using voice commands for a hands-free experience.
- **Web Searching**: Search the web for any query.
- **Real-time Weather Updates**: Get current weather conditions.
- **News Updates**: Retrieve the latest news headlines.
- **YouTube & Google Search**: Search for content on YouTube and Google.
- **Wikipedia Integration**: Get summarized information from Wikipedia.
- **Email Sending**: Send emails directly through voice commands.
- **Music Playback**: Play songs directly on YouTube.
- **Mathematical Calculations**: Perform mathematical calculations.
- **Translation**: Translate phrases into different languages.
- **Taking Notes**: Save important notes for later.
- **AI Chatbot**: Ask general questions, get coding help, and more.
- **Personalized Messages**: Leave messages for Muneeb Ali, the creator of Friday.
- **WhatsApp Messaging**: Send WhatsApp messages using voice commands.
- **System Control**: Open applications, control volume, and perform system tasks.

## Requirements
- Python 3.7+
- The following Python libraries:
  ```bash
  pip install os random smtplib pyttsx3 requests wikipedia webbrowser sympy speechrecognition googletrans beautifulsoup4 openai pywhatkit pyaudio
  ```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/friday-ai-assistant.git
   ```
2. Navigate to the project folder:
   ```bash
   cd friday-ai-assistant
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the assistant:
   ```bash
   python main.py
   ```

## Usage
- Say "Friday" to wake the assistant.
- Use voice commands for various functions such as:
  - "Open YouTube"
  - "Search for Python tutorials on Google"
  - "What is the weather in Lahore?"
  - "Tell me a joke"
  - "Send an email"
  - "Translate 'hello' to French"
  - "Play a song on YouTube"
  - "Get the latest news"
  - "Solve 5 + 3 * 2"
  - "Take a note"
  - "Who created you?"
  - "Send a WhatsApp message"
  - "Increase the volume"
  - "Open Notepad"
- Say "Exit" to close the assistant.

## Configuration
- Modify `music_dict` to add preferred songs.
- Update `jokes_list` with new jokes.
- Configure email credentials in `send_email` function.
- Set up WhatsApp messaging in `pywhatkit` with proper login.

## Security Notice
- Ensure API keys are kept secure.
- Do not share personal email credentials in public repositories.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss the proposed changes.

## Creator
- **Muneeb Ali**
  - Email: muneeb00ali@gmail.com
  - Phone: 0321-9697820

---

Enjoy using **Friday AI Assistant**!
