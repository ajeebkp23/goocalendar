A calendar widget for GTK using PyGoocanvas

[https://pypip.in/version/goocalendar/badge.png?style=flat](https://pypi.python.org/pypi/goocalendar)
[https://pypip.in/download/goocalendar/badge.png?style=flat](https://pypi.python.org/pypi/goocalendar)

# Nutshell #

Example usage:

```
>>> import datetime
>>> import goocalendar
>>> event_store = goocalendar.EventStore()
>>> calendar = goocalendar.Calendar(event_store)
>>> event = goocalendar.Event('Birthday',
...     datetime.date.today(),
...     bg_color='lightgreen')
>>> event_store.add(event)
```