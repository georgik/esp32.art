+++
title = "OpenTyrian - ESP32 Port"
description = "Port of the arcade-style DOS shooter Tyrian to ESP32 using SDL3 and ESP-IDF 5.4."
date = "2025-05-27"

[extra]
tags = ["game", "SDL", "C", "arcade"]
mcus = ["esp32-p4"]
boards = [
  { name = "ESP32-P4-Function-EV-Board", flash_url = "https://github.com/georgik/OpenTyrian/releases" }
]
source_url = "https://github.com/georgik/OpenTyrian"
images = ["https://camo.githubusercontent.com/05fd86ef2521eac1995f5db32064893bf5e940c8d80725009bfe71ab6fc7877e/68747470733a2f2f696d672e796f75747562652e636f6d2f76692f554c356554557637535a452f302e6a7067"]
+++

OpenTyrian is a port of the classic DOS game Tyrian to the ESP32 platform.

Originally ported by Gadget Workbench, this version was updated to run on newer ESP32 boards with ESP-IDF 5.4 and SDL3 from the Espressif Component Registry. Game data is stored in flash memory to improve reliability over SD cards.

**Storyline**:
You play as Trent Hawkins, a fighter pilot battling the MicroSol corporation to save the galaxy, in this fast-paced vertical scrolling shooter.
