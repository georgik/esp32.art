+++
title = "Spooky Maze Game - Bevy ECS Demo"
description = "A Bevy ECS-based maze game that runs cross-platform including no_std ESP32 targets."
date = "2025-05-27"
tags = ["game", "maze", "bevy", "rust", "no_std"]
mcus = ["esp32-s3"]
boards = [
  { name = "esp32-s3-box-3" },
  { name = "m5stack-atom-s3" },
  { name = "desktop" },
  { name = "wasm" }
]
source_url = "https://github.com/georgik/esp32-spooky-maze-game"
images = ["spooky-maze-preview.png"]
+++

Spooky Maze is a Bevy ECS-based game built in Rust with support for `no_std` embedded targets and desktop.

A ghost navigates a maze collecting coins while avoiding enemies. Events are used to abstract hardware-specific inputs from core logic, supporting modular embedded gameplay.

Special items like dynamite and the walker power-up introduce strategic depth.

