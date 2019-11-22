# bk_pn_examples
Short demonstration of panel, bokeh and hvplot/holoviews for the Strasbourg data science meetup

Courte démonstration de panel, bokeh et hvplot/holoviews pour la meetup data science de Strasbourg.

## Comment faire
- créez un environnement ou installer les packages listés dans environment.yml
- ouvrez et laisser tourner `Create DB.ipynb` afin de créer la DB simulée (ça peut durer qq minutes)
- `Viz.ipybn`  présente le contexte ainsi que plein d'exemples fonctionnels. Le dashboard a été déplacé dans `dashboard.ipybn` afin qu'il puisse tourner correctement:

`panel serve dashboard.ipybn --show`

vous pouvez aussi tester

`panel serve dashboard.ipybn Viz.ipybn --show` afin de voir le portail multi-app de Bokeh.

- `Meetup.ipybn` contient ce que nous avons vu le 2019-11-21

