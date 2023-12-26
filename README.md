# WhisperCraft: Text-to-Speech Synthesis with GANs

Welcome to WhisperCraft, an innovative project that harnesses the power of Generative Adversarial Networks (GANs) to weave enchanting and realistic human-like speech from textual inputs. WhisperCraft transforms the mundane into the extraordinary, breathing life into words and transcending the boundaries of traditional text-to-speech synthesis.

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------


## Project Overview

WhisperCraft employs advanced GAN architectures to create a seamless and natural transition from text to lifelike speech. The models are trained on extensive datasets to capture the nuances of human expression, resulting in an audio experience that is both captivating and authentic.

## Key Features

- **GAN-powered Synthesis**: Utilizes state-of-the-art GAN techniques for text-to-speech synthesis.
- **Realistic Human-Like Speech**: Generates speech with a level of realism that transcends traditional approaches.
- **Customizable Voices**: Explore a range of voices and styles to suit diverse preferences and applications.
- **Open-Source Freedom**: The project is open-source, inviting collaboration and improvement from the community.

## Getting Started

Follow these simple steps to experience the magic of WhisperCraft:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/smn06/WhisperCraft.git
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Demo:**
   ```bash
   python demo.py --text "Your text here"
   ```
   
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
