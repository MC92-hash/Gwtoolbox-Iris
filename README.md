# Iris

**More insight. Right inside Guild Wars.**

Iris is a module for [GWToolbox++](https://www.gwtoolbox.com) that brings extra match information directly into
Guild Wars Observer Mode. Enjoy watching matches in game? Iris adds HUD panels that help you follow the action,
without needing to open GW Observer.

![Iris in Guild Wars Observer Mode](iris-screenshot.png)

## How it works

GW Observer records matches. Iris uses data from those recordings and synchronizes it with the match you're
observing inside Guild Wars. When recording data is available for your match, Iris can display additional
information about players, skills, energy and effects alongside the action.

## What you need

- Guild Wars, watching a match in Observer Mode.
- The latest version of GWToolbox++.
- The Iris module: `Iris.dll` from this repository.
- Available GW Observer recording data for the synchronized match information.

You do not need to install or run GW Observer.

## Installation

1. Close Guild Wars.
2. Download `Iris.dll` from this repository.
3. Put it in your GWToolbox++ plugins folder: `Documents\GWToolboxpp\<your computer name>\plugins\`.
4. Start Guild Wars with GWToolbox++ and observe a match.
5. Tick **Iris** under Auto Camera / Hide UI to open the IRIS Options window.

## A note about accuracy

Energy values and effects shown by Iris are calculated from match events, rather than directly recorded. They may
contain errors or differ from the actual game state. Treat them as a guide, rather than exact values.

Plugins are not supported by the GWToolbox++ developers, and are not permitted by ArenaNet. Use at your own risk.

---

Purif & Maverick
