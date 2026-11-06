# SiteWatch changelog

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
