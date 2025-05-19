# Emotion Recognition Web Application

This project combines a Flask web application with real-time emotion detection capabilities using computer vision and machine learning. The application can detect emotions from webcam feed and visualize them in real-time.

## Features

- Real-time emotion detection from webcam feed
- Live emotion visualization with bar charts
- Video recording with emotion annotations
- GIF generation of emotion charts
- Cumulative emotion statistics tracking
- Web interface for easy access

## Project Structure

```
├── app.py              # Flask web application
├── emopy.py           # Emotion detection and visualization script
├── requirements.txt   # Python dependencies
├── static/           # Static files
│   └── favicon.ico   # Website favicon
└── artefacts/        # Generated output files
```

## Prerequisites

- Python 3.8 or higher
- Webcam
- Virtual environment (recommended)

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd <repository-name>
```

2. Create and activate a virtual environment:
```bash
python -m venv .venv
# On Windows
.venv\Scripts\activate
# On Unix or MacOS
source .venv/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

### Running the Web Application

Start the Flask web server:
```bash
python app.py
```
The application will be available at `http://localhost:5000`

### Running Emotion Detection

Run the emotion detection script:
```bash
python emopy.py
```

The script will:
- Open your webcam
- Detect emotions in real-time
- Display a live bar chart of emotions
- Save the video feed with emotion annotations
- Generate a GIF of the emotion chart
- Create a cumulative emotion statistics chart

Press 'q' to quit the emotion detection program.

## Output Files

The program generates several output files:
- `emotion_video.avi`: Video recording with emotion annotations
- `emotion_chart.gif`: Animated chart of emotion changes
- `cumulative_emotions.jpg`: Static chart showing emotion trends over time

## Dependencies

- Flask: Web framework
- FER: Face Emotion Recognition
- OpenCV: Computer vision library
- Matplotlib: Data visualization
- NumPy: Numerical computing
- Pandas: Data manipulation
- ImageIO: Image processing

For a complete list of dependencies, see `requirements.txt`.

## Contributing

Feel free to submit issues and enhancement requests!

## License

[Add your license information here] 