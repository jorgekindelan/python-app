# Currency Converter (Python + Flask)

**Author:** Juan Vicente Herrera Ruiz de Alejo  
**GitHub:** [@juanviz](https://github.com/juanviz)  
**Affiliation:** ICAI

A lightweight Flask web application that converts an amount in euros to U.S. dollars using a simple web interface.

## Overview

This repository contains a small Flask app that:

- Presents a web form where the user can enter an amount in euros
- Converts the submitted value to U.S. dollars using a predefined conversion rate
- Displays the converted result on the same page

The code is intentionally minimal and easy to understand, making it a good starting point for learning Flask basics, form handling, and template rendering.

## Project Structure

- `currency_converter.py` – Main Flask application. Defines the web routes, handles form input, and performs the currency conversion.
- `templates/index.html` – Jinja2 template for the web UI.
- `requirements.txt` – Python dependencies required to run the app.

## Getting Started

### 1) Install dependencies

```sh
pip install -r requirements.txt
```

### 2) Run the app

```sh
python currency_converter.py
```

### 3) Open in your browser

Visit `http://127.0.0.1:5000/` to access the currency converter interface.

## Configuration

The conversion rate is currently hard-coded in `currency_converter.py`. You can customize it by editing the `CONVERSION_RATE_EUR_TO_USD` constant.

## License

This project is licensed under the MIT License. See [MIT License](https://opensource.org/licenses/MIT) for details.
