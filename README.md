# MSM Plugin :: Create Request from Request Auto Copy Values

This plugin extends MSM functionality to create a new request from the existing request.
New MSM system versions (since 14.4?) allows user manually to select request field values to be copied to new request.
We have noticed that some system users are rather more frustrated than happy to do this extra task/choise. Very often it's even unclear what values should be selected in the extra dialog window.
So the plugin allows to configure some rules (by request types currently) and automatically apply field values that needs to be copied from initial request to the new one.
No extra step is required from user in this case.


# !!! IMPORTANT !!!:
Since MSM system doesn't have any MSM request actions data web services by default, MSM Web Service Extensions are required (not included here).
Only if/when new location api methods will be implemented in MSM system this package could be used in your systems.
Please feel free to contact Marval Baltic if you would like to see it working.

## Compatible Versions

| Plugin  | MSM             |
|---------|-----------------|
| 1.0.0   | 14.4.0 - 14.6.1 |

## Installation

Please see your MSM documentation for information on how to install plugins.

Once the plugin has been installed as plugin parameters you need to specify:
* Rules Action Message - Name or ID of MSM Action Message to be used as container for plugin rules stored as json object.
* MSM WSE Address - MSM Web Service Extensions (not available publicly) address
* MSM WSE User Name - MSM Web Service Extensions user name (encrypted)
* MSM WSE Password - MSM Web Service Extensions password (encrypted)

## Usage

The plugin is automatically started when function "Create Request from Request" is selected in a request form.

## Contributing

 Any feedback or improvement suggestion is very welcome.