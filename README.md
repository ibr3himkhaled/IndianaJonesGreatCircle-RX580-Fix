<div align="center">

# Indiana Jones and the Great Circle
## AMD Radeon RX 580 Compatibility Fix

**A community-developed graphics compatibility project for AMD Polaris GPUs.**

![GPU](https://img.shields.io/badge/GPU-AMD_RX_580-ED1C24?style=for-the-badge&logo=amd&logoColor=white)
![API](https://img.shields.io/badge/Graphics-Compatibility_Fix-0078D6?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![Distribution](https://img.shields.io/badge/Distribution-Windows_Installer-6F42C1?style=for-the-badge)
![Target](https://img.shields.io/badge/Target-AMD_Polaris-ED1C24?style=for-the-badge)

**Developed and tested primarily on the AMD Radeon RX 580 8GB.**

[⬇️ Download the Fix](../../releases/latest) · [Report an Issue](../../issues)

---

## ❤️ Support My Work

Hi, I'm **Ibrahim Khaled**, an independent developer working on compatibility fixes that help older AMD graphics cards run modern games.

Developing these projects involves graphics API investigation, shader analysis, debugging, compatibility research, and repeated testing.

If this project has been useful to you, please consider supporting the development of future fixes.

### ☕ Support Development

[![GitHub Sponsors](https://img.shields.io/badge/GitHub-Sponsor-EA4AAA?style=for-the-badge&logo=githubsponsors&logoColor=white)](https://github.com/sponsors/ibr3himkhaled)

[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support_Me-FF5E5B?style=for-the-badge&logo=kofi&logoColor=white)](https://ko-fi.com/ibr3himkhaled)

[![Buy Me a Coffee](https://img.shields.io/badge/Buy_Me_a_Coffee-Support-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black)](https://buymeacoffee.com/ibr3himkhap)

[![PayPal](https://img.shields.io/badge/PayPal-Donate-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/IbrahimKhaled011)

**All donations are optional. The compatibility fix is intended to remain free.**

Your support helps fund continued research, development, debugging, and compatibility testing for older GPUs.

**Thank you for supporting independent development!**

</div>

---

## Overview

This project provides a custom compatibility solution for **Indiana Jones and the Great Circle**, targeting the **AMD Radeon RX 580 8GB** and other potentially compatible GPUs based on AMD's Polaris architecture.

The project aims to make the game playable on older AMD hardware that is not officially supported by the game's standard hardware requirements.

The compatibility package includes a dedicated launcher and the required project-specific components intended to work together to start the game on the target hardware.

The fix has been tested on an AMD Radeon RX 580 8GB, achieving a reported performance range of approximately **40–60 FPS with stable performance during the developer's testing sessions**.

Actual performance depends on the game scene, graphics settings, driver version, and system configuration.

> [!IMPORTANT]
> **You must launch the game using `IJGCLauncher.exe` when using this compatibility fix.**
>
> Do not launch the standard game executable directly unless the project's release documentation explicitly states otherwise.
>
> `IJGCLauncher.exe` is the intended entry point for this compatibility setup.

The RX 580 8GB is the primary development and testing target. Compatibility and performance on other GPUs, drivers, and system configurations may vary.

---

## ⚠️ Supported Game Version

> [!IMPORTANT]
> **The compatibility fix has been tested with a newer version of Indiana Jones and the Great Circle, and the game runs successfully on the developer's RX 580 configuration.**
>
> Unlike compatibility projects that require a specific older game build, this project is intended to work with the game version confirmed in the corresponding fix release.
>
> Game updates may change executable files, shaders, rendering behavior, or other components that affect compatibility.
>
> Compatibility with a future update should not be assumed until it has been tested.
>
> **Check the release notes for the game versions confirmed to work with your installed fix.**
>
> If you encounter a problem after updating the game, include the exact game version or build number when reporting the issue.

### Important Notes

- Do not downgrade the game unnecessarily if your installed version is already confirmed to work with the fix.
- Keep the compatibility files from a single release together.
- Do not assume every future game update will remain compatible.
- Report version-specific problems with enough information to reproduce them.

---

## Features

- Compatibility work targeting AMD Polaris graphics hardware.
- A dedicated `IJGCLauncher.exe` launcher.
- Game-specific compatibility adjustments.
- Compatibility components designed to work together as a single package.
- A Windows installer to simplify installation of the required files.
- Testing focused primarily on the AMD Radeon RX 580 8GB.
- Successful gameplay testing on the target hardware.
- Reported performance of approximately 40–60 FPS during the developer's testing sessions.
- Ongoing investigation into graphics compatibility, performance, and stability.

> Performance depends on the GPU, driver, game version, graphics settings, and scene complexity. The reported 40–60 FPS result is based on the developer's testing configuration and is not a universal FPS guarantee.

---

## Installation

### Step 1 — Download the Installer

Download the latest available installer from the project's GitHub Releases page:

**[⬇️ Download Indiana Jones and the Great Circle — RX 580 Fix](../../releases/latest)**

Use the installer provided for a single release. Do not mix files from different releases or unrelated compatibility projects.

### Step 2 — Install the Fix

1. Make sure the game is installed and is not currently running.
2. Run the downloaded setup file.
3. Follow the installer's instructions.
4. Select the correct game installation directory if prompted.
5. Allow the installer to install the required compatibility components and launcher.
6. Wait for the installation to finish before starting the game.

Keep a backup of important game files before installing any compatibility modification.

Do not manually replace individual DLLs or compatibility files with versions from unrelated projects.

### Step 3 — Start the Game with the Correct Launcher

After installation, locate and run:

```text
IJGCLauncher.exe
```

> [!IMPORTANT]
> **Always start the game through `IJGCLauncher.exe` when using this fix.**
>
> Starting the game's standard executable directly may bypass the intended compatibility startup process and prevent the fix from working correctly.

The launcher is an essential part of the intended startup process for this compatibility setup.

### Step 4 — First Launch

The first launch may take longer than subsequent launches, depending on graphics initialization, shader compilation, and other runtime operations.

Allow the game enough time to start before assuming that it has failed.

If the game does not start, collect the relevant logs and check the troubleshooting section before modifying or deleting files.

---

## Recommended: Install the Game on an SSD

**Installing Indiana Jones and the Great Circle on an SSD is strongly recommended.**

The game uses substantial game assets and can involve frequent asset loading and streaming. Storage performance can influence loading times and asset availability during gameplay.

An SSD is recommended for a smoother overall experience, particularly when dealing with long loading times or delayed asset streaming.

### SSD vs. HDD

| Storage Type | Expected Experience |
|:---|:---|
| SSD | Recommended for faster loading and more responsive asset streaming |
| HDD | May result in longer loading times and delayed asset availability |

### Important Notes

- An SSD is recommended for the best overall experience.
- An HDD may increase loading times and contribute to asset-streaming delays.
- Storage-related delays are separate from graphics compatibility issues.
- An SSD cannot eliminate every source of stuttering or guarantee a particular FPS improvement.

**Recommendation:** Install the game on an SSD whenever possible, especially if you experience long loading times or asset-streaming problems.

---

## Recommended: Lossless Scaling

For users who want to experiment with smoother perceived motion, **Lossless Scaling** is an optional companion application.

[![Lossless Scaling on Steam](https://img.shields.io/badge/Steam-Lossless_Scaling-1B2838?style=for-the-badge&logo=steam&logoColor=white)](https://store.steampowered.com/app/993090/Lossless_Scaling/)

Lossless Scaling includes image-scaling and frame-generation features that may improve perceived smoothness when configured appropriately.

### Notes for RX 580 Users

- Lossless Scaling is a separate application and is **not included** with this compatibility fix.
- Frame generation requires additional GPU resources and may reduce the game's base FPS when the GPU is already heavily loaded.
- Results depend on the base frame rate, game settings, display mode, and application configuration.
- A reasonably stable base frame rate generally provides a better starting point for frame generation.
- Use a supported display mode and follow Lossless Scaling's own instructions.

**Lossless Scaling is optional.** It does not replace the compatibility fix and cannot guarantee smoother results on every system.

Frame generation can improve perceived motion, but generated frames are not equivalent to additional natively rendered frames.

---

## How the Fix Works

Modern games can depend on graphics features and GPU capabilities that are unavailable or unsupported on older graphics architectures.

This project investigates and implements a game-specific compatibility path intended to address the obstacles preventing Indiana Jones and the Great Circle from running correctly on the target AMD Polaris hardware.

Depending on the implementation included in a particular release, the compatibility work may involve graphics initialization, rendering compatibility, shader behavior, or other components required to start and run the game.

The launcher and compatibility components are intended to work together as a single setup.

### Important Implementation Notes

- Use the launcher and compatibility files supplied with the same release.
- Do not remove required files without understanding their purpose.
- Do not replace individual components with DLLs from unrelated projects.
- Do not combine files from different compatibility-fix versions.
- Follow the installation procedure documented for your release.

The implementation may evolve between releases as compatibility research and testing continue.

---

## Performance and Stability

The compatibility fix has been tested on an AMD Radeon RX 580 8GB, with the developer reporting **approximately 40–60 FPS and stable performance during testing**.

This demonstrates that a playable experience can be achieved on the tested hardware configuration.

Actual results may vary depending on scene complexity, graphics settings, driver behavior, background applications, and the specific game version.

### What to Expect

- Performance may vary between locations and gameplay situations.
- Some scenes may place a greater workload on the GPU or CPU.
- Driver and game updates may affect compatibility or performance.
- Additional scaling or frame-generation software can change perceived smoothness and resource usage.
- Results on one RX 580 system do not guarantee identical performance on every Polaris GPU.

The project aims to provide a functional and stable gaming experience while continuing to investigate graphics compatibility and performance limitations.

**No universal FPS guarantee is made.** The reported 40–60 FPS range represents the developer's observed testing experience.

### Reporting Performance Problems

If you experience frame drops or stuttering, include the following details when reporting the issue:

- The area or gameplay situation where it occurs.
- The approximate frame rate before and during the problem.
- Your graphics settings.
- Your GPU driver version.
- Your game version and compatibility-fix version.
- Whether the issue occurs consistently or only occasionally.

This information helps distinguish a compatibility problem from a performance limitation or a configuration-specific issue.

---

## GPU Compatibility

| GPU | Compatibility Status |
|:---|:---|
| AMD Radeon RX 580 8GB | Primary development and testing target |
| AMD Radeon RX 580 2048SP | Relevant target variant; results depend on the tested configuration |
| Other AMD Radeon RX 400 / RX 500 GPUs | Not individually verified unless stated in a release note |
| Other AMD GPUs | Not verified |
| NVIDIA GPUs | Not verified |
| Intel GPUs | Not verified |

> [!NOTE]
> The **AMD Radeon RX 580 8GB** is the primary target. Do not assume that another GPU will behave identically. GPU capabilities, memory capacity, drivers, and system configuration can affect compatibility and performance.

---

## Tested Hardware and Software

The primary development and testing configuration is focused on the following hardware:

| Component | Specification |
|:---|:---|
| GPU | AMD Radeon RX 580 8GB |
| GPU Architecture | AMD Polaris / GCN 4 |
| CPU | Intel Core i5-12400F |
| RAM | 16GB |
| Operating System | Windows 11 |
| Graphics Driver | See the tested configuration and release notes |
| Performance Observed | Approximately 40–60 FPS during developer testing |

Results may differ on other configurations. Refer to the release notes for any additional hardware or software requirements.

---

## Troubleshooting

### The Game Does Not Start

- Confirm that the installation completed successfully.
- Start the game through **`IJGCLauncher.exe`**.
- Verify that the required compatibility files from the same release are present.
- Check whether security software quarantined a required file.
- Confirm that the game installation directory is correct.
- Collect the relevant logs before changing or deleting files.

### The Game Starts but Crashes

- Confirm that you are using the launcher and compatibility files supplied with the same release.
- Record the game version and compatibility-fix version.
- Check for relevant error messages or crash reports.
- Avoid replacing individual compatibility components with files from unrelated projects.
- Include reproducible steps when reporting the issue.

### Missing Textures or Other Rendering Problems

- Verify that all required files from the installed release are present.
- Avoid mixing compatibility files from different versions.
- Record the game build, GPU driver version, and the location where the problem occurs.
- Include screenshots or logs when opening an issue.

### Stuttering or Frame Drops

Performance can vary depending on scene complexity, graphics settings, shader compilation, driver behavior, and system workload.

Stuttering does not automatically mean that the compatibility fix has failed.

Report when the stuttering occurs and whether it can be reproduced consistently. Avoid changing several settings at once, because doing so makes the underlying cause more difficult to identify.

### `IJGCLauncher.exe` Is Missing

Verify that the installer completed successfully and check whether security software removed the launcher.

If necessary, repair the installation using the installer associated with the same release.

Do not download individual launcher files from untrusted sources.

### The Fix Stops Working After a Game Update

A game update may change files or behavior required by the compatibility setup.

Record the exact game version or build, the compatibility-fix version, and the symptoms you observe.

Check the project's release notes for compatibility updates before making additional modifications.

---

## Reporting Issues

Before opening an issue, include as many of the following details as possible:

- GPU model and VRAM capacity.
- CPU and system RAM.
- Windows version.
- Graphics-driver version.
- Game version or build.
- Compatibility-fix release version.
- Confirmation that the game was started through `IJGCLauncher.exe`.
- Whether the problem occurs at startup or during gameplay.
- Steps to reproduce the problem.
- Relevant logs, screenshots, or a description of the observed behavior.

[**Open a GitHub Issue**](../../issues)

Please distinguish launch failures, crashes, rendering defects, and performance problems so each issue can be investigated appropriately.

---

## Disclaimer

This is an independent, community-developed compatibility project. It is not affiliated with or endorsed by the game's developer or publisher, AMD, Microsoft, or the developers of any third-party components used by the project.

All trademarks and game assets belong to their respective owners.

This project does not guarantee compatibility or a particular performance level across every hardware configuration, graphics-driver version, or game update.

Use the compatibility fix at your own discretion. Keep backups of important files before installing modifications, and download releases only from the project's official repository.

---

## Credits

**Project Author:** [ibr3himkhaled](https://github.com/ibr3himkhaled)

Developed through independent graphics compatibility research, debugging, experimentation, and testing focused on AMD Polaris hardware.

---

<div align="center">

**The fix is free to use. Support is always optional.**

</div>
