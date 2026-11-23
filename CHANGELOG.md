# Changelog

## 2026-11-23

### Fixed
- Leak alert: the trigger had `from: "off"`, so a sensor going `unavailable` → `on` (low battery, Zigbee blip) raised no alarm during a real leak.

### Changed
- TTS uses `tts.speak` with a selectable TTS engine (Home Assistant Cloud by default), so Piper and other engines work. Speakers picked by area or device are supported.
- Modern syntax (`triggers`/`actions`/`action`), `source_url` and `min_version: 2024.10.0`.
- Re-import the blueprint in Home Assistant to get the update.
