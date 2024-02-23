# Custom Templates

Home Assistant added the ability to write your Jinja templates off onto it's own file. HA will load it at runtime and you can then include it in your template sensors, etc. This allows you to create funtions that you reuse without having to copy code multiple times.

I'll post multiple examples as I've moved a lot of the jinja I had for templates into this format.

Most of these were taken from automations that [Jeffrey Stone](https://github.com/thejeffreystone/homeassistant-config) had. I've pulled them out into separate jinja files.

I use them in automations by calling them for example:

'''
{% from 'intro.jinja' import greeting %}
{{ greeting() }}
'''

If you take a look at the status_announcement.jinja you can see how these are used.
