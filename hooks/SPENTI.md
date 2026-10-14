# Hook spenti in questo fork

In questo fork gli hook di ECC sono spenti per scelta: `hooks/hooks.json` è stato rinominato in `hooks/hooks.disabled.json`, quindi Claude Code e Cowork non li caricano.

Per riaccenderli basta rinominare il file di nuovo in `hooks/hooks.json`.

Nei controlli mensili di aggiornamento il file resta rinominato. Le modifiche che arrivano dall'originale vanno applicate a `hooks.disabled.json`.
