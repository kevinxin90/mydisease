# outbreak.api
The data API server for outbreak.info

##  To install dependecies

  (recommend to setup a fresh Python venv first)

    pip install -r requirements.txt

## To start the dev server

  (require to have ES running at `localhost:9200` by default)

    python web/index.py --debug --conf=config_web

  To override the default settings, create a `config_web_local.py` on the root folder and include extra settings.
