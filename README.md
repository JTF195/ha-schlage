# Schlage WiFi locks integration for Home Assistant
A Home Assistant custom integration for Schlage Encode (and similar) WiFi locks.

> [!WARNING]
> This custom integration will be unsupported after Home Assistant release
> 2023.9.0, which will include native support for Schlage Encode locks.
>
> The custom integration hosted here will be removed in October 2023,
> which will cause issues for any installs via HACS. Please prepare to
> replace any installs of this integration with the native Home Assistant
> support.

## Installation

You can install this component in two ways: via
[HACS](https://github.com/hacs/integration) or manually.

### HACS

If you have HACS, go to the three-dot menu and click `Custom
repositories`. Paste the link to the Github repository and select "Integration"
as the category.

### Manual

1.  Download the code from GitHub. Either download the zip file of the code, or
    clone the master branch using the `git clone` command.
2.  Unzip the code and place the `custom_components` folder in your
    configuration directory (or add its contents to an existing
    `custom_components` folder).

    It should look similar to this:

    ```shell
    └── ...
    └── configuration.yaml
    └── custom_components/
        └── schlage/
            └── __init__.py
            └── __config_flow.py
            └── __const.py
            └── ...
    ```

3.  Restart Home Assistant

## Component Configuration

Once the component has been installed, you need to configure it using the web interface in order to make it work.

1.  Go to `Settings --> Devices & Services`.
2.  Click `+ Add Integration`.
3.  Search for "Schlage Encode Lock"
4.  Select the integration and Follow setup workflow
