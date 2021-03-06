# Custom Blueprints

## Definition

A Custom Blueprint is a Blueprint created by users in your organization or by Shipyard staff. These Blueprints provide a way for technical users to create a reusable piece of code with organization specific logic that business users can use to build a Vessel. These business users are only required to provide key inputs needed for the the Vessel to work correctly. All code and requirements are abstracted away from the end user.

All Custom Blueprints are built upon [Code Blueprints](code-blueprints.md). You must select a supported language and provide the necessary code, requirements, and packages necessary to make the Blueprint usable. However, unlike Code Blueprints, you can create Blueprint Variables that users fill out on the [Inputs ](../vessels/form-input.md)tab when they are setting up a new Vessel.

As a Custom Blueprint author or editor, you are in charge of writing the code that runs for the users of your Blueprint. You can update and manage the underlying code, making updates in bulk that can affect 100s of scripts.

## Components

### Creating a Custom Blueprint

When creating a Custom Blueprint, you must **always** provide the following elements:

* [Code](../vessels/code.md)
* [Command ](../vessels/command.md)to execute the code
* [Blueprint Information](../vessels/information-card.md)

You may also _optionally_ provide these elements:

* [Blueprint Variables](blueprint-variables.md) 
* [External Package Dependencies](../vessels/external-package-dependencies.md)
* [Environment Variables](../vessels/environment-variables/)
* [Guardrails](../vessels/guardrails.md)

### Building a Vessel

When creating a Vessel from a Custom Blueprint, you must always provide the following elements:

1. [Inputs](../vessels/form-input.md) \(if any are required\)
2. [Vessel Information](../vessels/information-card.md)

You may also _optionally_ provide these elements:

1. [Triggers](../triggers/)
2. [Notifications](../vessels/notifications.md)
3. [Guardrails](../vessels/guardrails.md)

## Limitations

1. Code for a Custom Blueprint must have an adequate level of error handling and validation because it relies on user input.
2. Notifications cannot be set for all Vessels that are built from a Custom Blueprint.

## Learn More

* [How to Search for Blueprints](../../how-tos/blueprints/how-to-search-for-blueprints.md)
* [How to Create a New Blueprint](../../how-tos/blueprints/how-to-create-a-new-blueprint.md)
* [How to Edit a Blueprint](../../how-tos/blueprints/how-to-edit-a-blueprint.md)
* [How to Delete a Blueprint](../../how-tos/blueprints/how-to-delete-a-blueprint.md)
* [How to Duplicate a Blueprint](../../how-tos/blueprints/how-to-duplicate-a-blueprint.md)

