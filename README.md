# Flask QR Code Generator

Flask application for generate QR Code pointing an URL passing input

## Installation

First, you need to clone this repository:

```bash
$ git clone git@github.com:jighen555/generateQRCode.git
```

Or:

```bash
$ git clone https://github.com/jighen555/generateQRCode.git
```

Then change into the `flask-examples` folder:

```bash
$ cd generateQRCode
```

Now, we will need to create a virtual environment and install all the dependencies:

```bash
$ python3 -m venv venv  # on Windows, use "python -m venv venv" instead
$ . venv/bin/activate  # on Windows, use "venv\Scripts\activate" instead
$ pip install -r requirements.txt
```

## How to Run a Specific Example Application?

Just execute these commands:

```bash
$ flask run
```

The applications will always running on http://localhost:5000.

## Example Applications Menu

You can call `/generateQRCode` and pass a JSON input file like this:
```bash
{
  "url": "http://www.google.com"
}
```
The API save a QR Code on the same folder.
