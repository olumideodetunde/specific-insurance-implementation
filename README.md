# Specific Insurance Implementation

I set this repo up as a place to keep the insurance data science work I want to come back to over time. The idea is simple. I want one clean place for small implementation notebooks, standard industry tasks, and the kinds of examples I can reuse instead of rebuilding from scratch each time.

This is mostly for me. I want the work here to stay practical, easy to revisit, and close to the way I actually think through insurance problems.

## Getting started

I am using Python and a virtual environment for this project.

If I already have the environment, I activate it with:

```bash
source .venv/bin/activate
```

If I need to create it again, I can do that with:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -U pip
pip install -e .
```

If I want to use `uv`, I can sync the project with:

```bash
uv sync
```

## Notebooks

- `rms_output_layer_and_portfolio_aggregation_.ipynb` - notes and implementation work around RMS output handling and portfolio aggregation.

## What I want to keep here

- small insurance focused implementation notebooks
- practical examples I can return to later
- useful workflows for common industry tasks
- reference work that is easy to update as I learn more

