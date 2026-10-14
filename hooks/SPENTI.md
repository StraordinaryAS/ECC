# Hook spenti in questo fork

In questo fork gli hook di ECC sono spenti per scelta: `hooks/hooks.json` è stato rinominato in `hooks/hooks.disabled.json`, quindi Claude Code e Cowork non li caricano.

Per riaccenderli basta rinominare il file di nuovo in `hooks/hooks.json`.

Nei controlli mensili di aggiornamento il file resta rinominato. Le modifiche che arrivano dall'originale vanno applicate a `hooks.disabled.json`.

## Connettore chrome-devtools spento

Il file `.mcp.json` dell'originale avvia il connettore `chrome-devtools` con `npx -y chrome-devtools-mcp`, che scarica il pacchetto da npm e controlla il browser Chrome. In questo fork è spostato in `mcp-configs/ecc-plugin.mcp.disabled.json`. Per riattivarlo basta riportarlo alla radice come `.mcp.json`.
