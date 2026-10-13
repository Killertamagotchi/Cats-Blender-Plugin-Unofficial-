# Cats Blender Plugin

> [!IMPORTANT]
> ## 🚨 CATS BLENDER PLUGIN HAS MOVED TO NEONEKO FORGEJO
>
> **THIS GITHUB REPOSITORY IS NO LONGER MAINTAINED.**
>
> Cats Blender Plugin has **NOT** been discontinued. However, all development, maintenance, updates, releases, and support have permanently moved to our self-hosted **NeoNeko Forgejo** instance.
>
> ### ➡️ [VISIT THE OFFICIAL CATS BLENDER PLUGIN REPOSITORY](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin)
>
> **What does this mean?**
>
> - ❌ **GitHub is no longer maintained.** No further updates, fixes, or releases will be published here.
> - ❌ **GitHub issues and pull requests are no longer monitored.** Please do not submit new issues or contributions here.
> - ❌ **The code and releases on GitHub are outdated.** Do not use this repository for new installations.
> - ✅ **Cats Blender Plugin is still actively maintained.** Development continues on NeoNeko Forgejo.
> - ✅ **All new releases and updates are published exclusively on Forgejo.**
> - ✅ **Bug reports, feature requests, and contributions are handled through Forgejo.**
> - ✅ **Documentation and project information are maintained on Forgejo.**
>
>
> **Official Repository:** https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin

---

## Official Project Links

