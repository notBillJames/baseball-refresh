# Baseball Refresh

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

The purpose of this project is to reacquaint myself with the Python and Data Science skills I once used to have. Originally I was just going to use the lahman baseball database and do some basic stuff but there's been a question nagging at me throughout the past baseball season.

**What happened to Zac Gallen?**

As I've been trying to get back into this, as per usual, I have gotten into some rabbit holes. I've discovered Cookiecutter Data Science, which I think will be a boon long-term for me as I improve my skills.

## Vision

Going forward, I want to get my feet in the water again by sourcing some external data to outline Zac's rise as a pitcher and subsequent decline.

To take my skills further, I want to explore the underlying data that led to his decline.

## Project Organization

There is a lot in this structure that I don't use right now. But I want continue using `ccds` so that I can build off the strengths of the platform as I learn and grow.

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for
│                         baseball_refresh and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── baseball_refresh   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes baseball_refresh a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling
    │   ├── __init__.py
    │   ├── predict.py          <- Code to run model inference with trained models
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

---
