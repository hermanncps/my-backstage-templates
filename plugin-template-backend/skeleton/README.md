# ${{values.friendly_name}}

Welcome to the ${{values.friendly_name}} backend plugin!

_This plugin was created through the Backstage CLI_

## Getting started
Run `yarn install` 

You can also serve the plugin in isolation by running `yarn start` in the plugin directory.
This method of serving the plugin provides quicker iteration speed and a faster startup and hot reloads.
It is only meant for local development, and the setup for it can be found inside the [/dev](/dev) directory.

Run `curl http://localhost:7007/${{values.component_id}}/health` to see if return is `{"status":"ok"}`
