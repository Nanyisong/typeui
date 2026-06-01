# TypeUI Gemini CLI Extension

TypeUI connects Gemini CLI to the TypeUI MCP server so it can use curated design systems, UI prompts, and layout variations while building interfaces.

## Install

Install TypeUI from the public repository:

```bash
gemini extensions install https://github.com/bergside/typeui
```

For local development, link this extension folder:

```bash
gemini extensions link plugins/gemini/typeui
```

After installation, Gemini CLI will connect to TypeUI MCP. Sign in with TypeUI if Gemini CLI asks you to authorize the connection.

## MCP server

This extension registers the TypeUI Streamable HTTP MCP server:

```text
https://mcp.typeui.sh/mcp
```

## Marketplace preparation

To submit TypeUI to the Gemini CLI extension gallery, keep `gemini-extension.json` at the repository root and add the `gemini-cli-extension` GitHub topic to the public repository.

## Links

- Website: https://www.typeui.sh
- Documentation: https://www.typeui.sh/docs
- Gemini CLI setup guide: https://www.typeui.sh/docs/guides/gemini-cli
- Privacy policy: https://www.typeui.sh/privacy
- Terms of service: https://www.typeui.sh/terms
