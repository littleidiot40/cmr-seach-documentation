# CMR Search documentation by example

The purpose of this notebook is to document the CMR Search API by example. These examples can be executed via Jupyter Notebooks using Python code.

CMR Search is a REST-based API that provides search capabilities at the collection (dataset) and granule (file) level.

The notebooks execute HTTPS requests and parse the results in either XML or JSON format.

## Pre-requisites

1. [Python 3.7](https://www.python.org/downloads/release/python-370/) or higher `brew install python@3.7`
2. [Jupyter lab](https://jupyter.org/) `pip install jupyterlab`
3. Python libs
   - [requests](https://docs.python-requests.org/en/master/) `pip install requests` 
   - [xml.dom.minidom](https://docs.python.org/3/library/xml.dom.minidom.html) -  `pip install libxml2` for xml parsing
   - [xml.etree.ElementTree](https://docs.python.org/3/library/xml.etree.elementtree.html) `pip install lxml` for xml traversal
   - [json](https://docs.python.org/3/library/json.html) for json parsing
   - [jq](https://pypi.org/project/jq/) `pip install jq` for json traversal

## Notebooks
- Gettting started with search `search.ipynb`
- Two-step searching
- Searching for collections
- Searching for granules `granule_search.ipynb`

## Running a notebook
`cd <root of cloned repo>`
`jupyter-lab`
