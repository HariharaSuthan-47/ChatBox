# Gemini API Connection Test

A simple Python script that connects to the Google Gemini API, sends a prompt, and prints the model's response.

## Features

- Loads the Gemini API key from a `.env` file
- Tests the Gemini API connection
- Prints a concise bullet-point response
- Includes clear error handling for a missing API key

## Requirements

- Python 3.10 or newer
- A Google Gemini API key

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/HariharaSuthan-47/ChatBox.git
   cd ChatBox
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```

3. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Create a `.env` file in the project directory:

   ```text
   GEMINI_API_KEY=your_gemini_api_key
   ```

   You can copy `.env.example` as a starting point.

## Usage

Run the script with:

```bash
python San.py
```

A successful connection prints:

```text
Connection successful! Gemini response:
```

followed by the Gemini model's response.

## Configuration

| Variable | Description |
| --- | --- |
| `GEMINI_API_KEY` | API key used to authenticate requests to the Gemini API |

Never commit your real API key or `.env` file. Rotate the key immediately if it is exposed publicly.

## Project Structure

```text
ChatBox/
|-- San.py
|-- .env.example
|-- .gitignore
|-- README.md
`-- requirements.txt
```
