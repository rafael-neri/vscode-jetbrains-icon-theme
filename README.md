# JetBrains Icon Theme – Open VSX Publisher

This repository automates publishing the JetBrains Icon Theme extension to the [Open VSX Registry](https://open-vsx.org/extension/chadalen/vscode-jetbrains-icon-theme), making it available for VS Code, VSCodium, and compatible editors.

- The extension source is maintained at: https://github.com/cadamsdev/vscode-jetbrains-icon-theme
- This repo only handles packaging and Open VSX publication.

## How it works
- The workflow fetches the latest release from the original repository.
- If a new tag is found, it builds and publishes the VSIX to Open VSX.
- No manual action is required for regular publishing.

## Links
- [Original Extension (GitHub)](https://github.com/cadamsdev/vscode-jetbrains-icon-theme)
- [Open VSX Registry](https://open-vsx.org/extension/chadalen/vscode-jetbrains-icon-theme)
- [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=chadalen.vscode-jetbrains-icon-theme)

---

This repository is not affiliated with JetBrains or the original extension author. For issues or contributions, please refer to the original project.
