# FlashFocus: Reading and Vocabulary Support for Dyslexic Individuals

FlashFocus is a web-based application designed to assist dyslexic individuals in strengthening their reading and vocabulary skills. With an engaging and customizable experience, FlashFocus enables users to build essential language skills through tailored flashcards, phonetic hints, and reading exercises. FlashFocus has been successfully tested among dyslexic students, helping users improve word recognition and comprehension, which are valuable skills for both academic and daily life.

## Features
- **Customizable Flashcards**: Offers flexible word and sentence displays to enhance readability and focus.
- **Word Database for Reading Practice**: Provides a curated set of challenging vocabulary words, supporting improved recognition and comprehension.
- **Phonetic Hints and Definitions**: Integrated phonetic hints and easy-to-understand definitions that support users in decoding and understanding difficult words.
- **Standardized Test Preparation**: Vocabulary relevant for standardized tests like the SAT, aiding users in their exam preparation.
- **User-Friendly Interface**: Accessible design that adapts to both desktop and mobile screens, allowing users to practice reading anywhere.

## Built With
- **Flask**: A lightweight Python framework used to handle backend functionality efficiently.
- **Flutter & Dart**: For a responsive, cross-platform user experience.
- **HTML/CSS**: Building the interface for readability and accessibility.
- **JavaScript**: To manage dynamic interactions for the exercises.

## Getting Started

### Prerequisites
- Python 3.6 or higher
- Flask
- Web Browser (Chrome, Firefox, Safari)

### Demo
Check out our [demo video](https://linktodemo) that highlights FlashFocus’s unique features and its impact on reading development.

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/flashfocus.git
   cd flashfocus
Create a Virtual Environment (recommended):

bash
Copy code
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install Dependencies:

bash
Copy code
pip install -r requirements.txt
Run the App:

bash
Copy code
flask run
Access the App: Open your browser and navigate to http://127.0.0.1:5000/.

Usage
Start the app by running flask run in your terminal.
Upon loading the app, you’ll be presented with reading exercises, including flashcards and definitions tailored to dyslexic individuals.
Use customizable features to adjust the word display, making it easier to focus on specific words and phrases.
Track progress with interactive feedback, helping you improve comprehension and retention.
File Structure
flashfocus/ │ ├── static/ │ ├── css/ │ │ └── flashfocus.css # Styling for the app │ ├── templates/ │ ├── main.html # Main interface for the reading exercises │ ├── word_database.txt # Database of words for reading practice ├── app.py # Main Flask application ├── requirements.txt # List of Python dependencies └── README.md # This file

How It Works
Word Selection: The app selects words from a custom word database.
Customization: Users can tailor the flashcard display settings for optimal readability.
Phonetic Hints and Definitions: Hints and definitions are provided to enhance word recognition and understanding.
Progress Tracking: Users receive real-time feedback to monitor improvements.
Difficulty Levels: Words range from beginner to advanced, supporting users of different reading levels.
Contributing
We welcome contributions to FlashFocus! Please feel free to open an issue or submit a pull request with any suggestions or enhancements.

