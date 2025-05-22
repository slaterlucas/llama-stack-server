### How to spin up server

UV_PYTHON=/opt/homebrew/bin/python3.10

pip install -r requirements.txt

uv run --with llama-stack llama stack build --template together --image-type venv

then run server.py