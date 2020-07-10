# ⚠️⚠️⚠️ THIS IS A WORK IN PROGRESS. USE AT YOUR OWN RISK. ⚠️⚠️⚠️

# Hello World Superset Example Plugin

This project is meant to be used as a template to create your own Chart Plugins for Superset.

## Initializing Your Own Plugin

For now, you can fork this project to get started. Delete the `.git` folder and run `git init` if you want a clean commit history.

In the future we plan on adding a Yeoman script, and potentially moving portions of this code into a library to make plugin development simpler.

## Developing Your Plugin

To build the plugin:

```shell
npm install
npm run build-dev
```

Superset will need to load your built plugin bundle from somewhere. You can temporarily serve the plugin locally using the following command:

```shell
npm run serve-dev
```

Use the "Custom Plugins" menu in Superset to make Superset aware of your plugin.

To build for production:

```shell
npm run build-prod
```
