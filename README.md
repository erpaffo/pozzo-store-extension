# Pozzo Store Extension

Estensioni ufficiali per [Pozzo Launcher](https://github.com/erpaffo/Pozzo-Launcher).

Lo Store dell'app legge `index.json` in questa cartella; ogni estensione sta nella cartella con il suo id e si installa solo se tutti i file elencati nell'indice hanno lo sha256 indicato. I permessi che ogni estensione richiede sono dichiarati nel suo `plugin.toml` (`permissions`) e vengono mostrati prima dell'installazione.
