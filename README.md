YML Presets file for Ghost (UI)
===============================

Those files are presets loaded by Ghost.
They contains a set of Ghost feature needed by a generic component.

YML syntax:


```
#!yaml
description: Preset description
features:
  {key}: {value}
  {key}: {value}


```

You can use some slug/placeholder in the `value` element, they will be replaced by Ghost when importing:

* `${GHOST_CLIENT}` based on the Ghost Domain
* `${GHOST_APP}` current app name
* `${GHOST_ENV}` current app env
* `${GHOST_ROLE}` current app role

