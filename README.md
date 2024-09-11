# Phishing Link Detection

This project leverages machine learning to detect phishing links by analyzing URLs and predicting their legitimacy.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Usage](#usage)
- [Model](#model)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Project Overview

Phishing attacks use deceptive URLs to trick users into sharing sensitive information. This project develops a machine learning model to classify URLs as either phishing or legitimate, helping to identify and mitigate these attacks.

## Features

- **Feature Extraction:**
  - Protocol (e.g., HTTP, HTTPS)
  - Domain name
  - Presence of `@` symbol
  - Redirection using `//`
  - Prefix-suffix separation in domain name
  - Subdomains count
- **Model Training:** Trains a machine learning model to predict URL legitimacy.
- **Prediction:** Provides predictions on whether a URL is "Normal" (legitimate) or "Malicious" (phishing).

## Usage

1. Open the `Phishing_Link_Detection.ipynb` notebook.
2. Execute the cells to load the dataset, extract features, and train the model.
3. Use the trained model to classify URLs.

## Model

The model uses machine learning techniques to analyze URL features.

**Algorithm Used:**
- **Decision Tree Classifier:** This algorithm was used in the initial implementation but showed low accuracy. Future updates will explore alternative algorithms to improve performance.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue with any suggestions or improvements.
