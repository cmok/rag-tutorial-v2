# rag-tutorial-v2
Create a database from custom data and the local llama-3 uses this to answer user questions.

Pull llama3
```
ollama pull llama3
```

>> **_NOTE:_** Run/Tested with Python 3.11.9

```python
# Create python virtual environment with the default python version
python3 -m venv .venv

# Active the virtual environment
source .env/bin/activate
```

```python
pip install -r requirements.txt
```

```python
python populate_database.py
```

```python
python query_data.py "How to get into a jail?"
```

```python
pytest -s
```

Reference: YouTube video
* [RAG](https://youtu.be/2TJxpyO3ei4?si=-SGJKXHWVihMk8WY).
* [Virutal Environment in Pythong](https://www.freecodecamp.org/news/how-to-setup-virtual-environments-in-python/)