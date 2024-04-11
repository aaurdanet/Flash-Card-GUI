Flash Cards

This Python script creates a simple flashcard application using Tkinter for the graphical interface and Pandas for data handling. The application helps users learn vocabulary by presenting French words and prompting them to recall the corresponding English translations.

Features:

Flashcard Presentation: Displays a French word on the front of the flashcard and its English translation on the back.
Random Selection: Randomly selects a word from the dataset to present to the user.
Learning Progress: Allows users to mark words as known or unknown, updating the dataset accordingly.
Persistence: Saves the progress of learning words to a CSV file to ensure continuity across sessions.

Usage:

Run the Script: Execute the script using Python.
Flashcard Display: The application will display a French word on the front of the flashcard.
Recall Translation: Try to recall the English translation of the word.
Feedback: Click the "Right" button if you know the translation or the "Wrong" button if you don't.
Progression: The application will show the English translation and proceed to the next word automatically after a few seconds.
Learning Continuity: The script saves the words that need further learning to a CSV file, ensuring continuity across sessions.

Requirements:

Python 3.x
Tkinter
Pandas

Notes:

Dataset: The script assumes a CSV file containing French words and their English translations. Additional CSV files can be added to learn other topics.
Image Files: The application uses image files for the flashcard graphics and buttons. Make sure the image paths are correctly specified.
Learning Progress: Users can track their learning progress by observing the words presented and marking them as known or unknown.

This script provides a simple yet effective tool for learning vocabulary through interactive flashcards within a graphical interface.
