# Finance Manager

## Setup Instructions

1. **Create and activate a virtual environment**:
   ```sh
   python -m venv .venv
   source .venv/bin/activate
   ```

2. **Install required libraries from `requirements.txt`**:
   ```sh
   pip install -r requirements.txt
   ```

3. **Set environment variables**:
   Create a `.env` file in the root directory with the following content:
   ```env
   SECRET_KEY=your_secret_key_here
   ```

4. **Run the application**:
   ```sh
   flask run
   # OR
   python app.py
   ```