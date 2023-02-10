
# Google Assistant TTS for Home Assistant

This is a custom component bring back the deprecated 
digitalloggers component


## Installation
This component is available via HACS as a [custom repository](https://hacs.xyz/docs/faq/custom_repositories) which is the recommended method of installation. 

You can also copy `custom_components/digitalloggers` to your `custom_components` folder in HomeAssistant if you prefer to install manually.

## Example `switch` entry in your `configuration.yaml`

    # DLI Switch:
      - platform: digitalloggers
        host: "192.168.1.43"
