# DualSense-playstation-hid-game-compatibility

The **DualSense** is a a game controller developed by [Sony Interactive Entertainment](https://www.pcgamingwiki.com/wiki/Company:Sony_Interactive_Entertainment "Company:Sony Interactive Entertainment") and manufactured by [Sony](https://www.pcgamingwiki.com/wiki/Company:Sony "Company:Sony"), released on November 12, 2020. It was released alongside the [PlayStation 5](https://www.pcgamingwiki.com/wiki/Emulation:PlayStation_5 "Emulation:PlayStation 5").
In addition to features carried over from its predecessor, the [DualShock 4](https://www.pcgamingwiki.com/wiki/Controller:DualShock_4 "Controller:DualShock 4"), the DualSense has introduced two new features, adaptive triggers and haptic feedback. On PC, selected games have native support for either feature or both.

In addition to the standard white color model, the DualSense also comes in midnight black, cosmic red, nova pink, starlight blue, galactic purple and grey camouflage. It also has limited editions for games like God of War: Ragnarok, [Hogwarts Legacy](https://www.pcgamingwiki.com/wiki/Hogwarts_Legacy "Hogwarts Legacy"), and Marvel's Spider-Man 2.

It has a pro-orientated version in the form of [DualSense Edge](https://www.pcgamingwiki.com/wiki/Controller:DualSense_Edge "Controller:DualSense Edge"), which was released on January 26, 2023.

The DualSense is a generic DirectInput controller, so it is not supported by games that use the XInput API unless XInput wrappers like [Steam Input](https://www.pcgamingwiki.com/wiki/Steam_Input "Steam Input") are used. Some wrappers can expose additional features such as gyroscope, touchpad control including the ability to change lightbar color, and built-in speaker. The DualSense is supported natively in selected games, where features like adaptive triggers and haptic feedback are natively supported (see [support in games](https://www.pcgamingwiki.com/wiki/Controller:DualSense#Support_in_games)), however it is only supported with a wired connection. Audio passthrough to the 3.5mm audio jack also only works when wired.
(Source: https://www.pcgamingwiki.com/wiki/Controller:DualSense#Linux)

# Motivation

DualSense is a fairly recent gamepad. There is a lot of information on the internet about Windows, but having been a long time Arch Linux user, I would like to create a small documentation about DualSense compatibility in different games.  This repo is heavily inspired by [PCGW]([PCGamingWiki PCGW - an encyclopedia of PC game fixes](https://www.pcgamingwiki.com/wiki/Home)). 

# My test setup:

OS: Arch Linux with latest linux-zen kernel
Gamepad: Sony DualSense CFI-ZCT1W
Wine/proton builds I usually experiment with: wine-ge-custom, wine-staging, proton-ge-custom,  proton experimental
I use these wine builds with Lutris, proton builds with Steam.

# DualSense Lutris Compatibility

| Game                          | Compatibility | Vibration | PlayStation® Icons | Connection | Initial Release Date | Notes                |
| ----------------------------- | ------------- | --------- | ------------------ | ---------- | -------------------- | -------------------- |
| TEKKEN 7                      | ✅             | ✅         | ❌                  | Wired/BT   | 18. February 2015    | Working as intended. |
| Colin McRae Rally 04          | ✅             | ❌         | ❌                  | Wired/BT   | 2. April 2004        | Working as intended. |
| Tokyo Ghoul: re Call to Exist | ✅             | ✅         | ❌                  | Wired/BT   | 15. November 2019    | Working as intended. |
| Control                       | ✅             | ✅         | ❌                  | Wired/BT   | 27. August 2019      | Working as intended. |
| Dark Souls III                | ✅             | ✅         | ❌                  | Wired/BT   | 24. March 2016       | Working as intended. |


