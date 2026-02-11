# Changelog

All notable changes to Weather Sound.

## [1.1.0] - 2025-02-10

### Added
- CHANGELOG.md to track project changes
- Verified geolocation and weather API integration

### Features Working
- Geolocation-based weather detection
- Open-Meteo API for weather data (free, no key needed)
- Nominatim for reverse geocoding (location name)
- 9 ambient sounds: Rain, Thunder, Wind, Birds, Crickets, Ocean, Fire, Forest, Snow
- Play/pause/skip controls
- Volume slider
- Dynamic background based on weather
- Audio visualizer bars
- Sound picker to manually select sounds

### Auto-Sound Selection Logic
- Thunderstorm → Thunder
- Snow → Snow  
- Rain → Rain
- Fog → Forest
- Windy (>20km/h) → Wind
- Night → Crickets
- Clear day → Birds
- Cloudy → Wind

### Technical Notes
- Uses Web Audio API for sound generation
- Synthesized sounds (not audio files)
- No data stored locally

## [1.0.0] - 2025-02-03

### Initial Release
- Weather-based ambient sound player
- Location-aware sound selection
- Multiple sound options
