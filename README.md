# Web Automation with Selenium

This repository contains examples of web automation using Selenium with Python. The examples cover various common tasks such as finding elements, interacting with buttons, handling tabs, scrolling, and more.

## Repository Structure

- `main.py`: Contains different web automation tasks implemented using Selenium.

## Setup and Installation

To run the scripts in this repository, you'll need to have the following installed:

- Python 3.x
- Selenium
- ChromeDriver

### Installing Selenium

You can install Selenium using pip:

    ```bash
    pip install selenium

## Usage

### 1. Finding Elements and Interacting with Them

This example demonstrates how to use Selenium to:

- Find elements using different locators like `By.NAME`, `By.CSS_SELECTOR`, and `By.ID`.
- Interact with input fields and buttons on a web page.

  ```python
  # Locate text box by name and send keys
  text_box = driver.find_element(by=By.NAME, value="my-text")
  text_box.send_keys("Selenium")

# Locate and click the submit button
submit_button = driver.find_element(by=By.CSS_SELECTOR, value="button")
submit_button.click()
