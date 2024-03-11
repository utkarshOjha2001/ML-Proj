
# Faster Whisper Speech Recognition System

Faster Whisper is a state-of-the-art speech recognition model designed for general-purpose use. This project utilizes the Faster Whisper library from Hugging Face to implement a speech recognition system without transformers and pipelines.

## Features

- Utilizes Faster Whisper for efficient speech recognition.
- Supports various GPU and CPU configurations for different processing speeds.
- Achieves high accuracy of 95-98% across multiple languages.
- Compatible with Python 3.8.11 and requires additional libraries like Librosa, PyTorch, hsdpa, logger, kafka-python, pathlib, and timeit.

## Requirements

- Python 3.8.11
- Librosa
- Faster Whisper
- PyTorch
- hsdpa
- logger
- kafka-python
- pathlib
- timeit
- torch

## Performance

- **GPU Processing Time:**
  - Large: 71 seconds
  - Medium: 64.08 seconds
  - Small: 20 seconds
  - Base: 16 seconds
  - Tiny: 13.09 seconds

- **CPU Processing Time:**
  - Tiny
  - Base
  - Small

## Language Support

- English
- French
- Spanish
- Portuguese
- Russian
- Turkish
- Dutch

## Accuracy

- Achieves an accuracy range of 95-98% across supported languages.

## File Size

- Input file size: 15 minutes

## Usage

1. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

2. Execute the script with the desired input file.

   ```bash
   python speech_recognition.py input_file.wav
   ```

## Additional Notes

- The model's performance may vary depending on the quality and length of the input audio file.
- Feel free to experiment with different GPU and CPU configurations to optimize processing speed and resource utilization.

## Contributing

Contributions are welcome! If you have any suggestions, feature requests, or bug reports, please open an issue or submit a pull request.



## Acknowledgments

- Special thanks to the developers of Faster Whisper for providing such a powerful speech recognition model.
- This project was inspired by the need for fast and accurate speech recognition in various applications.

