Start build, so i can build winehq so later i can build fusion flatpak

flatpak install org.freedesktop.Sdk/x86_64/21.08
flatpak install org.freedesktop.Sdk.Compat.i386/x86_64/21.08
flatpak install org.freedesktop.Sdk.Debug/x86_64/21.08
flatpak install org.freedesktop.Sdk.Docs/x86_64/21.08
flatpak install org.freedesktop.Sdk.Extension.toolchain-i386/21.08
flatpak-builder build-dir org.winehq.Sdk.yaml .

