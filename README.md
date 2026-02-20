# ⚡ CoreX JTL Social Proof Ribbon

Die ultimative Lösung für rechtssicheren und performanten Social Proof in JTL-Shop 5 – direkt integriert in das native Ribbon-System.

## 🌟 Warum CoreX Social Proof Ribbon?

Viele Social-Proof-Tools bremsen den Shop durch externe API-Abfragen oder riskieren Abmahnungen durch gefälschte Daten. Das **CoreX Social Proof Ribbon** nutzt vorhandene Signale deines Shops (wie "Top bewertet" oder "Bestseller") und hebt diese dynamisch hervor. Das Ergebnis: **Maximaler Trust bei 0% rechtlichem Risiko.**

## 🛠 Key Features

- **Legal-Safe Technology:** Keine erfundenen Verkäufe. Nutzt ausschließlich echte JTL-Ribbons als Trigger.
- **Zero Database Load:** Keine SQL-Abfragen oder Smarty-Hacks, die zu Error 500 führen könnten.
- **One-Time Focus:** Erscheint pro Session nur einmal, um den Kunden zu konvertieren, nicht zu nerven.
- **Modular Design:** Vollständig anpassbar auf jeden Ribbon-Typ (Neu, Top-Seller, Sonderpreis).
- **CoreX Clean Code:** Hochoptimiertes Vanilla JavaScript ohne externe Abhängigkeiten (kein jQuery nötig).

## 🚀 Schnellstart

### 1. JTL-Shop Vorbereitung
Stelle sicher, dass deine Artikel in der Wawi oder im Shop über Ribbons verfügen (z.B. "Top bewertet" oder "Bestseller").

### 2. Konfiguration
Öffne die `corex-ribbon-proof.html` und passe das `config`-Objekt am Anfang des Scripts an:
- `searchText`: Der Text des Ribbons, auf den das Tool reagieren soll.
- `displayTitle`: Die Überschrift in der Bubble.
- `displayText`: Deine überzeugende Trust-Botschaft.

### 3. Einbau
Kopiere den Inhalt der `corex-ribbon-proof.html` einfach in einen **JTL-Dropper** (Typ: Eigener Code) oder direkt in dein Template (z.B. in die `footer.tpl`).

## 💎 Über CoreX-Systems

Dieses Tool wurde nach den CoreX-Performance-Standards entwickelt:
- **Variable Prefixing:** `crp_`
- **Unique DOM ID:** `corex-ribbon-proof`
- **Keine externen Abhängigkeiten** (Vanilla JS)

Developed with ❤️ by **Corex-Systems** (GitHub: **Corex-Systems**)
