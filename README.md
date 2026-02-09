# Whisperspace OBR Rules Extension

Shared Whisperspace rules reference extension for Owlbear Rodeo.

## Build

```bash
npm install
npm run build
```

## Development

```bash
npm run dev
```

## Manifest

Load `dist/manifest.json` in Owlbear Rodeo after building.

## Hosting
- Target: `https://obr.whisperspace.com/rules/manifest.json` (or separate subdomain if preferred)
- Build output: `dist/`
- Deploy model: build from this project directory and serve the `dist/` folder directly.

## Related Repos

- Character sheet extension: `whisperspace-obr-extension`
- SDK: `whisperspace-sdk`
- Rules API: `whisperspace-rules-api`
