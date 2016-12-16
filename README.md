# Customizations of ConEmu with clinks

If you want to stick with `cmd.exe` on windows, [ConEmu](https://conemu.github.io/) is probably the best terminal for it.
If you combine it with [Clink](https://mridgers.github.io/clink/), you can also improve `cmd.exe` completion and get something quite usable.

This repo includes my own customizations for both of those tools.

- `ConEmu.xml`
  <br>**ConEmu settings:**
  - (Main) Sets the font to `Consolas` and `Yasashisa Antique` for CJK
  - (Main/Tab bar) Disables tabs
  - (Startup/Tasks) Default directories (`i:\` by default, desktop)
  - (Startup/Environment) Custom prompt and aliases
  - (Features/Colors) Colors
  - (Features/Status bar) Status bar customization
  - ...
  
- `clink/clink.lua`
  <br>**Autocomplete customization:**
  - ssh/(s)ftp
  - gradle(w)
  
- `clink/profile/settings`
  <br>**Clink settings**

