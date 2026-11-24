# LEO SIM

A low Earth orbit launch simulator that runs in a single HTML file. Pick a launch site on the globe, fire a ballistic shot or a two-burn rocket, and watch it climb through the atmosphere into orbit.

**Live demo:** https://orbit.hawxaerospace.workers.dev/

## Features
- Real atmosphere model (USSA-76) with Mach-dependent drag
- Nose heating, shock cone and plasma effects
- Ballistic mode with selectable body materials
- Rocket mode with two burns, stage separation and a satellite model
- Telemetry: altitude, speed, Mach, pressure, apoapsis, periapsis, inclination
- Inertial and Earth-fixed reference frames, time warp, follow camera
- Turkish and English interface

## Running locally
Open `index.html` in a browser. It loads three.js and map data from a CDN, so an internet connection is needed.

## Notes
This is an educational simulation. Vehicle mass is constant and the separated lower stage has no drag, so it is not suitable for real mission planning.
On first visit the app may ask a public service (ipapi.co) for your country to pick the interface language.

## Credits
- [three.js](https://threejs.org/) (MIT)
- [Natural Earth](https://www.naturalearthdata.com/) map data (public domain)
- Built together with Claude (Anthropic)

## License
MIT
