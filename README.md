# VDA Serial Profiles

Community serial device profiles for [VDA IR Control](https://github.com/vda-solutions/vda-ir-control).

These profiles define serial command sets for devices controllable over RS-232/RS-485 (projectors, HDMI matrices, etc.) and can be synced directly into your Home Assistant instance via the VDA IR Control integration.

## Usage

Profiles are synced automatically via the VDA IR Control admin card. To manually use a profile:

1. Open the VDA IR Control Admin Card in Home Assistant
2. Navigate to **Serial Devices → Community Profiles**
3. Sync and apply the desired profile to your serial device

## Profile Format

Each profile is a JSON file with the serial command set for a specific device model. See the [VDA IR Control documentation](https://github.com/vda-solutions/vda-ir-control) for the full schema.

## Contributing

Submit a pull request with a new JSON profile file in the appropriate category directory. Include manufacturer, model, and baud rate in the filename and profile metadata.

## License

These profiles are provided as-is for personal use.

---

**VDA Solutions LLC** — [info@vdasolutionsny.com](mailto:info@vdasolutionsny.com)
