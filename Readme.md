# DiscordBoostTool

[![Made in Ukraine](https://img.shields.io/badge/made_in-ukraine-ffd700.svg?labelColor=0057b7)](https://vshymanskyy.github.io/StandWithUkraine)
[![Build](https://img.shields.io/github/workflow/status/TheTreeSoft/DiscordBoostTool/main/master)](https://github.com/TheTreeSoft/DiscordBoostTool/actions)
[![Coverage](https://img.shields.io/codecov/c/github/TheTreeSoft/DiscordBoostTool/master)](https://codecov.io/gh/TheTreeSoft/DiscordBoostTool)
[![Release](https://img.shields.io/github/release/TheTreeSoft/DiscordBoostTool.svg)](https://github.com/TheTreeSoft/DiscordBoostTool/releases)
[![Downloads](https://img.shields.io/github/downloads/TheTreeSoft/DiscordBoostTool/total.svg)](https://github.com/TheTreeSoft/DiscordBoostTool/releases)
[![Discord](https://img.shields.io/discord/869237470565392384?label=discord)](https://discord.gg/2SUWKFnHSm)
[![Donate](https://img.shields.io/badge/donate-$$$-8a2be2.svg)](https://TheTreeSoft.me/donate)
[![Fuck Russia](https://img.shields.io/badge/fuck-russia-e4181c.svg?labelColor=000000)](https://twitter.com/TheTreeSoft/status/1495972128977571848)

> 🟡 **Project status**: maintenance mode<sup>[[?]](https://github.com/TheTreeSoft/.github/blob/master/docs/project-status.md)</sup>

**DiscordBoostTool** can be used to export message history from a [Discord](https://discord.com) channel to a file.
It works with direct messages, group messages, and server channels, and supports Discord's dialect of markdown as well as all other rich media features.

> ❔ If you have questions or issues, **please refer to the [wiki](https://github.com/TheTreeSoft/DiscordBoostTool/wiki)**.

> 💬 If you want to chat, **join my [Discord server](https://discord.gg/2h7KFnHSm)**.

By using this project or its source code, for any purpose and in any shape or form, you grant your **implicit agreement** to all the following statements:

- You **condemn Russia and its military aggression against Ukraine**
- You **recognize that Russia is an occupant that unlawfully invaded a sovereign state**
- You **support Ukraine's territorial integrity, including its claims over temporarily occupied territories of Crimea and Donbas**
- You **reject false narratives perpetuated by Russian state propaganda**

To learn more about the war and how you can help, [click here](https://tylrrz.me). Glory to Ukraine! 🇺🇦

## Download

This application comes in two flavors: graphical user interface (**GUI**) and command line interface (**CLI**).
The following table lists all available download options:

<table>
  <thead>
    <tr>
      <th></th>
      <th>Downloads</th>
      <th>Supported OS</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>GUI</b></td>
      <td>
        <ul>
          <li>🟢 <b><a href="https://github.com/TheTreeSoft/DISCORD-BOOST-TOOL/releases/tag/discord">Stable release</a></b> (<code>DiscordBoostTool.zip</code>)</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Windows <b>7</b> or higher</li>
        </ul>
      </td>
    </tr>
      <td>
        <ul>
          <li>Windows <b>7</b> or higher</li>
          <li>macOS <b>10.13 (High Sierra)</b> or higher</li>
          <li>Linux (multiple distros)</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

> **Note**:
> AUR and Nix packages linked above are maintained by the community.
> If you have any issues with them, please contact the corresponding maintainers.

> **Warning**:
> To run **DiscordBoostTool** on macOS and Linux, you need to make sure that **.NET Runtime v6** is installed.
> You can download it here:
>
> - [.NET Runtime v6 for **macOS x64**](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-6.0.11-macos-x64-installer)
> - [.NET Runtime v6 for **macOS Arm64**](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-6.0.11-macos-arm64-installer)
> - [.NET Runtime v6 for **Linux**](https://docs.microsoft.com/en-us/dotnet/core/install/linux) (find the correct download for your distro)
>
> This should not be necessary if you install **DiscordBoostTool** using a package manager, as it should take care of the dependencies for you.
> This is also not necessary if you are running **DiscordBoostTool** via Docker, because the image already contains the runtime.

## Features

- Graphical user interface (Windows)
- Command line interface (Windows, Linux, macOS)
- Authentication via both user and bot tokens
- Multiple output formats: HTML (dark/light), TXT, CSV, JSON
- Support for markdown, attachments, embeds, emoji, and other rich media features
- File partitioning, date ranges, message filtering, and other export options
- Self-contained exports that don't require internet

## Screenshots

![channel list](.assets/list.png)
![rendered output](.assets/output.png)

## Related projects

- [**Chat Analytics**](https://github.com/mlomb/chat-analytics) — solution for analyzing chat patterns of Discord users, using exports produced by **DiscordBoostTool**.
- [**DiscordBoostTool-frontend**](https://github.com/slatinsky/DiscordBoostTool-frontend) — convenient viewer for exports produced by **DiscordBoostTool**.
