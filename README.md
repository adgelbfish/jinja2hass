# jinja2hass
takes a csv and runs a jinja2 template on it, designed for generating config for home assistant

installation: `pip3 install jinja2hass`

usage: `jinja2hass template.yaml input.csv output.yaml`

the jinja2 template gets the csv entries as a dict named entries where the keys are the csv headers.

