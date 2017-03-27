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
