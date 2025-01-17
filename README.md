# Gesture Palette

Gesture Palette is an interactive application that utilizes computer vision techniques to enable gesture-based painting. This project combines Python, OpenCV, and web technologies to create an engaging user experience for artistic expression through gestures.

## Features

- **Gesture-Based Painting**: Use hand gestures to draw and interact with the canvas.
- **Customizable Colors and Brushes**: Select different colors and brush sizes.
- **Web Interface**: The project includes a web application for interacting with the tool.
- **Database Integration**: A SQL database is included for storing user data or configurations.
- **Pre-built Modules**: The project includes modular Python scripts for various functionalities.

## Project Structure

- `app.py`: Main entry point for the web application.
- `Gesture_Palette_Code.py`: Core logic for gesture recognition and processing.
- `Virtual_Painter.py`: Standalone script for gesture-based painting.
- `MINIPROJECT.sql`: SQL script for setting up the database.
- `requirements.txt`: Python dependencies.
- `static/`: Contains static files such as images, stylesheets, and JavaScript.
- `templates/`: Contains HTML templates for the web application.

## Prerequisites

To run this project, you need:

- Python 3.8+
- OpenCV
- Flask
- A web browser

You can install the required Python libraries using:
```bash
pip install -r requirements.txt
```

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/gesture-palette.git
   cd gesture-palette
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up the database:
   - Run the SQL script `MINIPROJECT.sql` in your preferred database management tool.

4. Start the web application:
   ```bash
   python app.py
   ```
   The application will be available at `http://127.0.0.1:5000/`.

5. Optionally, run the virtual painter:
   ```bash
   python Virtual_Painter.py
   ```

## Usage

- Launch the web interface and start interacting with the gesture-based tools.
- Use the standalone `Virtual_Painter.py` script for offline painting directly using gestures.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- OpenCV for the powerful computer vision library.
- Flask for the lightweight and flexible web framework.
- Python community for the extensive resources and libraries.