| Resource | Link |
|---|---|
| **Official Repository** | [NeoNeko Forgejo](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin) |
| **Latest Releases / Downloads** | [Forgejo Releases](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/releases) |
| **Bug Reports / Feature Requests** | [Forgejo Issues](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/issues) |
| **Contributions / Pull Requests** | [Forgejo Pull Requests](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/pulls) |
| **Documentation / Wiki** | [Forgejo Wiki](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/wiki) |
| **NeoNeko Website** | [neoneko.org](https://neoneko.org/) |

---

## ⚠️ Important: Support and Community

### DO NOT REQUEST SUPPORT IN THE ORIGINAL CATS DISCORD SERVER

**This version of Cats Blender Plugin is an unofficial continuation and is not maintained by the original Cats development team.**

Please do not request assistance with this version in the original Cats Discord server. The original developers and their community are not responsible for supporting the NeoNeko version.

**NeoNeko does not operate an official Cats Discord server or a separate Cats website.**

If you encounter a bug, require assistance, or wish to suggest an improvement, please use our official issue tracker:

### [➡️ Open an Issue on NeoNeko Forgejo](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/issues)

Please provide as much information as possible when reporting an issue, including your Blender version, Cats version, and any relevant error messages.

**Support requests submitted through the old GitHub repository will not be monitored or answered.**

---

## About Cats Blender Plugin

Cats Blender Plugin is a Blender add-on designed to simplify the process of importing, fixing, optimizing, and preparing 3D models for VRChat.

Originally developed by Absolute Quantum and later maintained by the community, Cats provides a collection of tools that automate many otherwise time-consuming processes involved in avatar creation.

This unofficial continuation is maintained by **NeoNeko (Yusarina)**, with ongoing development focused on compatibility with modern Blender versions, performance improvements, bug fixes, and additional functionality.

Cats supports models and workflows from various applications and formats, including:

- MMD (MikuMikuDance)
- XNALara / XPS
- Mixamo
- Source Engine
- Unreal Engine
- DAZ / Poser
- Blender Rigify
- The Sims 2
- MotionBuilder
- Autodesk 3ds Max
- FBX
- VRM
- glTF / GLB
- And potentially more!

With Cats, tasks that would otherwise take hours can often be completed in just a few operations.

From fixing armatures and preparing eye tracking to generating visemes and optimizing materials, Cats aims to simplify the avatar creation workflow.

---

## Blender Version Support

**Current development focuses on Blender 5.x and newer compatible releases.**

Not every Cats release supports every Blender version. Please ensure you download the appropriate release for your installed version of Blender.

For the latest compatibility information, visit:

- [Official Releases](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/releases)
- [Version Support Wiki](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/wiki/Version-Support)

> [!NOTE]
> Older Blender versions may require earlier Cats releases.
>
> Compatibility with older Blender versions is not guaranteed, and support for legacy releases may no longer be provided.

---

## Features

Cats provides comprehensive tools for VRChat avatar creation, optimization, and maintenance.

### Import / Export

- Import models from MMD, VRM, FBX, Source Engine, and other supported formats.
- Simplify model preparation for VRChat.
- Support various model types and workflows.

### Model Optimization

- Combine materials.
- Generate texture atlases using the built-in Texture Atlas Tool.
- Merge bones.
- Remove unnecessary geometry.
- Optimize meshes and materials.
- Reduce unnecessary complexity in avatar models.

### Eye Tracking

- Automatically configure eye tracking.
- Support SDK3 and legacy eye tracking workflows.
- Assist with eye bone setup and configuration.

### Visemes / Lip Sync

- Automatically generate and configure visemes.
- Prepare mouth shapes for VRChat lip synchronization.
- Simplify facial animation setup.

### Armature Tools

- Merge armatures.
- Attach meshes to existing rigs.
- Repair and optimize bones.
- Simplify skeletal structures.
- Prepare models for VRChat.

### Shape Key Tools

- Repair and manage shape keys.
- Assist with shape key optimization.
- Simplify common shape key operations.

### Translation Tools

- Translate Japanese bone, shape key, material, and object names into English.
- Support multiple translation providers, including Google, DeepL, LibreTranslate, and MyMemory.
- Provide tools for managing model translations.

### Texture Atlas Tool

- Generate texture atlases directly within Cats.
- Combine materials and textures to improve optimization.
- Support configurable atlas dimensions and tiling.
- Reduce material complexity without requiring the legacy Material Combiner add-on for supported workflows.

### Additional Features

- Model scaling tools.
- Custom model creation.
- Material cleanup.
- Mesh repair.
- Rig optimization.
- Various quality-of-life improvements.

**And much more!**

For complete feature documentation, visit the [official Cats Wiki](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/wiki).

---

## Requirements

- A supported version of Blender matching your chosen Cats release.
- Blender downloaded from the [official Blender website](https://www.blender.org/download/).
- NumPy, if required when using a custom Python installation that Blender accesses.

### Important Notes

- **Windows Store Blender:** No support is provided due to known permission issues.
- **Linux:** Blender installations from Linux package managers, Snap, or Flatpak are not officially supported.
- **Older Blender Versions:** Compatibility depends on the Cats release, and older versions may no longer receive support.
- **Development Builds:** Development versions may contain experimental functionality and are not recommended for production use.

### Optional Dependencies

Some features can integrate with additional Blender add-ons.

- **[Material Combiner](https://github.com/Grim-es/material-combiner-addon/)** — Legacy material combining and texture atlas functionality.
- **[Immersive Scaler](https://github.com/triazo/immersive_scaler)** — Additional scaling functionality.

> [!NOTE]
> Cats includes its own built-in Texture Atlas Tool.
>
> Material Combiner remains available for legacy workflows but is no longer required for supported built-in atlas generation.
>
> Optional dependencies are only required for the specific features that use them.

For more information, see the [Installation Wiki](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/wiki/Installation).

---

## Installation

> [!CAUTION]
> ### DO NOT DOWNLOAD CATS FROM THIS GITHUB REPOSITORY
>
> **This repository is outdated and no longer maintained.**
>
> Download Cats exclusively from our official NeoNeko Forgejo instance:
>
> **[➡️ Download Cats Blender Plugin](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/releases)**

### Installation Steps

1. Visit the [official Cats Releases page](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/releases).
2. Download the Cats release compatible with your Blender version.
3. Open Blender.
4. Navigate to **Edit > Preferences**.
5. Open the **Get Extensions** or **Add-ons** section, depending on your Blender version.
6. Select **Install from Disk** from the relevant menu.
7. Choose the downloaded Cats ZIP file. **Do not extract it.**
8. Enable Cats if it has not been enabled automatically.
9. Restart Blender if necessary.
10. Open the 3D Viewport and press **N** to access the Cats panel.

For detailed installation instructions, visit the [Installation Wiki](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/wiki/Installation).

---

## Updating Cats

All future Cats Blender Plugin updates are distributed through **NeoNeko Forgejo**.

To update Cats:

1. Visit the [official Releases page](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/releases).
2. Download the latest compatible version.
3. Install the updated version in Blender.
4. Restart Blender if required.

You may also use the built-in updater if supported by your installed Cats version.

> [!IMPORTANT]
> **GitHub is no longer an official update source.**
>
> Older versions of Cats may still reference GitHub for updates. These references are outdated.
>
> Please migrate to a current release from NeoNeko Forgejo to ensure you receive future updates and fixes.

---

## Help & Documentation

Documentation for the actively maintained version of Cats Blender Plugin is available through NeoNeko Forgejo.

### Official Documentation

- [Cats Wiki](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/wiki)
- [Quick Access Guide](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/wiki/Quick-Access)
- [Optimization Tools](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/wiki/Optimization)
- [Eye Tracking Setup](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/wiki/Eye-Tracking)
- [Visemes Setup](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/wiki/Visemes)
- [Installation Guide](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/wiki/Installation)
- [Version Support](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/wiki/Version-Support)
- [Troubleshooting](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/wiki/Troubleshooting)
- [FAQ](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/wiki/FAQ)

> [!WARNING]
> Documentation previously hosted on GitHub may be outdated.
>
> Always refer to the official Forgejo Wiki for current documentation.

---

## Bug Reports and Feedback

Found a bug or have a suggestion?

We welcome feedback and contributions that help improve Cats Blender Plugin.

Please submit all bug reports, feature requests, and suggestions through our official issue tracker:

### [➡️ Report a Bug or Suggest a Feature](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/issues)

When reporting a problem, please include:

- Your Blender version.
- Your Cats Blender Plugin version.
- Your operating system.
- Steps to reproduce the issue.
- Any relevant error messages or screenshots.

This information helps us investigate and resolve problems more efficiently.

**Please do not report bugs through the archived GitHub repository.**

---

## Contributing

Cats Blender Plugin is an open-source community project, and contributions are welcome.

All development now takes place on **NeoNeko Forgejo**.

If you would like to contribute:

1. Visit the [official Cats repository](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin).
2. Create a Forgejo account if you do not already have one.
3. Fork the repository.
4. Make your changes.
5. Submit a pull request for review.

You can also contribute by reporting bugs, improving documentation, or suggesting features.

### Important

**GitHub pull requests are no longer reviewed or accepted.**

Any code contributions must be submitted through:

[NeoNeko Forgejo Pull Requests](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin/pulls)

---

## Acknowledgements

Cats Blender Plugin was originally developed by **Absolute Quantum** and subsequently maintained and expanded by community contributors.

This unofficial continuation is maintained by **NeoNeko (Yusarina)**.

We would like to thank the original developers, past contributors, and wider Blender and VRChat communities for their continued contributions and support.

### Code Contributors

- Hotox
- Shotariya
- Neitri
- Kiraver
- Jordo
- Ruubick
- 989onan
- rurre

### Original Cats Blender Plugin

The original Cats Blender Plugin was developed by Absolute Quantum.

You can find the original project here:

[absolute-quantum/cats-blender-plugin](https://github.com/absolute-quantum/cats-blender-plugin)

**Please note:** The original Cats project and this NeoNeko continuation are separate projects.

### Third-Party Projects

Cats incorporates or integrates functionality from several third-party projects, including:

- [MMD Tools](https://github.com/UuuNyaa/blender_mmd_tools)
- [Immersive Scaler](https://github.com/triazo/immersive_scaler)
- [Material Combiner](https://github.com/Grim-es/material-combiner-addon)

We thank the developers and contributors of these projects for their work.

---

## About NeoNeko

**NeoNeko** maintains and develops open-source software, tools, and services, including this unofficial continuation of Cats Blender Plugin.

Our projects and development infrastructure are hosted on our own services.

- **Website:** [https://neoneko.org](https://neoneko.org/)
- **Git Hosting:** [https://git.neoneko.org](https://git.neoneko.org/)
- **Cats Blender Plugin:** [Official Repository](https://git.neoneko.org/NeoNeko/Cats-Blender-Plugin)

---
