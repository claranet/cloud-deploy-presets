YML Presets file for Claranet Cloud Deploy (Ghost Project)
==========================================================

Those files are presets loaded by Ghost - Web UI.
They contains a set of Ghost feature needed by a generic component.

YML syntax:


```
#!yaml
description: Preset description
features:
  -
    name: {key}
    value: {value}
    provisioner: {provisioner}
  -
    name: {key}
    value: {value}
    provisioner: {provisioner}

```

You can use some slug/placeholder in the `value` element, they will be replaced by Ghost when importing:

* `${GHOST_CLIENT}` based on the Ghost Domain
* `${GHOST_APP}` current app name
* `${GHOST_ENV}` current app env
* `${GHOST_ROLE}` current app role

