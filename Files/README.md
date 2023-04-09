# File Structure
## Python 
[Structuring Your Project](https://docs.python-guide.org/writing/structure/)

[Guide to Python Project Structure and Packaging](https://medium.com/mlearning-ai/a-practical-guide-to-python-project-structure-and-packaging-90c7f7a04f95)

```
.
├── melhousing
│   ├── __init__.py
│   ├── classes
│   │   ├── __init__.py
│   │   └── housingdata.py
│   ├── constants
│   │   ├── __init__.py
│   │   └── myconstants.py
│   └── scripts_internal
│       └── main_internal.py
├── data
│   ├── processed
│   │   └── processeddata.csv
│   └── raw
│       └── sampledata.csv
├── scripts
│   ├── expconfig
│   │   ├── __init__.py
│   │   ├── locconfig.json
│   │   └── locconfig.py
│   └── main.py
├── tests
    ├── __init__.py
    └── test_demo.py
├── pyproject.toml
├── requirements.txt
├── LICENSE
├── README.md
├── setup.cfg
└── setup.py
```