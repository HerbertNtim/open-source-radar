# 4. Trova una issue che puoi completare

Una buona issue da affrontare per la prima volta è piccola, descritta chiaramente, riproducibile e non è già stata presa in carico da un altro contributore. È proprio quest'ultimo aspetto che fa perdere più tempo a chi inizia.

## Dove cercare

- **L'[indice delle issue](../../issues/README.md)** e il [sito web](https://tanbirramim.github.io/open-source-radar/) di questo repository: apri le issue contrassegnate come adatte ai nuovi contributori, già filtrate per escludere quelle assegnate a qualcuno o collegate a una pull request aperta.
- **Il sistema di gestione delle issue del progetto**, filtrando per le etichette dedicate ai nuovi contributori.
- **La ricerca di GitHub**, ad esempio:

```text
is:issue is:open no:assignee -linked:pr label:"good first issue" language:python
```

`no:assignee` nasconde le issue assegnate e `-linked:pr` nasconde quelle che hanno già una pull request collegata. Aggiungi `updated:>2026-06-01` (utilizzando una data recente) per escludere quelle non aggiornate da molto tempo.
