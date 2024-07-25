# Snakery

Snakery is a classic Snake game built using Python Flask for the backend and HTML for the frontend. The game allows you to control a snake to collect food, grow in size, and avoid collisions with walls or itself.

## Features

- Classic Snake gameplay
- Simple and clean user interface
- Score tracking
- Video tutorial included

## Requirements

- Python 3.6 or higher
- Flask
- HTML5-compatible web browser

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/yourusername/snakery.git
    cd snakery
    ```

2. Create a virtual environment and activate it:

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:

    ```sh
    pip install -r requirements.txt
    ```

4. Run the Flask application:

    ```sh
    flask run
    ```

5. Open your web browser and go to `http://127.0.0.1:5000/` to play the game.

## Usage

- Use the arrow keys on your keyboard to control the direction of the snake.
- Try to collect as many food items as possible to grow your snake and increase your score.
- Avoid running into the walls or the snake itself.

## Video Tutorial

Below is a video tutorial to help you get started with Snakery:

```html
<video width="600" controls>
  <source src="snake.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
