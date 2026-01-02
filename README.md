# Karabiner Configuration

This repository contains a `karabiner.json` file for [Karabiner-Elements](https://karabiner-elements.pqrs.org/), a powerful keyboard customizer for macOS.

## Modifications

This configuration includes the following modifications:

*   **Home Key**: Moves the cursor to the beginning of the line.
    *   `Home` -> `Left Command + Left Arrow`
    *   `Left Shift + Home` -> `Left Command + Left Shift + Left Arrow` (for selecting text to the beginning of the line)
*   **End Key**: Moves the cursor to the end of the line.
    *   `End` -> `Right Command + Right Arrow`
    *   `Left Shift + End` -> `Right Command + Left Shift + Right Arrow` (for selecting text to the end of the line)
*   **Swap Modifier Keys**: Swaps the `Left Command` and `Left Option` keys. This is to support the Razer Ornata Chroma keyboard with the Mac.
    *   `Left Command` -> `Left Option`
    *   `Left Option` -> `Left Command`

## Installation

Install [Karabiner-Elements](httpss://karabiner-elements.pqrs.org/).

Then, run the install.sh script:

    ./install.sh

