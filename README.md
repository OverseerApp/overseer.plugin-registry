# Overseer Plugin Registry

This is the registry of plugins available for Overseer.

## Submitting Your Plugin

To submit your plugin for review:

- Clone this repository.
- Create a new branch.
- Add information about your plugin to the end of the [Plugins JSON File](./plugins.json).
- Create a pull request for your change.

Your plugin will be reviewed for safety and stability. If accepted, your PR will be merged.

```json
[
    ...
    {
        ...
    },
    {
        "name": "Plugin's Name",
        "author": "Plugin's authors name",
        "description": "A description of the plugins functionality",
        "license": "The license of the plugin",
        "githubRepository": "The github repository url"
    }
]
```

## Plugin Development

Plugins can be developed using the Overseer Plugin SDK available in the [overseer.integration](https://github.com/OverseerApp/overseer.integration) repository
