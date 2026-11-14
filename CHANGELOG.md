# SiteWatch changelog

## 3.10.4 (2026-11-14)
- Fix: in 3.10.3 the main page could not load ("App not reachable", empty sensor list) while a LoRaWAN gateway was connected. Data kept recording; only the screen was affected. 3.10.3 was withdrawn.

## 3.10.3 (2026-11-14)
- Radar tab: gateway in the centre, sensors on rings at their distance (range colours, pulsing when live, grey when offline); drag to set each sensor's real direction (remembered), Reset directions, optional sweep and safe-range ring; log ring spacing and name-only labels on large sites.
- Devices that aren't yours: a sensor's join requests show under its name once added; other devices the gateway hears go to a collapsed "Other devices heard (not yours)" list with Hide; the Gateway tile and worst-link rating use only your sensors.
- Installer and MSI code-signed.

## 3.10.2 (2026-11-13)
- Free trial: 14 days, every feature, up to 2 live sensors (demo mode still shows 60).
- License window: sensor packs of 10 and tier upgrades, with a link to add sensors; + Add sensor at the license limit opens the license window.
- Installer and MSI code-signed.

## 3.10.1 (2026-11-13)
- "+ Add sensor" button on the Sensors toolbar and on an empty Sensors page: opens a new sensor entry with numbered steps, or the sensors already asking to join.
- The owner license no longer shows a license pill in the top bar.
- Installer and MSI code-signed.

## 3.10.0 (2026-11-06)
- Phone app: SiteWatch can be added to a phone's Home Screen and opens full screen (manifest, app icons), with a layout for phone screens (scrolling tabs, 2-column tiles, full-screen windows, scrollable tables).
- Gateway signal levels: RSSI, SNR, link margin and rating, noise floor, damaged packets (CRC), gateway status report, 24-hour RSSI/SNR chart, per-sensor and per-channel tables; 7 days of history kept and rebuilt from saved reports on first start. Main page "Gateway" tile.
- Distance to the gateway: estimate and "safe up to" range for every sensor (sensor tile, sensor window, gateway tables, floor plan, Trends graph and table). Tape-measure calibration ("I measured it"); two readings also measure the site's path-loss factor. Steadier: uses the middle value of the last hour.
- Floor plans: pulsing range rings for live sensors coloured by distance (blue closest to red farthest), Details lines (distance, signal, battery, last report), Range rings and Details switches, colour legend.
- Web address shown in the top bar and footer, with copy buttons for this PC, other PCs and phones, and PC name.
- Version number shown in the header, footer and all 5 splash screens.
- Screen settings (marker size, colours, calibration) are saved with SiteWatch's data so updates keep them.
- Fixes: a sensor that goes quiet stays on screen marked OFFLINE instead of disappearing; alarm setpoint boxes no longer reset while you type; installer pages are dark with readable check boxes; installer waits for Windows to release the old program file.

## 3.9.0 (2026-11-03)
- Trends (day, week, month, year) with automatic history, PDF reports by time range, alerts with Windows, e-mail, phone push and webhook notifications, and sensor records with calibration reminders.
- Installs to Program Files with data in C:\ProgramData\SiteWatch; moves an older per-user install across automatically.

## 3.1.1 (2026-10-21)
- Renamed from SY SiteWatch to SiteWatch; signed installer.
