# Readme
Reference package for dependency injection
source: https://python-dependency-injector.ets-labs.org/tutorials/cli.html#what-are-we-going-to-build


## install
pythom -m venv venv
. venv/bin/activate
pip install -r requirements.txt

## run
MOVIE_FINDER_TYPE=csv python -m movies
MOVIE_FINDER_TYPE=sqlite python -m movies


## testing
pytest movies/tests.py --cov=movies

