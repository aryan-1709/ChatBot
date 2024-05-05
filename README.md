# MNNIT Chatbot

## Overview

This project is a chatbot designed to provide information about Motilal Nehru National Institute of Technology (MNNIT). The chatbot is capable of answering questions related to various general topics about MNNIT, such as the name of buildings, weather, time, date, hobbies, and music related to MNNIT.

The project consists of several files:

- `intents.json`: This file contains general topics about MNNIT, including information on buildings, weather, time, date, hobbies, and music. Each topic has associated intents and responses that the chatbot can use to answer user queries.

- `updated_model.ipynb`: This Jupyter Notebook contains code to train our chatbot using the data from `intents.json`. It utilizes natural language processing techniques to understand user queries and generate appropriate responses.

- `chat.ipynb`: This Jupyter Notebook serves as the user interface for interacting with our chatbot. It allows users to input their questions and receive responses from the chatbot based on the trained model.

## Usage

To use the MNNIT Chatbot:

1. Ensure you have Python installed on your system along with necessary libraries such as TensorFlow, NLTK, etc.

2. Open `updated_model.ipynb` and execute the code cells to train the chatbot model using the data from `intents.json`.

3. Once the model is trained, open `chat.ipynb` and run the cells to start the chatbot interface.

4. Interact with the chatbot by typing your questions or queries into the provided input field. The chatbot will process your query and respond accordingly based on the information available in `intents.json`.

## Files

- `intents.json`: Contains general topics about MNNIT along with associated intents and responses for the chatbot.
- `updated_model.ipynb`: Jupyter Notebook containing code to train the chatbot model.
- `chat.ipynb`: Jupyter Notebook providing a user interface to interact with the chatbot.

## Contributing

Contributions to this project are welcome! If you'd like to contribute, feel free to fork this repository, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to reach out if you have any questions or need further assistance!
