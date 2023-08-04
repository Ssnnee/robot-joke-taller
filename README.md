# robot-joke-taller
A robot voice that tells a programming jokes
# Joke Taler Project README

**Robot Joke Taler** is a simple web application that tells programming-related jokes using both text and audio. It fetches jokes from an external API and provides an option to hear the jokes being narrated by a synthetic voice. This project combines web development with the VoiceRSS API to create a fun and interactive experience for users.

## Features
- Fetches programming-related jokes from an external API.
- Utilizes the VoiceRSS API to convert jokes into synthesized speech.
- Allows users to click a button to get a new joke.
- Provides a "Repeat" button to hear the joke again.
- Disables the button while the joke is being played to prevent interruptions.

## Setup
To set up the project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/your-username/joke-taler.git
```

2. Navigate to the project directory:

```bash
cd joke-taler
```

3. Obtain a VoiceRSS API key by signing up at [VoiceRSS](https://www.voicerss.org/).

4. Create a `config.js` file in the project directory and add your API key:

```javascript
// config.js
const config = {
    apiKey: 'YOUR_API_KEY'
};

export default config;
```

5. Open `index.html` in your web browser to use the Joke Taler application.

## Usage
1. Load the Joke Taler application by opening the `index.html` file.
2. Click the "Tell Me A Joke" button to fetch and hear a programming-related joke.
3. To hear the joke again, click the "Repeat" button.

## Technologies Used
- HTML
- CSS
- JavaScript
- JokeAPI (for fetching jokes)
- VoiceRSS API (for text-to-speech conversion)

## Contributing
Contributions to the Joke Taler project are welcome! If you find any issues or want to enhance the application, feel free to submit a pull request.

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Open a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

---

Enjoy the Joke Taler application and have fun sharing programming humor!
