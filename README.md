# PCI Demo App (Dummy)

Diese GitHub-Pages-Demo zeigt die PCI Preisauskunft-App im Original-Look, aber **ohne echte Preise**.

## Dummy-Logik
- Alle Preisfelder werden beim Laden im Browser auf **5,00 €** gesetzt (Nettopreis, AWR-Preise, Staffelpreise).
- Artikelnummern/Produktnamen bleiben unverändert.

## Deployment (GitHub Pages)
1. Repository anlegen (z.B. `pci-demo-app`).
2. Inhalt dieses Ordners in das Repo-Root hochladen (mind. `index.html`).
3. GitHub: Settings → Pages → "Build and deployment"
   - Source: Deploy from a branch
   - Branch: `main` (oder `master`) / Folder: `/ (root)`
4. Speichern → URL öffnen.
