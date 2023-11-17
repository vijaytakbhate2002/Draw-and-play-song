# Draw-and-play-song

Welcome to Draw-and-play-song, a fun Streamlit application that combines the concepts of deep learning and music to create an interactive experience. This project focuses on image classification, specifically digit classification from 0 to 9. Here's how it works:

## Project Overview

1. **Draw Digit:** Use the drawing section to draw a digit from 0 to 9.

2. **Image Processing:** The backend algorithm will crop the drawn image as per the requirements.

3. **Digit Classification:** The pre-trained digit classification CNN model will predict the digit based on the drawn image.

4. **Music Interaction:** Once the digit is identified, a numbered song corresponding to the drawn digit will play automatically.

5. **Stop Song:** By clearing the draw box, the music will stop.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/vijaytakbhate2002/Draw-and-play-song.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:

   ```bash
   streamlit run app.py
   ```

4. Have fun drawing and playing songs with deep learning!

## Contributing

We welcome contributions! Please read our [Contributing Guidelines](CONTRIBUTING.md) to get started.

## License

This project is licensed under the [MIT License](LICENSE).
