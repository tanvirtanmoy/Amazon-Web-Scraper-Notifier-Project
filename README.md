# Amazon-Web-Scraper-Notifier-Project

This project is designed to scrape product information from Amazon and send notifications when specific criteria, such as price drops, are met. The project is implemented in Python using various libraries for web scraping, data handling, and notification.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Features](#features)
- [Configuration](#configuration)
- [Contributing](#contributing)

## Introduction

This project provides a way to monitor product prices on Amazon and receive notifications if the price drops below a specified threshold. It can be useful for tracking product prices and getting the best deals.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your_username/amazon-web-scraper-notifier.git
    cd amazon-web-scraper-notifier
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Set up environment variables:
    - Create a `.env` file in the project root directory.
    - Add your environment variables (e.g., `email address`, `email key` etc.) to the `.env` file.



## Features

- **Web Scraping**: Scrapes product details from Amazon.
- **Notification System**: Sends email notifications when criteria are met.
- **Customizable**: Easily configure the product URLs and notification criteria.

## Configuration

1. **Amazon Product URLs**:
    - Specify the product URLs in a configuration file or directly in the script.

2. **Notification Criteria**:
    - Set the price threshold and other criteria for notifications in a configuration file or directly in the script.

3. **Email Notifications**:
    - Configure email settings (email address and email key) in the `.env` file.
  
    - 
## Contributing

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-branch
    ```
3. Make your changes.
4. Commit your changes:
    ```bash
    git commit -am 'Add new feature'
    ```
5. Push to the branch:
    ```bash
    git push origin feature-branch
    ```
6. Create a new Pull Request.



