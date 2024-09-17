# RailVoice
RailVoice operates through user voice input, utilizing voice commands to deliver the necessary information audibly. Recognizing that voice communication is highly effective, this system employs a microphone to capture user speech, which is then converted into text using Google's speech-to-text converter. Developed in Python, the system leverages an SQLite database to store the information required to respond to user inquiries. The speech control mechanism processes the text and provides appropriate responses in voice form, ensuring seamless and intuitive interactions.


Developing a voice-activated train inquiry system using Google Speech Recognition, SQLite, and Python's Tkinter library for the user interface.

Overview
Import the necessary Python packages.
Prepare the railway database (a sample train.db file is provided).
On first execution, create a user profile for database administration (this step is unnecessary if using the provided train.db).


Prerequisites
Basic programming experience in Python.
Fundamental understanding of database CRUD (Create, Read, Update, Delete) operations.
Basic knowledge of Tkinter UI functions.


Execution Steps
Run the FRONT.py module using any IDE.
Access the Administration tab to open the database monitoring window, where you can modify record entries.
Use the "Give command in Speech" tab to activate the speech recognition module. Speak your enquiry about any train listed in the database.
Ensure your speech includes keywords such as "from", "to", <source_name>, <destination_name>, and <date>.

