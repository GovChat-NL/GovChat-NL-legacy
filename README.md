# GovChat-NL-legacy

> [!IMPORTANT]
> **This is the legacy OpenWebUI implementation. The default GovChat-NL stack is now LibreChat.**
>
> Go to the current repository: **[GovChat-NL](https://github.com/GovChat-NL/GovChat-NL)**.
> Read the current documentation: **[GovChat-NL documentation](https://govchat-nl.github.io/)**.

## Transition

On 13 October 2026, the GovChat-NL steering group decided to make the LibreChat-based stack the default. The meeting had a quorum (5 of 8 members); all five votes supported the transition. The Compose-based deployment now brings up the required services, connects them, and imports the n8n workflows automatically.

This repository contains the former OpenWebUI stack and is retained as a **legacy reference** for existing deployments and historical context. It is not the source of truth for new installations and should not be used as the starting point for new deployments. New development and deployment documentation belongs in the current repository linked above.

## Existing installations

Do not replace a running installation by simply copying the new Compose file over it. The LibreChat stack has different application services, persistence, authentication and configuration. Plan and validate any data migration separately; the legacy OpenWebUI data is not automatically imported into LibreChat.

The old configuration and deployment files remain in this repository for operators who need to understand or maintain an existing OpenWebUI installation. Treat them as frozen legacy material unless an explicit security or maintenance fix is required.
