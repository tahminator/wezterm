# Wezterm

This is my config for Wezterm, a cross platform terminal, which includes a lot of sane defaults + nice manual color scheme (oxocarbon).

The main purpose of the repository is so that I can simply clone my config anywhere and get to work as needed, but feel free to look around!

## Instructions

- ### MacOS

  1. Make a copy of your wezterm config, if you have it installed.

  ```bash
  mv ~/.config/wezterm{,.bak}

  # or if you use ~/.wezterm.lua
  mv ~/.wezterm.lua{,.bak}
  ```

  2. Download wezterm with Homebrew

  ```bash
  brew install --cask wezterm
  ```

  3. Clone repository

  ```bash
  git clone https://github.com/tahminator/wezterm ~/.config/wezterm
  ```

  4. [Optional] - Delete the .git folder so you can track the changes in your own repository.

  ```bash
  rm -rf ~/.config/wezterm/.git
  ```

  5. Open Wezterm via Spotlight Search or the `Applications` folder.

- ### Windows

  1. Make a copy of your wezterm config, if you have it installed.

  ```powershell
  Move-Item $env:USERPROFILE\.config\wezterm $env:USERPROFILE\.config\wezterm.bak

  # if you are using .wezterm.lua instead:
  Move-Item $env:USERPROFILE\.wezterm.lua $env:USERPROFILE\.wezterm.lua.bak
  ```

  2. Download Wezterm with WinGet

  ```powershell
  winget install wez.wezterm
  ```

  3.  Clone repository

  ```powershell
  git clone https://github.com/tahminator/wezterm $env:USERPROFILE\.config/wezterm
  ```

  4. [Optional] - Delete the .git folder so you can track the changes in your own repository.

  ```powershell
  Remove-Item $env:USERPROFILE\.config\wezterm\.git -Recursive -Force
  ```

  5. Open Wezterm via the Windows Start Menu.
