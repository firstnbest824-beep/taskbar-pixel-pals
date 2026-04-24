# Taskbar Pixel Pals

Taskbar Pixel Pals is a small Windows desktop companion that places animated pixel animals on your taskbar.

It is built for a light, playful desktop feel without turning into a full widget platform.

## Links

- Product page: [firbe-labs.netlify.app/products/taskbar-pixel-pals](https://firbe-labs.netlify.app/products/taskbar-pixel-pals/)
- Latest release: [GitHub Releases](https://github.com/firstnbest824-beep/taskbar-pixel-pals/releases/latest)

## What It Does

Taskbar Pixel Pals watches taskbar hover and preview states, then places a tiny animated character so it feels like the character is reacting to your desktop.

Current MVP includes:

- 4 characters: `Cow`, `Penguin`, `Duck`, `Dog`
- 3 motion profiles: `Calm`, `Playful`, `Bouncy`
- 3 size presets: `Small`, `Medium`, `Large`
- Hover position adjustment
- Preview hover position adjustment
- Randomize character per icon
- Randomize motion per icon
- Fullscreen suppression option
- Local settings persistence

## Download

The latest release includes three download options.

| File | Recommended for | Notes |
| --- | --- | --- |
| `TaskbarPixelPalsSetup.exe` | Most users | Recommended. Installs the app, creates a Start menu entry, and adds uninstall support. |
| `TaskbarPixelPals.U2OverlaySpike.exe` | Portable use | Raw executable with no installer. |
| `taskbar-pixel-pals-windows-x64.zip` | Manual extraction | Portable ZIP build. |

## Installation

### Recommended: Setup EXE

1. Open the [latest release page](https://github.com/firstnbest824-beep/taskbar-pixel-pals/releases/latest).
2. Download `TaskbarPixelPalsSetup.exe`.
3. Run the installer.
4. Launch `Taskbar Pixel Pals` from the Start menu after install.

The current installer:

- installs to your local app directory
- can create a desktop shortcut
- creates an uninstall entry
- can launch the app right after installation

### Portable EXE

If you do not want installation:

1. Download `TaskbarPixelPals.U2OverlaySpike.exe` from the latest release.
2. Place it anywhere you want.
3. Run it directly.

### ZIP Build

If you prefer a packaged portable build:

1. Download `taskbar-pixel-pals-windows-x64.zip`.
2. Extract it.
3. Run the executable inside the extracted folder.

## First Run

On first run, Windows may show a SmartScreen warning because this is an indie desktop app.

If that happens:

1. Click `More info`
2. Click `Run anyway`

## How To Use

### 1. Launch the app

Start Taskbar Pixel Pals.

The app opens a settings window and starts the overlay behavior.

### 2. Choose a character

You can pick one fixed character:

- `Cow`
- `Penguin`
- `Duck`
- `Dog`

Or enable random character selection per taskbar icon.

### 3. Choose a motion profile

You can tune the behavior style with:

- `Calm`
- `Playful`
- `Bouncy`

Or enable random motion selection per icon.

### 4. Choose a size

Available scale presets are:

- `Small` -> `112`
- `Medium` -> `128`
- `Large` -> `160`

### 5. Adjust taskbar alignment if needed

Depending on display scale, taskbar layout, preview shape, and system setup, the character may need a small manual position correction.

You can adjust:

- `Hover position X/Y`
- `Preview hover position X/Y`

Notes:

- `Hover` controls the normal taskbar icon hover position.
- `Preview` controls the perched position when a preview pops up.
- In the current UI, negative `Y` values move the character downward.

### 6. Fullscreen suppression

If enabled, the overlay hides itself while fullscreen content is active.

This is useful when you do not want the character to appear during games, video playback, or fullscreen work.

### 7. Apply your settings

Click `Apply` to save the current configuration.

The current build saves settings locally and minimizes the settings window after applying.

## Where Settings Are Stored

Taskbar Pixel Pals stores settings locally at:

`%LOCALAPPDATA%\FirbeLabs\TaskbarPixelPals\settings.json`

## Privacy

Taskbar Pixel Pals works locally on your machine.

- No sign-in
- No account
- No cloud sync
- No upload of desktop content

It uses taskbar hover and preview state only to place the overlay correctly.

## Current Status

This is the first public MVP release.

The current focus is:

- character feel
- perched preview placement
- lightweight desktop utility behavior
- quick local customization

## Troubleshooting

### The character feels slightly too high or too low

Use `Hover position Y` or `Preview hover position Y` in settings until it lines up better with your taskbar.

### The preview pose looks slightly off for your system

Use `Preview hover position X/Y` to fine-tune the perched alignment.

### Nothing appears while a fullscreen app is open

Check whether `Fullscreen suppression` is enabled.

## Firbe Labs

Taskbar Pixel Pals is made by [Firbe Labs](https://firbe-labs.netlify.app/).

For updates and release notes:

- [Product page](https://firbe-labs.netlify.app/products/taskbar-pixel-pals/)
- [Releases](https://github.com/firstnbest824-beep/taskbar-pixel-pals/releases)
