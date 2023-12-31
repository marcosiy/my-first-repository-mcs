# my-first-repository-mcs
 
## Setup

Create and activate a virtual environment:

```sh
conda create -n my-first-env python=3.10

conda activate my-first-env
```

Obtain an [API Key from Alphavantage](https://www.alphavantage.co/support/#api-key) or from the prof (`ALPHAVANTAGE_API_KEY`).

Follow the [setup instructions](https://github.com/prof-rossetti/intro-to-python/blob/main/notes/python/packages/sendgrid.md) to create an account, verify your account, setup a single sender, and obtain an API Key.

Create a ".env" file and paste in the following contents:

```sh

ALPHAVANTAGE_API_KEY="_________"

SENDGRID_API_KEY="_________"
SENDER_ADDRESS="example.gmail.com"
```



Install Packages:
```sh
pip install -r requirements.txt
```


## Usage

Run the example script:

```sh
python app/my_script.py
```

Run the unemploymeny report:

```sh
#python app/unemployment.py

python -m app.unemployment
```
Send an example email:

```sh
python app/email_service.py
```

## Testing

Run tests:

```sh
pytest
```


## Usage

Run the report:
Run the unemployment report:

```sh
python app/unemployment.py

python -m app.unemployment
```


Run the stocks report:

```sh
python -m app.stocks
```


Run the web app:

```sh
# Mac OS:
FLASK_APP=web_app flask run

# Windows OS:
# ... if `export` doesn't work for you, try `set` instead
# ... or try a ".env" file approach
export FLASK_APP=web_app
flask run
```


## Testing

```sh
pytest
```


## [Deployment Guide](/DEPLOYING.md)