# cookiecutter-udata-theme

A cookiecutter template for a uData theme

## Usage

```
pip install cookiecutter
cookiecutter https://github.com/opendatateam/cookiecutter-udata-theme
```

Provide the requested informations and then you can go in the newly created directory
(which will be the `project_slug` that you provided) and launch the `docker-compose` stack:

```
cd $project_slug
docker-compose up
```

You ready to start hacking on your new theme.
You can go on <http://localhost:7000> to see your development server with livereload.

See the [udata theming documention](https://udata.readthedocs.io/en/stable/creating-theme/)
to know the possibilities.
