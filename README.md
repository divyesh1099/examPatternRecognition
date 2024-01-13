
# Exam Pattern Recognition

This project, `examPatternRecognition`, is designed to analyze exam question patterns by identifying the weightage of various topics over the years. It processes PDF files containing exam questions, uses OCR to extract text, and then analyzes the data to predict the importance of different topics.

## Features

- PDF processing to extract question text and metadata.
- OCR (Optical Character Recognition) to convert images to text.
- Data analysis to determine the weightage of topics.
- Visualization to display the topic weightage in a specified year.
- Export functionality to save the visualizations.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them:

- Python 3.6 or higher
- PyMuPDF
- pytesseract
- PIL (Pillow)
- pandas
- matplotlib

You can install the necessary libraries using `pip`:

```sh
pip install fitz pytesseract pillow pandas matplotlib
```

Make sure that you have Tesseract OCR installed on your system, which pytesseract uses to perform OCR.

### Installing

1. Clone the repository:

```sh
git clone https://github.com/divyesh1099/examPatternRecognition.git
```

2. Navigate to the project directory:

```sh
cd examPatternRecognition
```

3. Install the requirements:

```sh
pip install -r requirements.txt
```

4. Run the Jupyter Notebook sequentially from top to bottom. 

## Usage

To use this project, replace the placeholder values in the scripts with your actual file paths, topic names, and years of interest.

For detailed instructions, see the comments in the script files.

## Visualization

This project can generate bar charts representing the weightage of each topic for a specified year. To save a chart, use the `savefig` function in the script.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

- **Divyesh Nandlal Vishwakarma** - *Initial work* - [divyesh1099](https://github.com/divyesh1099)

See also the list of [contributors](https://github.com/divyesh1099/examPatternRecognition/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Contact

- **Divyesh Nandlal Vishwakarma**
- Email: divyesh1099@gmail.com

## Acknowledgments

- Arjun Sing (Hon. Sailor in the Indian Navy)
- ChatGPT