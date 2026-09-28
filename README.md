# Minecraft AI Build Compiler

A desktop app for previewing, editing and exporting Minecraft builds from commands and photo references.
This repository hosts public installers, release notes and SHA-256 checksums. No GitHub account is needed to download them.

## Download

[Get the latest release](https://github.com/Ayanokoji12786/minecraft-ai-build-compiler-downloads/releases/latest)

Choose **arm64.dmg** for an Apple silicon Mac, **.dmg** without arm64 for an Intel Mac,
**Setup.exe** for Windows, or **.AppImage / .deb** for Linux. ZIP and portable EXE versions are also provided.
The release contains `SHA256SUMS.txt` to verify your download.
These community builds are not signed with an Apple Developer or Windows publisher certificate;
the operating system may ask you to approve the app when opening it.

## Build from photos

1. Open **File → Build from photos**.
2. Put building views in **Exteriors** and room styles in **Interiors**.
3. Keep **Automatic** selected, and click **Install local model if needed** once.
4. Choose **Reconstruct building → Preview build**. Compare the result with the reference, edit and export.

Photos are analyzed locally with Ollama. A ChatGPT connection is not needed.
The macOS installer includes the runtime; Windows and Linux currently need Ollama running separately.
Model weights download separately and remain in your local Ollama cache.
The app produces approximate, editable drafts. It does not promise exact reconstruction or recover unseen surfaces.
Read the latest release notes for supported models, memory settings and validation limits.

## Exports

Minecraft Java commands, Sponge schematics, Litematica, structures and data packs are available in the app.
Save an editable `.mabuild` project to continue working later.

Minecraft is a trademark of Mojang Studios. This app is an independent project and is not affiliated with Mojang or Microsoft.
