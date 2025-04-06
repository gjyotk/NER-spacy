# Custom NER and Redaction using Spacy

## Overview
This project implements a **Custom Named Entity Recognition (NER)** system and a **Redaction tool** using the **spaCy** and **faker** libraries. The custom NER model identifies domain-specific entities from text, while the redaction functionality masks sensitive information to ensure privacy.



## Features
- Train a custom NER model using labeled datasets.
- Identify domain-specific entities such as names, dates, addresses, and more.
- Redact sensitive information from text using customizable redaction patterns.
- Generate synthetic data for testing and training using the **faker** library.
- Easy-to-use Python-based implementation.



## Installation

### Prerequisites
- Python 3.8+
- `pip` (Python package manager)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/gjyotk/NER-spacy
   cd NER-spacy
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate # On Windows: env\Scripts\activate
   ```


## Usage

- Prepare a labelled dataset in the .spacy format for training the NER model

- Train the NER Model on labelled dataset

- Redact Sensitive Information from text using the trained model

- Optionally, Generate Synthetic Data for training or testing using the faker library



## Examples

### Input Text
```text
John Doe lives at 1234 Elm Street, New York, and works for Acme Corp.
```

### Output (Redacted Text)
```text
Mary Adams lives at 54130 Bates Village Apt. 231 and works for Shiromiya Org.
```



## Future Improvements
- Enhance NER model accuracy with additional training data.
- Add support for more entity types.
- Extend redaction options to customize masking formats.
- Incorporate GUI for easier usability.



