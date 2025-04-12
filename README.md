# TomatoModelZoo

A comprehensive machine learning project for tomato analysis and classification. This project includes data loading, model training, evaluation, and a web interface for interacting with the trained model.

## Features

- Data loading and preprocessing
- Model training pipeline
- Model evaluation tools
- Web interface using Streamlit
- Utility functions for image processing

## Project Structure

```
TomatoModelZoo/
├── app.py              # Streamlit web application
├── data_loader.py      # Data loading and preprocessing
├── model_trainer.py    # Model training implementation
├── model_evaluation.py # Model evaluation tools
├── utils.py           # Utility functions
├── pyproject.toml     # Project dependencies
└── uv.lock           # Lock file for dependencies
```

## Setup

1. Clone the repository:
```bash
git clone https://github.com/ahmad4life/TomatoModelZoo.git
cd TomatoModelZoo
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the web application:
```bash
streamlit run app.py
```

## License

This project is open source and available under the MIT License.