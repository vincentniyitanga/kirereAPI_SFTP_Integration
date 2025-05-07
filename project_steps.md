# Project Steps for kirereAPI_SFTP_Integration

## Step 1: Set Up the Environment
- Created a virtual environment:
  ```bash
  python -m venv venv
  ```
- Activated the virtual environment:
  - On Windows:
    ```bash
    venv\Scripts\activate
    ```
  - On macOS/Linux:
    ```bash
    source venv/bin/activate
    ```

## Step 2: Install Dependencies
- Created a `requirements.txt` file with the following content:
  ```plaintext
  requests==2.31.0       # For making API calls to OpenWeatherMap
  paramiko==3.2.0        # For SFTP integration
  python-dotenv==1.0.0   # For managing environment variables securely
  ```
- Installed dependencies:
  ```bash
  pip install -r requirements.txt
  ```

## Step 3: Configure API and SFTP Credentials
- Planned to create a `.env` file to store sensitive information securely.