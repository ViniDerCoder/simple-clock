### Simple Clock Project

This project is a simple clock application that displays both analog and digital clocks. It allows customization of various clock properties such as colors and animation settings.

## Features

- **Analog Clock**: Displays the current time with hour, minute, and second hands.
- **Digital Clock**: Displays the current time in digital format.
- **Customizable Colors**: Allows customization of background color, clock face color, hand colors, and more.

## Installation


1. Clone the repository:
    ```sh
    git clone https://github.com/ViniDerCoder/simple-clock.git
    ```
2. Open `index.html` in your web browser to view the clock.

Or Use the url and iframes to integrate the clock in your website: https://vinidercoder.github.io/simple-clock/



## Usage

### URL Parameters

You can customize the clock by adding URL parameters. Here are some examples:

- `smoothSeconds`: Enable or disable smooth second hand animations (`true` or `false`(default)).
- `showDigital`: Show or hide the digital clock (`true`(default) or `false`).
- `animateDigital`: Enable or disable digital clock animation (`true`(default) or `false`).
- `digitalOnTop`: Display the digital clock on top of the analog clock (`true`(default) or `false`).
- `showDate`: Show or hide the current date (`true`(default) or `false`).
- `timeOffset`: Specify a time offset in hours (number (default = 0)).
- `showSecondHand`: Hide or show the seconds hand (`true`(default) or `false`).

- `colorPreset`: Set a color preset (`dark`, `light`, etc.).
- `customColors_backgroundColor`: Set the background color (e.g., `#ffffff`).
- `customColors_clockFaceColor`: Set the clock face color (e.g., `#000000`).
- `customColors_handColor`: Set the hand color (e.g., `#ff0000`).
- `customColors_secondHandColor`: Set the second hand color (e.g., `#00ff00`).
- `customColors_hourMarkerColor`: Set the hour marker color (e.g., `#0000ff`).
- `customColors_digitalClockColor`: Set the digital clock color (e.g., `#ffff00`).
- `customColors_digitalClockBackgroundColor`: Set the digital clock background color (e.g., `#00ffff`).

### Example URL

```
https://vinidercoder.github.io/simple-clock/?animateDigital=true&digitalOnTop=false&customColors_backgroundColor=%23ffffff&customColors_clockFaceColor=%23000000&customColors_handColor=%23ff0000&customColors_secondHandColor=%2300ff00&customColors_hourMarkerColor=%230000ff&customColors_digitalClockColor=%23ffff00&customColors_digitalClockBackgroundColor=%2300ffff
```

## Images

- Default: ![image](https://github.com/user-attachments/assets/377dd3bd-b77c-42b0-833a-0e5244dfbf78)
- Example from above: ![image](https://github.com/user-attachments/assets/e8afd344-a409-444a-89f1-e61d5a747b76)


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
