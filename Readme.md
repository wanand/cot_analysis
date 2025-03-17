# Installing Dependencies with Pip

To set up the required environment and install dependencies for this project, follow these steps:

## Prerequisites
Make sure you have the following installed:
- [Python](https://www.python.org/downloads/) (version 3.x or higher)
- [pip](https://pip.pypa.io/en/stable/installation/)

## Steps

1. Clone this repository to your local machine:
    ```bash
    git clone <repository-url>
    cd <repository-folder>
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    ```

3. Activate the virtual environment:
   - On Windows:
      ```bash
      venv\Scripts\activate
      ```
   - On macOS/Linux:
      ```bash
      source venv/bin/activate
      ```

4. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

5. Run the cot_analysis.ipynb


## Notes
- If you encounter issues, make sure your `pip` is up to date:
    ```bash
    pip install --upgrade pip
    ```
- Use `deactivate` to exit the virtual environment when you're done.

Enjoy coding!
