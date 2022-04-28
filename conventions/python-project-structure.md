# Python Project Structure

## Directory
```
modulename
- .gitignore: tell git what to ignore
- README.md
- LICENSE.md
- requirements.txt
- setup.py

- venv

- lib

- bin

- data
  - input.csv
  - output.csv
  
- {{ modulename }}
  - __init__.py
  - {{ modulename }}.py
  - helpers.py
  - main.py
  
- docs
  - conf.py
  - index.rst
  
- tests
  - __init__.py
  - test_main.py
  - test_helpers.py
  ```


## References
- https://docs.python-guide.org/writing/structure/