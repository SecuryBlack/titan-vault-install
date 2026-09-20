# TitanVault Install Worker

Official Cloudflare Worker that dynamically serves the installation script for **TitanVault** based on the client User-Agent and operating system:

- **Linux / macOS:** `curl -fsSL https://install.titanvault.dev | sudo bash`
- **Windows (PowerShell):** `irm https://install.titanvault.dev | iex`

## License

Apache-2.0 License.
