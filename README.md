# PAN Card Tampering Detection

This project demonstrates a method to detect tampering in PAN (Permanent Account Number) cards using image processing techniques. It utilizes Python's `skimage.metrics` module and the Structural Similarity Index (SSIM) to compare two images and identify any discrepancies that indicate tampering.

## Features
- Detects structural differences between the original and a potentially tampered PAN card image.
- Highlights the tampered areas for better visualization.
- Provides a notebook implementation for easy demonstration and experimentation.

## Future Plans
- Develop a web application to allow users to upload PAN card images for tampering detection.
- Integrate additional image preprocessing techniques for improved accuracy.
- Add support for batch processing of multiple images.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/DoCTheBest01/Pan-Card-Tampering-Detection.git
   cd pan-card-tampering-detection
   ```
2. Create a virtual environment (optional):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install the required dependencies:
   ```bash
   pip install notebook sklearn-image
   ```

## Usage
1. Open the provided Jupyter notebook:
   ```bash
   jupyter notebook notebook.ipynb
   ```
2. load your images and run the detection process.

## How It Works
- The `structural_similarity` function from `skimage.metrics` is used to compare the structure of two images.
- Areas with significant differences are marked as potential tampering regions.

## Example
for the examples you can navigate to the notebook.

## Requirements
- Python 3.7+
- Required Python libraries (included in `requirements.txt`):
  - `requests`
  - `scikit-image`
  - `matplotlib`
  - `opencv-python`
  - `numpy`
  - `pillow`
  - `imutils`

## Contributing
Contributions are welcome! If you have ideas for improvements or new features, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Author
[Your Name](https://github.com/your-username)
