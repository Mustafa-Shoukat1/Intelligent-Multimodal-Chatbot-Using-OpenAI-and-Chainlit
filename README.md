# Intelligent-Multimodal-Chatbot-Using-OpenAI-and-Chainlit

## Welcome Screen

![Screenshot 2024-08-02 223128](https://github.com/user-attachments/assets/134cc4a0-f699-4952-92bc-03e761597f34)

Welcome to the **Multimodal Chatbot** project! This project showcases a chatbot capable of handling various types of inputs, including text, images, and audio. By leveraging OpenAI's models and Chainlit, this chatbot provides a versatile and intelligent conversational experience.


# Chatbot's responses
![Screenshot 2024-08-02 213410](https://github.com/user-attachments/assets/20d42a32-07b1-4112-af86-bd71a6cc063d)

# Process while working on the VS code 

![Screenshot 2024-08-02 213253](https://github.com/user-attachments/assets/66dfa3d9-7849-44e3-90c2-2efb8fb68dfd)


## Features

- **Text Input**: Handle and process user queries in text format.
- **Image Input**: Convert images to base64 and process them in chat responses.
- **Audio Input**: Transcribe audio files into text and integrate them into the chatbot's responses.
- **Integration**: Uses OpenAI's GPT-4o model for generating responses and Whisper-1 for audio transcription.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Mustafa-Shoukat1/Intelligent-Multimodal-Chatbot-Using-OpenAI-and-Chainlit.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Intelligent-Multimodal-Chatbot-Using-OpenAI-and-Chainlit
    ```

3. Install the required dependencies:

    ```bash
    pip install openai chainlit
    ```

4. Set your OpenAI API key in the environment variable:

    ```bash
    export OPENAI_API_KEY='your_openai_api_key'
    ```

## Usage

1. Ensure you have the required environment variable set:

    ```bash
    export OPENAI_API_KEY='your_openai_api_key'
    ```

2. Run the chatbot server:

    ```bash
    chainlit run app.py
    ```

3. Interact with the chatbot through the Chainlit interface. You can send text, images, or audio files and receive intelligent responses.

## Code Description

- **append_messages**: Prepares messages based on input types (text, image, audio) and sends them to the OpenAI API for completion.
- **image2base64**: Converts an image file to a base64 encoded string.
- **audio_process**: Transcribes audio files to text using the Whisper-1 model.
- **chat**: Handles incoming messages and processes text, images, or audio accordingly.

   <h2 style="color: red; margin-top: 15px; font-size: 28px;">Contact Information</h2>
        <table style="width: 100%; margin-top: 15px; border-collapse: collapse;">
            <tr style="background-color: #64B5F6; color: #ffffff;">
                <th style="padding: 8px; border-bottom: 2px solid #000000;">Name</th>
                <th style="padding: 8px; border-bottom: 2px solid #000000;">Email</th>
                <th style="padding: 8px; border-bottom: 2px solid #000000;">LinkedIn</th>
                <th style="padding: 8px; border-bottom: 2px solid #000000;">GitHub</th>
                <th style="padding: 8px; border-bottom: 2px solid #000000;">Kaggle</th>
            </tr>
            <tr style="background-color: #FFFFFF; color: #000000;">
                <td style="padding: 8px;">Mustafa Shoukat</td>
                <td style="padding: 8px;">mustafashoukat.ai@gmail.com</td>
                <td style="padding: 8px;">
                    <a href="https://www.linkedin.com/in/mustafashoukat/" target="_blank">
                        <img src="https://img.shields.io/badge/LinkedIn-0e76a8.svg?style=for-the-badge&logo=LinkedIn&logoColor=white" alt="LinkedIn Badge" style="border-radius: 5px; width: 100px;">
                    </a>
                </td>
                <td style="padding: 8px;">
                    <a href="https://github.com/Mustafa-Shoukat1" target="_blank">
                        <img src="https://img.shields.io/badge/GitHub-171515.svg?style=for-the-badge&logo=GitHub&logoColor=white" alt="GitHub Badge" style="border-radius: 5px; width: 100px;">
                    </a>
                </td>
                <td style="padding: 8px;">
                    <a href="https://www.kaggle.com/mustafashoukat" target="_blank">
                        <img src="https://img.shields.io/badge/Kaggle-20beff.svg?style=for-the-badge&logo=Kaggle&logoColor=white" alt="Kaggle Badge" style="border-radius: 5px; width: 100px;">
                    </a>
                </td>
            </tr>
        </table>
    </div>
</div>

