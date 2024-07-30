# Selenium Web Automation Project

This project uses Selenium WebDriver to automate tasks on the [Elefant](https://www.elefant.ro) website, such as checking product prices and simulating login attempts.

## Prerequisites

- Python 3.6+
- Google Chrome
- ChromeDriver (match your Chrome version)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/poprobert0412/VerificareTestareProdusElefant.git
   cd your-repo-name
   ```

2. **Install dependencies:**

   ```bash
   pip install selenium
   ```

## Usage

1. Ensure `chromedriver` is in your PATH or update the script with its location:

   ```python
   chrome = webdriver.Chrome(executable_path='/path/to/chromedriver')
   ```

2. Run the script:

   ```bash
   python main.py
   ```

## What the Script Does

- Maximizes the browser window and navigates to a product page.
- Retrieves product details and checks for specific elements.
- Simulates login with invalid credentials and checks the login button state.
