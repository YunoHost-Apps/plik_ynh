Plik is a scalable & friendly temporary file upload system — like WeTransfer, self-hosted.

### Features

- 🖥️ Modern Vue 3 web interface with i18n (12 languages) and light, dark, custom themes
- 🧑‍💻 Powerful [Command line client](https://root-gg.github.io/plik/features/cli-client.html)
- ☁️ Multiple storage backends (local, S3, OpenStack Swift, Google Cloud Storage)
- 🗄️ Multiple metadata backends (SQLite, PostgreSQL, MySQL)
- 🔑 Multiple authentication providers (Local, Google, GitHub, OVH, OIDC)
- ⏱️ Configurable TTL with auto-cleanup
- 💣 OneShot downloads (file deleted after first download)
- ⚡ Stream mode (uploader → downloader, nothing stored)
- 🔐 Password-protected uploads (BasicAuth)
- 🔒 End-to-end encryption with [Age](https://age-encryption.org/) (CLI ↔ Web interoperable)
- 🖼️ File preview with syntax highlighting, Markdown rendering, Mermaid diagrams and media player
- 📦 Archive directly from CLI/Web
- 📊 Prometheus metrics
- 🤖 [MCP server](https://root-gg.github.io/plik/features/mcp-server.html) for AI assistant integration

### Third-party clients

   - [ShareX](https://getsharex.com/) Uploader : Directly integrated into ShareX
   - [plikSharp](https://github.com/iss0/plikSharp) : A .NET API client for Plik
   - [Filelink for Plik](https://gitlab.com/joendres/filelink-plik) : Thunderbird Addon to upload attachments to Plik