# H-EALTH

Software per la sanità: strumenti per le aziende sanitarie.

## Come è organizzato il codice

| Repository | Cosa contiene |
|---|---|
| `platform` | Reusable workflows, composite actions, ruleset, scaffold, ADR di piattaforma. Versionato con tag `vX.Y.Z`. |
| `template-product` | Scheletro del monorepo di un prodotto. |
| `<dominio>-<tipo>` | Un monorepo per prodotto, es. `sale-operatorie-ussl2`. |
| `.github` | Questo repo: file comuni ereditati da tutti gli altri. |

## Come lavoriamo

Branch corto → PR con template compilato → CI verde e una review → merge su `main` → staging automatico → tag di rilascio → Release con SBOM → deploy in produzione con approvazione.

Il perché è su Notion ([Engineering hub](https://app.notion.com/p/3cf4af5aa4ca801abf10ca040d9823cd)); il come è nel README di `platform`; la regola formale è su Drive.
