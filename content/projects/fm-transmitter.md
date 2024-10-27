+++
author = "Nahid"
title = "FM Transmitter"
date = "2024-10-27"
description = "ESP32 based FM transmitter for my car."
tags = [
    "esp32",
    "fm",
    "electronics",
]
github = "https://github.com/n-delic/ESP32-FM-Transmitter"
+++

#### Github link
https://github.com/n-delic/ESP32-FM-Transmitter

## Introduction

After my aftermarket Android car radio failed, I decided to simplify things and reinstalled the original VW RCD 310 radio in my car. To stream music, I relied on an FM transmitter. However, as someone who enjoys discovering new music through random playlists, I found the lack of song titles displayed on the radio frustrating. My current FM transmitter doesn’t support showing track information. After learning that the Radio Data System (RDS) feature is available on FM radio, I decided to take matters into my own hands and build a custom ESP32-based FM transmitter that could transmit both audio and song details.