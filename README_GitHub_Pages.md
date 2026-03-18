
# Rechtstexte (Impressum & Datenschutzerklärung) + Verlinkung zur AGB

Dieses Paket enthält:

- `impressum.html`
- `datenschutz.html`
- `agb-footer-snippet.html` (HTML-Footer zum Einfügen in deine AGB-Seite)

## So veröffentlichst du alles auf GitHub Pages

1. **Dateien hochladen** in dasselbe Repository wie deine AGB-Seite (z. B. `agb/`):
   - Lade `impressum.html` und `datenschutz.html` ins **Repo-Root** (oder in denselben Ordner wie deine AGB-Datei).
   - Öffne deine AGB-Datei (z. B. `index.html`) und füge den Inhalt aus `agb-footer-snippet.html` **vor `</body>`** ein.

2. **GitHub Pages aktivieren** (falls nicht geschehen):
   - *Repository* → **Settings** → **Pages** → *Source:* `Deploy from a branch` → Branch `main` → Ordner `/ (root)` → **Save**.
   - Warte, bis die Seite gebaut ist. Die URL wird dir dort angezeigt (z. B. `https://dein-username.github.io/agb/`).

3. **Links prüfen**
   - Rufe `https://dein-username.github.io/agb/impressum.html` und `…/datenschutz.html` auf.
   - Klicke in deiner AGB-Seite ganz unten auf **Impressum**/**Datenschutzerklärung** – beide Seiten sollten sich öffnen.

4. **(Optional) Eigene Subdomain bei IONOS**
   - Lege z. B. `recht.deinedomain.de` oder `agb.deinedomain.de` als **CNAME** auf `dein-username.github.io`.
   - In GitHub: **Settings** → **Pages** → **Custom domain**: `agb.deinedomain.de` → **Enforce HTTPS** aktivieren.

## Anpassen
- Ersetze die Platzhalter `[ … ]` in `impressum.html` und `datenschutz.html` durch deine echten Daten.
- Ergänze in `datenschutz.html` die eingesetzten Tools (z. B. Stripe/PayPal, Analytics, Einbindungen) und – falls vorhanden – Info zur Einwilligungsverwaltung (Cookie-Banner).

> Hinweis: Diese Vorlagen sind als praxisnahe Muster gedacht und ersetzen keine Rechtsberatung. Aktualisiere das **Stand-Datum** bei Änderungen.
