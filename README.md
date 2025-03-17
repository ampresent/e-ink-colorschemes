# Ink - Display Color Schemes README

## Introduction

This repository is dedicated to storing software color schemes for e - ink displays. The main goal is to optimize the display effects on low - color - depth monitors, making the visual experience more comfortable and vivid. Additionally, we are maintaining a list of tested display devices. Currently, the only device on the list is the Dasung Paperlike Color.

## Purpose of Color Schemes

E-ink displays, especially those with low color depth, often face chalenges in distingushing colors. The color schemes in this repository are carefully crafted to address these issues. They aim to:

**Enhance Color Contrast**: Make text and images more distinguishable, which is crucial for reading and viewing content.

**Optimize Color Representation**: Although the number of colors is limited, the schemes try to map the available colors in a way that closely mimics the original appearance of the content.

**Reduce Color Jitter**: Monitors use lazy refreshing. It tricks our brains and eyes, trading display quality for stable rates. But it fails with too many dark areas and causing color jitter.

## How to Use

**Download the Color Scheme Files**: Clone this repository to your local machine using `git clone https://github.com/ampresent/e-ink-colorschemes`.

**Apply the Color Scheme**: The specific method of applying the color scheme depends on the software you are using on your e - ink display. For example, if you are using a custom reader software, there may be an option to load a color configuration file. Locate the appropriate color scheme file (usually in a format like `.json` or `.xml` depending on the software's requirements) in the repository and select it in the software's settings.

## Supported Display Devices

- [x] (Dasung Paperlike Color)

## Adding New Devices & Apps

If you have tested these color schemes on a different e - ink display device or have a new device that you want to test, please contribute to this repository by following these steps:

**Create a New Device Entry**: In the `devices.md` file (or create it if it doesn't exist), add a new section for your device. Include details such as the device model, manufacturer, resolution, color depth, and any unique features.

**Describe the Testing Process**: Explain how you tested the color schemes on the device. Include information about the software used for testing, any adjustments made to the color schemes during testing, and the overall testing environment.

**Share the Results**: Share your findings, including which color schemes worked well, any issues encountered, and suggestions for improvement.

## Contributing

We welcome contributions to improve the color schemes and expand the list of tested devices. If you want to contribute:

Fork the repository.

Make your changes (such as modifying color schemes, adding new schemes, or updating the device list).

Create a pull request, clearly describing the changes you have made and their purpose.

## License

The color schemes and related documentation in this repository are released under the GPLv2 license. Please review the `LICENSE` file for more details.
