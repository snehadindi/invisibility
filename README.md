# Invisible Cloak

This project uses OpenCV to create an "invisible cloak" effect, making a specified color (in this case, pink) disappear by blending it with a pre-captured background.

## Requirements

- Python 3.x
- OpenCV
- NumPy

## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/your-username/invisible-cloak.git
    cd invisible-cloak
    ```

2. **Create and activate a virtual environment**:

    ```bash
    python -m venv venv
    ```

    - On Windows:
      ```bash
      venv\Scripts\activate
      ```
    - On macOS and Linux:
      ```bash
      source venv/bin/activate
      ```

3. **Install the required packages**:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the script**:

    ```bash
    python invisible.py
    ```

2. **Instructions**:
   - The script will first capture the background. Ensure nothing pink is in the frame and move out of the frame during this period.
   - After capturing the background, the main loop starts. You can use a pink object to test the invisibility effect.
   - Press 'q' to quit the program.
