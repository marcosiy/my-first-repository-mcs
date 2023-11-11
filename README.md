# my-first-repository-mcs
 
## Setup

Create and activate a virtual environment:

```sh
conda create -n my-first-env python=3.10

conda activate my-first-env
```

Obtain an [API Key from Alphavantage](https://www.alphavantage.co/support/#api-key) or from the prof (`ALPHAVANTAGE_API_KEY`).

Create a ".env" file and paste in the following contents:

```sh

ALPHAVANTAGE_API_KEY="_________"
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
python app/unemployment.py

```