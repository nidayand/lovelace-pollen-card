# pollen-card
A Lovelace card to display the sensor data from the integration component.
![Screenshot 2022-08-05 at 22 37 45](https://user-images.githubusercontent.com/2181965/183159066-2cef1a6e-e59b-4bb3-832b-7bff781b471c.png)

## Requirement
- [Home Assistant Pollenprognos integration](https://github.com/JohNan/homeassistant-pollenprognos)

## Credits
Rewrote @isabellaalstrom [pollenprognos-card](https://github.com/isabellaalstrom/lovelace-pollenprognos-card) to fit the pattern of the integration component.

## Options

| Name | Type | Default | Description
| ---- | ---- | ------- | -----------
| type | string | **Required** | `custom:pollen-card`
| city | string | **Required** | City from which you have sensors
| allergens | list | **Required** | List of allergens for which you have sensors
| title | boolean | **Optional** | Custom title if string, boolean value if generated or not to show. Default is generated text
| show_text | boolean | **Optional** | Set to `true` if you want to show the state text under the images