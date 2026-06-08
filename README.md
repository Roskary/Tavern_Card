# Tavern Card Public

This repository hosts public runtime assets for SillyTavern character cards.

## Runtime Assets

The character card itself is not stored in this repository. The card loads the WeChat UI and MVU helper scripts from:

- `cards/jyx/WeChat_UI_index.html`
- `cards/jyx/Variable_Structure_index.js`
- `cards/jyx/MVU_index.js`

## URLs

Use jsDelivr URLs under:

```text
https://testingcf.jsdelivr.net/gh/Roskary/Tavern_Card@main/
```

After creating a release tag, replace `@main` in the card with the tag name, such as `@v0.1.0`, for a more stable release.
