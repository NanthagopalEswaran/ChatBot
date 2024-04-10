# ChatBot

Welcome to the ChatBot!

## About

This project is a simple ChatBot built using **Chainlit**, a Python library for quickly building chat applications. Chainlit provides a wide range of features that make it easy to develop interactive and engaging chatbots.

## Features

- **Easy to use**: Similar interface to ChatGPT.
- **Customizable**: You can easily customize the behavior and responses of your ChatBot to suit your specific requirements.
  - **Models**: Choose models that you want (Only OpenAI models are supported for now)
  - **Temperature**: Alter the temperature as per your need and continue the conversation
  - **Stream Answers**: Control streaming of answers.
  - **Chat Window Size**: Control no of chat that you want to use for further communications. This helps staying within the context window of the model
- **Microphone Support**: ChatBot can use your microphone instead of keyboards for chats. (Permission Required)
- **Multiple Chats**: Multiple Chats in single window is disabled for now since it required to store chats in chainlit account for data persistent. Quick Work Around is to open the chatbot in new tabs.

## Getting Started

To get started with the ChatBot, follow these steps:

1. Clone the repository: `git clone https://github.com/NanthagopalEswaran/ChatBot.git`
2. Install the required dependencies: `poetry install`
3. Run the ChatBot application: `poetry run chainlit run app.py`. This will automatically open the chatbot in your default browser. 
   
    > Default url - [http://localhost:8000/](http://localhost:8000/)

## Usage

1. You will be prompted for `OpenAI API Key` for the first time. To use this ChatBot, the above API key is required. The key is stored on your device's local storage.
2. Select a persona of your choice.
   1. `Factful` - AI will try to stick to facts while giving answers instead of creating an answer on its own.
        > Note: LLMs are not reliable yet. so do not trust the answers from LLM blindly. This option is to instruct LLM to use facts but does not gurentee.
    2. `Creative` - AI will try to generate new ideas and be creative as much as possible in its replies.
    3. `Normal` - Some conversations does not need to stick to facts or more creative answers. (Default)
 3. Open Chat Settings and configure settings as per your need. For more information on each settings. refer Feature section above.
 4. You can use history and microphone features as and when needed.

<p align="center"><strong><em>Happy chatting!</em></strong></p>

## Contributing

We welcome contributions from the community! 

This ChatBot is an example for ChatBots build using Chainlit, Langchain and OpenAI.

If you have any ideas, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contact

If you have any questions or need further assistance, feel free to contact us at nanthagopaleswaran@gmail.com.