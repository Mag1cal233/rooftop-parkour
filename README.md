# Rooftop Parkour — English Edition

A Windows first-person parkour prototype set around Wembley, HA9. Cross the rooftops and reach the station.

**[Download the Windows game](https://github.com/Mag1cal233/rooftop-parkour/releases/latest)**

Download `Rooftop-Parkour-English-Windows.zip` from the release's **Assets**, extract the whole archive, then double-click **Play.bat**. Keep the `Windows` folder and its contents together. Unreal Engine is not required to play.

## Controls

| Key | Action |
| --- | --- |
| W A S D | Move |
| Mouse | Look |
| Left Shift | Sprint |
| Space | Jump |
| E | Vault or climb; jump first for higher ledges |
| Left Ctrl | Crouch |
| Esc | Pause / resume |
| R | Restart the entire run from the beginning |
| M | Open local records while paused or on the results screen |
| Alt + F4 | Quit |

The timer starts when you move. Pass checkpoints in order. Falling returns you to the last checkpoint. When out of stamina, recover to the marked threshold before sprinting again.

**R resets the entire run and its timer.** If you get stuck against a wall or step, keep pushing towards it without moving sideways for about 10 seconds to trigger checkpoint recovery.

## English edition

The HUD, countdown, stamina messages, checkpoint prompts, pause text, results, leaderboard and record-management menus are in English. The package includes English controls and launch instructions. Route geometry, movement rules and artwork are taken from the existing project.

This is a development prototype, with unfinished scenery and narrow recovery ledges in some places. It is not a surveyed reconstruction of Wembley. Local records are stored on your PC; automated demonstration runs do not count as personal bests.

The repository hosts distribution documentation and the localisation change. The playable Windows game is attached to Releases. Unreal Engine and uncooked third-party assets are not distributed as source here.

## Runtime

Windows 64-bit, keyboard and mouse, with a DirectX-capable graphics driver. The build uses Unreal Engine 5.8. Hardware minimums have not been established.

If Windows reports a missing Microsoft Visual C++ runtime, use Microsoft's [supported Visual C++ redistributable](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist).

Checksums and validation details are included with each release.
