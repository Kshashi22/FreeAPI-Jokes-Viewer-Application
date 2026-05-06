
# FreeAPI: Jokes Viewer Application

A simple web application that fetches and displays jokes from a free public API. This project demonstrates API integration, asynchronous programming, and dynamic content rendering using JavaScript.

---

## Features

* Fetch random jokes from a public API
* Display jokes dynamically on the UI
* Support for different joke types (single-line and two-part jokes)
* Generate a new joke on demand
* Responsive and user-friendly interface
* Lightweight and fast performance

---

## Tech Stack

* Frontend: HTML, CSS, JavaScript
* API: Free public jokes API (e.g., JokeAPI)
* Tools: VS Code, Git, Browser DevTools

---

## Project Structure

```
FreeAPI-Jokes-Viewer-Application/
│── index.html
│── style.css
│── script.js
│── README.md
```

---

## Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/FreeAPI-Jokes-Viewer-Application.git
   ```

2. Navigate to the project directory:

   ```bash
   cd FreeAPI-Jokes-Viewer-Application
   ```

3. Open the `index.html` file in your browser

---

## API Integration

Example API used:

```
https://v2.jokeapi.dev/joke/Any
```

### Fetch Example

```javascript
fetch('https://v2.jokeapi.dev/joke/Any')
  .then(response => response.json())
  .then(data => console.log(data));
```

---

## How It Works

1. The application sends a request to the jokes API
2. The API returns joke data in JSON format
3. The application checks the joke type (single or two-part)
4. The joke is displayed dynamically on the webpage

---

## Joke Types Supported

* Single: A one-line joke
* Two-part: Setup and delivery format

---

## Future Improvements

* Add category-based joke filtering
* Include a favorites or save feature
* Add sharing functionality
* Improve UI/UX with animations
* Add dark mode support

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Submit a pull request

---

## Acknowledgements

* Public jokes APIs for providing free data
* Open-source community for inspiration and tools

