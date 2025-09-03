## Deploying Rust UIs to the Terminal (and to your pocket) 🐭🎛️

Ratatui is a Rust library for building powerful terminal user interfaces. While TUIs are typically bound to the desktop, Ratatui's new no_std support makes it possible to run them on embedded devices too. Join me in this talk to see what cool stuff you can build with Ratatui and learn how to deploy Rust UIs, from terminals to tiny screens!

### Abstract

UI development in Rust is gaining traction with the emergence of new libraries, and Ratatui is leading the way in terminal UI development. However, we didn't want to stop at /dev/tty and wanted to bring terminal aesthetics to other platforms as well. One of the most fitting use cases was running Ratatui on embedded systems and with the recently introduced no_std support, this is now possible!

In this talk, we'll walk through the full lifecycle of a TUI: building it for the desktop, adapting it for embedded, and finally deploying it to real hardware using Rust’s powerful cross-compilation toolchain. There will be a live demo of flashing and running a Ratatui-powered UI on an ESP32 microcontroller. Attendees will gain hands-on insight into building portable UIs and learn directly from the maintainer of Ratatui and walk away with cheesefull amount of inspiration ✨🧀

## Presenting

To start the presentation, first install [presenterm](https://github.com/mfontanini/presenterm):

```bash
cargo install presenterm
```

Then simply run:

```bash
presenterm presentation.md -X -c config/presenterm.yml -p
```

> [!IMPORTANT]  
> It is recommended to use [wezterm](https://github.com/wez/wezterm) for good image rendering. The configuration file can be found in [`config/wezterm.lua`](./config/wezterm.lua).

> [!TIP]  
> Run the [`present.sh`](./present.sh) script to present with the recommended tools and configuration.
