# Text-to-Speech Web App Using Flask and gTTS

This repository contains a simple **Text-to-Speech (TTS)** web application built using Python, Flask, and the **Google Text-to-Speech (gTTS)** library. The app supports converting input text into speech in multiple accents, including:

- British  
- Indian  
- Canadian  
- South African  
- Australian  
- Spanish  
- Irish  

## Features  
- **User-Friendly Interface**: Simple web interface for entering text and selecting the desired accent.  
- **Multiple Accents**: Generate speech in seven different accents.  
- **Downloadable Audio**: Option to download the generated speech as an MP3 file.  
- **Fast and Lightweight**: Powered by Flask and gTTS for quick TTS generation.  

---

## Table of Contents  
- [Installation](#installation)  
- [Usage](#usage)  
- [Supported Accents](#supported-accents)  
- [Example](#example)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Installation  

1. **Clone the Repository**  
   ```bash  
   git clone https://github.com/your-username/text-to-speech-flask.git  
   cd text-to-speech-flask  
   ```  

2. **Set Up the Virtual Environment**  
   ```bash  
   python3 -m venv venv  
   source venv/bin/activate  # For Linux/Mac  
   venv\Scripts\activate     # For Windows  
   ```  

3. **Install Dependencies**  
   ```bash  
   pip install -r requirements.txt  
   ```  

4. **Run the Application**  
   ```bash  
   python app.py  
   ```  

5. Open the app in your browser at `http://127.0.0.1:5000/`.  

---

## Usage  

1. Enter your desired text in the text box.  
2. Select an accent from the dropdown menu.  
3. Click the **Convert** button to generate the speech.  
4. Play the audio directly on the page or download it as an MP3 file.  

---

## Supported Accents  

Below is the mapping of accents with their respective `gTTS` language and regional settings:

| Accent         | Language Code | Example Region |  
|----------------|---------------|----------------|  
| British        | `en`         | UK             |  
| Indian         | `en`         | IN             |  
| Canadian       | `en`         | CA             |  
| South African  | `en`         | ZA             |  
| Australian     | `en`         | AU             |  
| Spanish        | `es`         | ES             |  
| Irish          | `en`         | IE             |  

---

## Example  

1. Enter text:  
   **"Hello, welcome to our text-to-speech app!"**  
   
2. Choose accent:  
   **British**  

3. Output:  
   The app generates a British-accented MP3 file, which you can play or download.  

---

## Project Structure  

```
text-to-speech-flask/  
│  
├── app.py                     # Main Flask application  
├── templates/  
│   └── index.html             # Webpage template  
├── static/  
│   ├── styles.css             # Optional CSS for styling  
│   └── generated_audio/       # Folder for saving audio files  
├── requirements.txt           # Project dependencies  
└── README.md                  # Project documentation  
```  

---

## Contributing  

Contributions are welcome! To contribute:  

1. Fork the repository.  
2. Create a new branch for your feature:  
   ```bash  
   git checkout -b feature-name  
   ```  
3. Commit your changes and push them to the branch:  
   ```bash  
   git commit -m "Add feature"  
   git push origin feature-name  
   ```  
4. Submit a pull request.  

---

## License  

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.  

---

## Acknowledgments  

- [Flask Documentation](https://flask.palletsprojects.com/)  
- [gTTS Documentation](https://gtts.readthedocs.io/)  

Happy coding! 😊  