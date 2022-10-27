# Hello, World!

## Installing requirements

Requires Python 3.8 or later.

The requirements can then be installed using pip:

```
python3.8 -m pip install -r requirements.txt
```

## Running the app

```
uvicorn main:app
```

The app will listen on port 8000.

http://127.0.0.1:8000

The greeting can be configured with an query parameter:

http://127.0.0.1:8000/?name=Dave
