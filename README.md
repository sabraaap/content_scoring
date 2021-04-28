# Content Scoring

The purpose of this project is to score every page on a website, split into `catch`, `connect` and `convert`, using its Google Analytics data and data scraped directly from the site.

## Quick Start

Follow the guide [here](https://developers.google.com/analytics/devguides/reporting/core/v4/quickstart/service-py), to get set up with the Google Analytics API. You should end up with two files which you need to put in this directory: `client_secrets.json` and `analyticsreporting.dat`.

Create and setup a virtual environment

```sh
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Make a copy of `.env.example` and rename it to `.env`. Update the values as necessary

Open jupyter notebook

```sh
jupyter notebook
```

Open `content_scoring.ipynb` and run all code blocks chronologically
