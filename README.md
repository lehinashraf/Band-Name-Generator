# Random Adjective-Noun Generator

This is a simple web application built using **Express.js** and **EJS** that generates random adjective-noun combinations. The application displays a dynamically updated current year in the footer.

## Features

- Generates random adjective-noun combinations upon form submission.
- Displays the current year dynamically in the footer.
- Uses **Express.js** for server-side logic and **EJS** for rendering dynamic content.
- Basic form handling with **body-parser** middleware.

## Technologies Used

- Node.js
- Express.js
- EJS (Embedded JavaScript Templating)
- body-parser (middleware)
- HTML/CSS (Bootstrap for styling)

## Getting Started

### Prerequisites

Make sure you have **Node.js** and **npm** installed on your machine.

You can download Node.js [here](https://nodejs.org/).

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/random-adjective-noun-generator.git
    ```

2. Navigate to the project directory:
    ```bash
    cd random-adjective-noun-generator
    ```

3. Install the dependencies:
    ```bash
    npm install
    ```

### Running the Application

1. Start the server:
    ```bash
    node index.js
    ```

2. Open your browser and navigate to:
    ```
    http://localhost:3000
    ```

### File Structure

### Usage

1. Visit the homepage at `http://localhost:3000`.
2. Fill in the form and submit to generate a random adjective-noun combination.
3. The dynamically generated adjective and noun will appear on the page.

### Customization

To modify the adjectives and nouns used in the generator, simply add or remove items from the arrays in `index.js`:

```js
const adj = ["cool", "funny", "amazing", "bright", "charming"];
const noun = ["cat", "dog", "bird", "robot", "fish"];


