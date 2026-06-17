# air-traffic widget for Tesserae

Flights currently overhead at your location via the [OpenSky Network](https://opensky-network.org/) public API. Shows the total count plus the nearest N flights with callsign, origin country, altitude, and speed. No API key.

Set the cell's `latitude` / `longitude` once and the widget polls OpenSky's `states/all` endpoint within the configured radius.

Install via Settings → Widgets → Browse community widgets on [Tesserae](https://github.com/dmellok/tesserae).

## Folders shipped

- `sky_air_traffic`

Previously bundled in [`tesserae-sky`](https://github.com/dmellok/tesserae-sky); carved into its own repo for v0.1.2+ so users who only want flights don't have to pull the rest of the sky bundle.

## License

AGPL-3.0-or-later. See [LICENSE](./LICENSE).
