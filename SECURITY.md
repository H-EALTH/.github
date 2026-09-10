# Security Policy

## Segnalare una vulnerabilità

Non aprire issue pubbliche per problemi di sicurezza.

Usa **Report a vulnerability** nel tab *Security* del repository interessato (GitHub Private Vulnerability Reporting), oppure scrivi al team engineering tramite i canali interni indicati nell'Engineering hub.

Includi: repository e versione (tag `<prodotto>-vX.Y.Z` o SHA), descrizione, passi per riprodurre, impatto stimato.

## Cosa aspettarsi

- Conferma di ricezione entro 3 giorni lavorativi.
- Valutazione e piano di correzione tracciati in Linear come `RSK-___`.
- La correzione segue il flusso ordinario: PR, CI, review, release taggata. Il documento di rilascio su Drive registra la chiusura.

## Ambito

Tutti i repository dell'organizzazione `H-EALTH`. Le immagini pubblicate su `ghcr.io/h-ealth/*` sono identificate da digest: indica il digest se la segnalazione riguarda un'immagine.
