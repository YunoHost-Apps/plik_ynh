Plik est une application d’envoi de fichiers temporaires comparable à WeTransfer.

### Fonctionnalités
- 🖥️ Interface web moderne disponible en 12 langues et en thème clair, sombre et personnalisé.
- 🧑‍💻 [Command line client](https://root-gg.github.io/plik/features/cli-client.html)
- ☁️ Plusieurs possibilités de stockage (local, S3, OpenStack Swift, Google Cloud Storage)
- 🗄️ Plusieurs possibilités de stockage des métadonnées (SQLite, PostgreSQL, MySQL)
- 🔑 Plusieurs fournisseurs d’authentification (Local, Google, GitHub, OVH, OIDC)
- ⏱️ Durée de vie configurable des fichiers avec nettoyage automatique
- 💣 Téléchargement unique (le fichier est supprimé après le premier téléchargement)
- ⚡ Mode streaming (expéditeur → destinataire, sans stockage)
- 🔐 Envois protégés par mot de passe (BasicAuth)
- 🔒 Chiffrement End 2 End avec [Age](https://age-encryption.org/) (interopérabilité CLI ↔ Web)
- 🖼️ Aperçu des fichiers avec coloration syntaxique, rendu Markdown, diagrammes Mermaid et lecteur multimédia
- 📦 Création d'archives directement depuis la CLI ou l'interface Web
- 📊 Prometheus Metrics
- 🤖 [MCP server](https://root-gg.github.io/plik/features/mcp-server.html) pour l'intégration avec des assistants IA.

### Clients

   - [ShareX](https://getsharex.com/) Uploader : directement intégré dans ShareX
   - [plikSharp](https://github.com/iss0/plikSharp) : Client API .NET pour Plik
   - [Filelink for Plik](https://gitlab.com/joendres/filelink-plik) : extension Thunderbird pour envoyer des PJ via Plik
