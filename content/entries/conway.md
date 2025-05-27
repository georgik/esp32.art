+++
title = "Conway's Game of Life - Rust Embedded"
description = "Rust bare-metal implementation of Conway's Game of Life for multiple ESP32 boards."
date = "2025-05-27"
tags = ["demo", "game-of-life", "rust", "no_std"]
mcus = ["esp32-c3", "esp32-c6", "esp32-s3"]
boards = [
    "esp32-c3-lcdkit",
    "esp32-c6-waveshare-1_47",
    "esp32-s3-box-3-minimal",
    "esp32-s3-box-3",
    "esp32-s3-lcd-ev-board",
    "esp32-wrover-kit",
    "desktop",
    "wasm"
]
source_url = "https://github.com/georgik/esp32-conways-game-of-life-rs"
images = ["conway-preview.png"]
+++

This Rust bare-metal implementation demonstrates Conway's Game of Life on multiple ESP32 boards using `no_std`. It supports a shared game core that runs across desktop, embedded targets, and even WebAssembly (wasm).

Each tick computes the next generation of the board while rendering through embedded-friendly backends.