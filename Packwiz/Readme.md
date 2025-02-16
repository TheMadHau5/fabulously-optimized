# Packwiz

[Packwiz](https://github.com/comp500/packwiz) is a tool for making self-updating modpacks for MultiMC.

The best way to update it for Fabulously Optimized is to just create a CF pack and update the Packwiz manifests (`index.toml` and the hash of `pack.toml`) via the terminal:

```
.\packwiz.exe curseforge import filepath
.\packwiz.exe remove hydrogen
.\packwiz.exe mr install hydrogen
.\packwiz.exe refresh
```

After that it is possible to just use the MultiMC pack created in MultiMC-Packwiz, instructions are in the Packwiz repo. Because Packwiz cannot upgrade the MC, the modpack versions are foldered by Minecraft versions (always latest for the version).

Requirements:

1. [Download the manifest creating executable from here](https://github.com/comp500/packwiz/actions) and place it to `../Packwiz`.
2. [Download the MultiMC bootstrap from here](https://github.com/comp500/packwiz-installer-bootstrap/releases) and place it to `../MultiMC-Packwiz/Fabulously Optimized (auto-update)/.minecraft`