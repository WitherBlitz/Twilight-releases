# Twilight releases

Installers for **Twilight**, a multi-seat remote desktop for Windows built on
Sunshine/Apollo and Moonlight: up to 10 people stream the same PC at once, each
with their own cursor, keyboard and desktop.

Download from the [latest release](https://github.com/WitherBlitz/Twilight-releases/releases/latest):

| File | Install it on |
|---|---|
| `TwilightHostSetup.exe` | The PC you stream **from**. Asks for administrator rights. Installs Sunshine and Apollo too if they're missing. |
| `TwilightClientSetup.exe` | Each device you connect **from**. No administrator rights needed. |

Once installed, both keep themselves up to date from this repo's releases:
the host checks once a day (01:00 by default, changeable on its dashboard at
http://127.0.0.1:47902) and the client checks while it's open (Settings > App).
Every download is checked against the SHA-256 GitHub publishes for it.

This repo only holds release files; the source code is private.
