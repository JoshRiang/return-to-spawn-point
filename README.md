# Return To Spawn Point

A FiveM and RedM resource for GTA V that lets players save their current position as a spawn point and instantly return to it later.

![Return To Spawn Point](https://user-images.githubusercontent.com/placeholder/return-to-spawn.png)

## Features

- **Save Spawn Point** - Mark your current position with a chat command or keybind
- **Instant Teleport** - Return to your saved spawn point quickly
- **Vehicle Handling** - Teleports with your vehicle if you're driving
- **Custom Keybinds** - Set custom keys for setspawn and return commands
- **Notifications** - In-game notifications for actions and errors

## Commands

| Command | Description |
|---------|-------------|
| `/setspawn` | Save current position as spawn point |
| `/r` | Return to saved spawn point |
| `/deletecoords` | Delete saved spawn point |

## Keybinds

Default keybinds (configurable in `client.lua`):
- `J` - Set spawn point
- `K` - Return to spawn point

## Installation

1. Place this resource in your FiveM resources folder
2. Add to your `server.cfg`:
   ```
   ensure return-to-spawn-point
   ```
3. Restart your FiveM server

## Configuration

Edit `client.lua` to change:
- Keybinds (line 2)
- Notification colors and messages

## File Structure

```
├── fxmanifest.lua  # Resource manifest
├── client.lua      # Client-side script
├── README.md       # Documentation
└── LICENSE         # License file
```

## Requirements

- FiveM or RedM build 5078 or later
- FXServer (artifact 3095+)

## Credits

- Notification system courtesy of jamesbron
- Spawn point system by Joshhh#5048

## License

MIT License