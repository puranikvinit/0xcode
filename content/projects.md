+++
title = "My Projects"
author = "Vinit Puranik"
description = ""
tags = ["index"]
toc = false
+++

## [rpi5os](https://github.com/puranikvinit/rpi5os)

(C, ARM, Raspberry Pi, Bare Metal Programming)

- A minimalistic kernel written for the Raspberry Pi 5, written in C and ARMv8 assembly.
- Uses ARM PrimeCell PL011 UART (revision r1p5) for serial communication, with a baud rate of 9600 bps.
- Uses the ARM Corelink Generic Interrupt Controller (GIC) - 400 for handling interrupts.
- Uses the BCM2835 ARM System Timer for scheduling and timer ticks in general.
- Implements a basic set of system calls for process management, memory management, and I/O operations.
- Comes with Virtual Memory enabled, for a physical addressable memory of 4GiB, along with the peripheral space.

## [system monitor](https://github.com/puranikvinit/system-monitor)

(C, Linux, Prometheus, Grafana, Valgrind)

- An intuitive Linux-based System Resource Monitor to view various system statistics to the user.
- Scrapes the `/proc` Virtual File System to collect the CPU usage metrics in real-time.
- Multi-threaded application, with a separate thread for watchdog functionality.
- Exposes the scraped metrics to a socket, following the OpenMetrics Standard of metrics exposition.
- Setup a Prometheus server to scrape the metrics and a Grafana dashboard to visualize the metrics.
- Used Valgrind to detect memory leaks and other memory-related errors in the code.

## solmelu

(Dart, Flutter, OpenStreetMaps, MapBox)

- A platform for seamless travel in Dakshina Kannada and Udupi regions, aiding curation and execution.
- Designed a high-level system architecture, database ER diagram, and application feature list.
- Creating a custom-curated travel path with OpenStreetMaps and MapBox SDK and API for Flutter’s map-based UI.
- Setup frontend interface for searching activities, trips and places on the map.
