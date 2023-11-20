# openai_assistant
Home automation with the OpenAI Assistants API

**Note:** you will need Hue lights to use this app as is

Ensure you add a `.env` file with the following:

```bash
OPENAI_API_KEY=YOUR_OPENAI_API_KEY
```

Ensure you install `portaudio`. E.g., on MacOS with brew:

```bash
brew install portaudio
```

Install Python packages with `pip install -r requirements.txt`

In `hue.py`, replace the IP with with IP of your bridge. Check https://github.com/studioimaginaire/phue for help with connecting to the bridge.

Now run the app with `python3 hue.py`