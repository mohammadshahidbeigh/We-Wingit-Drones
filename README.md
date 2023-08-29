# We-Wingit Drones

![Screenshot_20230827_142859](https://github.com/mohammadshahidbeigh/We-Wingit-Drones/assets/85876937/911a4a31-2951-40b7-bc25-28a3412c7858)



"We-Wingit Drones is a web-based conversational AI chatbot 🤖 that leverages OpenAI's davinci model. It allows users to engage in interactive conversations by inputting messages, and the chatbot responds with contextually relevant replies. The chatbot's responses are generated in real-time, creating a dynamic and engaging user experience. This chatbot has been fine-tuned using custom data, enabling it to provide personalized and domain-specific interactions, making it a versatile tool for various applications."

## Prerequisites for Fine-Tunning with OpenAi

- Node.js and npm installed on your machine
- OpenAI API key
- Refer to ```terminal-commands.md``` for fine tunning
- Fine tunning dataset example ```we-wingit-data_prepared.jsonl```

## Getting Started

1. Clone this repository to your local machine.
2. Install the required dependencies using the following command:
3. Create a `.env` file in the root directory and add your OpenAI API key: ` `
4. Replace `davinci:ft-2023` with the desired OpenAI model ID in the code.

## Usage

1. Open the `index.html` file in a web browser.
2. Enter your message in the input field and submit.
3. The chatbot will generate a response based on your input using the OpenAI API.

## Code Explanation

- The application uses the OpenAI JavaScript SDK to interact with the OpenAI API.
- User input is captured from the input field and used to create a conversation prompt.
- The OpenAI API is called to generate a response based on the conversation prompt.
- The response is displayed in a typewriter-like animation.

## Customization

Feel free to modify the code to suit your needs. You can change the conversation behavior, and styling, or add more features as desired.


Quick start:

```
$ npm install
$ npm start
```

Head over to https://vitejs.dev/ to learn more about using vite

Happy Coding!
