# Zyntra Security Analyzer

A Flask app for asking questions about fictional or public cybersecurity documents. It returns a plain-language answer grounded in uploaded file text. Uploaded files are treated as source material, not instructions to the model.

## Run locally

1. Install Python dependencies: `python -m pip install -r requirements.txt`
2. Copy `.env.example` to `.env` and add your BearcatGPT key after `BEARCAT_KEY=`. Keep `.env` private; it is excluded from Git.
3. Start the app: `python app.py`
4. Open `http://127.0.0.1:5001`, select `zyntra_security_quick_guide.md`, and ask: `What should I do if I clicked a suspicious link?`

The guide included here is fictional demonstration content. For real security incidents, use the official procedures for your organization and verify any AI-generated summary against its source.
