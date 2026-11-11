# Tools

Canale di distribuzione dei tool di Andrea. Ogni tool ha due rami, gestiti dagli script di rilascio (non modificarli a mano):

| Tool | Stabile | Test |
|---|---|---|
| CDS Manager | [cds-stabile](https://github.com/themask1987/tools/tree/cds-stabile) | [cds-test](https://github.com/themask1987/tools/tree/cds-test) |
| Forecast Grouping Tool | [forecast-stabile](https://github.com/themask1987/tools/tree/forecast-stabile) | [forecast-test](https://github.com/themask1987/tools/tree/forecast-test) |

Ogni ramo contiene uno zip protetto da password (fornita separatamente) e un `manifest.json` firmato: le app si aggiornano da sole e installano solo aggiornamenti con firma valida.
