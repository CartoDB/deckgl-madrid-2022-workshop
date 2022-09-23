# Visualizing geospatial data with Python

Open Visualization Collaborator Summit
Thursday 22nd - Friday 23rd September 2022
OpenJS Foundation

https://deck.gl/events/madrid-summit-2022/

In this workshop we will explore some tools to render geospatial data in a Jupyter Notebook.

Slides: https://docs.google.com/presentation/d/1bpqyLWsa9DKBFcjWtsrDfS36IX2vWEM6XF4tlfW8dYg/edit?usp=sharing

## Setup

It requires Python3 (+3.7)

**Prepare the virtual environment**
```
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
```

**Configure Jupyter**

```
jupyter nbextension install --sys-prefix --symlink --overwrite --py pydeck
jupyter nbextension enable --sys-prefix --py pydeck
```

## Workshop

```
jupyter notebook
```

Author: Jesús Arroyo

Company: CARTO
