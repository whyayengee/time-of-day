# Time of Day

An interactive visualization component that displays the time of day with a playful grid representing sunlight and starlight.

## Features

- **Real-time data**: Automatically detects your location, timezone, and fetches live weather/temperature
- **Animated grid**: Visual representation of sunlight during day, twinkling stars at night
- **Smooth transitions**: Seamless color and visual changes between dawn, day, dusk, and night
- **Interactive controls**: Drag the slider to explore different times, or let it autoplay
- **Keyboard shortcuts**: Press `Space` to pause/resume autoplay

## Demo

[View Live Demo](https://whyayengee.github.io/time-of-day/time-of-day.html)

## Usage

Simply open `time-of-day.html` in a browser. The component will:

1. Detect your current local time and set the display accordingly
2. Request location permission to show your city name
3. Fetch real weather data for accurate temperature display

If location access is denied, it falls back to default values.

## Time Phases

| Phase | Time | Visual |
|-------|------|--------|
| Night | 12am - 5am | Twinkling stars on dark grid |
| Dawn | 5am - 6am | Stars fade, first light appears |
| Sunrise | 6am - 8am | Sun rises from horizon |
| Morning | 8am - 10am | Bright, warm light spreads |
| Midday | 10am - 12pm | Full daylight |
| Noon | 12pm - 2pm | Sun at peak, buzzing rays |
| Afternoon | 2pm - 4pm | Warm afternoon glow |
| Golden Hour | 4pm - 6pm | Rich golden light |
| Sunset | 6pm - 7pm | Sun descends |
| Dusk | 7pm - 8pm | Light fades, stars appear |
| Night | 8pm - 12am | Full starry sky |

## License

MIT
