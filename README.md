# FoloToy AI Passport — Weekly Meals V1

This repository builds a Chinese 7-day / 3-meal planner for FoloToy AI Passport (ESP32-C3, 8 MiB flash, 240×320 ST7789P3).

This is an ESP-IDF firmware project, not MicroPython. The workflow must compile and verify the merged full-flash `.bin` before it can be used in PassportSim.

The source is bundled in `weekly-meals-source.tar.xz`; the GitHub Actions workflow extracts it into the checkout and overlays the `main/` files onto the official `FoloToy/ai-passport` BSP.

**Do not flash any unverified firmware to a real device.**
