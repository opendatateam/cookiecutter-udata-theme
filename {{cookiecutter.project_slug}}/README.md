# {{ cookiecutter.project_name }}

{{ cookiecutter.description }}

## Usage

Install the theme package in you udata environement:

```bash
pip install {{ cookiecutter.project_slug }}
```

Then, define the installed theme as current in you `udata.cfg`:

```python
THEME = '{{ cookiecutter.project_slug }}'
```

## Development

There is a `docker-compose` configuration to get started fast.
Just run:

```bash
docker-compose up
```

Then go to <http://localhost:7000> to connect to the development server
with live reload.
