# JARVIS AI Assistant

*I'm a huge Iron Man nerd, and I'm in the process of learning Python. I was told the best way to learn Python is by creating personal projects, so that's what I've done over the last few weeks. My version of JARVIS is an AI assistant designed to help with a variety of tasks, from handling voice commands to managing media and providing weather updates. This project showcases a desktop application developed using Python and integrates various functionalities to create a seamless user experience.*

## 🚀 Features

- **Voice Command Recognition**: The program communicates and recieves input exclusively through verbal communication.
- **Audio Management**: Control Spotify playback, shuffle playlists.
- **Weather Updates**: Get real-time weather information for the Baltimore area. (I am a student at Johns Hopkins).
- **Customizable Interface**: Simple, functional, and tailored to your needs.

## 🛠 Installation

### Prerequisites

- **Python 3.12** or higher
- **PyInstaller** for creating the executable
- **tkinter** for the GUI
- **speech_recognition** for voice commands
- **spotipy** for Spotify integration
- **requests** for API requests

### Setup

1. **Clone the Repository**

    ```bash
    git clone https://github.com/your-username/JARVIS-AI-Assistant-Free.git
    cd JARVIS-AI-Assistant-Free
    ```

2. **Install Dependencies**

    Create a virtual environment (optional but recommended) and install the required packages:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

3. **Run the Application**

    For testing, you can run the Python script directly:

    ```bash
    python TTJarv.py
    ```

    To create an executable file for your desktop, use PyInstaller:

    ```bash
    pyinstaller --onefile --windowed --icon=path/to/icon.icns TTJarv.py
    ```

    The executable will be located in the `dist` directory.

## 🎤 Usage

- **Play around!**: There are several easter eggs hidden for friends and family, but use words that you'd use in normal conversations with people. This chatbot was designed to be friendly to speak to, like the real JARVIS was!

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📬 Contact

For any inquiries or support, please contact:

- **Email**: ababu5@jh.edu
