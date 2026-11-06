# SiteWatch

One dashboard for wireless LoRaWAN temperature, corrosion (ISA-71.04) and gas sensors.
Runs on your own Windows PC and your own network. No cloud, no subscription. Developed by Syon Automation LLC.

**Download:** [SiteWatch-Setup-3.10.0.exe](https://syonautomation.com/download/SiteWatch-Setup-3.10.0.exe) (free 14-day trial, every feature)
· Product page and licenses: https://syonautomation.com/sitewatch.html

## Proof of concept: a real installation

SiteWatch 3.10 was filmed on a real site, not demo data: one Dragino D22-LB sensor with two probes in a garage, 11 ft from a Dragino LoRaWAN gateway, reporting every 5 minutes since Oct 30, 2026.
When that gateway lost its server for two days, the sensor kept its readings, SiteWatch recovered them, and the signal graph shows exactly when the link was down.

Video: https://syonautomation.com/sitewatch.html#watch

## What it does

- **Every sensor on one screen**: live readings, alarms, uptime, signal health and the gateway itself.
- **Built-in LoRaWAN network server**: any gateway that speaks Semtech UDP (Dragino, RAK, Milesight and others) sends straight to SiteWatch. ADFweb HD67F25 (EtherNet/IP) and Modbus sources are supported too.
- **Gateway signal levels (new in 3.10)**: what the concentrator hears: RSSI, SNR, link margin, noise floor, damaged packets, channels in use, and a 24-hour chart, kept for 7 days.
- **Distance to the gateway (new in 3.10)**: an estimate for every sensor from its signal strength, with a "safe up to" range. One tape-measure reading ("I measured it") calibrates the whole site; a second reading also measures how the site absorbs signal.
- **Floor plans with range rings (new in 3.10)**: live sensors pulse with rings coloured by distance (blue closest, red farthest), with distance, signal, battery and last report under each name.
- **Phone app (new in 3.10)**: open SiteWatch on any phone on your network and add it to the Home Screen; it opens full screen like an app, laid out for phone screens.
- **Trends**: day, week, month and year, saved automatically, with PDF reports for any time range.
- **Alerts**: signal lost, no gateway, high/low limits, gas, corrosion class, weak signal, missed reports, low battery, sensor faults, calibration due. Sent as a Windows pop-up, e-mail, text (e-mail to text) or free phone push (ntfy).
- **Sensor records**: function, calibration required, installed date, calibration due date with a reminder one week before.
- **Screen settings follow your data**: marker sizes, colours and calibration are saved with SiteWatch's data, so updates keep them.

## Requirements

Windows 10 or 11 (64-bit). Google Chrome is used for the SiteWatch window. A LoRaWAN gateway on the same network (US915 tested).

## Range guidance

Calibrated against the proof-of-concept hardware (stock antennas), the safe range with a 20 dB margin is about 1,300 to 1,900 ft (roughly a quarter mile) through a typical plant. Open yards and roof-mounted gateways reach farther. Every installation can check its own figure live in SiteWatch: Gateway > Network server > Each sensor through this gateway.

## Versions

See [CHANGELOG.md](CHANGELOG.md). The current installer is on the [product page](https://syonautomation.com/sitewatch.html); older ones are on the [Releases](https://github.com/syon2009/SiteWatch/releases) page.

Copyright 2026 Syon Automation LLC. SiteWatch is commercial software; the installer includes the end user license agreement, privacy statement and third-party notices.
