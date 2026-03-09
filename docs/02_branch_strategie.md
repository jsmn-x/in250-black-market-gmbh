# Branch-Strategie
 
## Geweahlte Strategie
Fuer dieses Repository wird die **GitHub-Flow-Strategie** verwendet.
 
## Ziel
Die Strategie stellt sicher, dass der Branch `main` jederzeit stabil bleibt und Aenderungen kontrolliert ueber Pull Requests integriert werden.
 
## Regeln
 
### main
- Der Branch `main` enthaelt immer den aktuellen stabilen Stand.
- Direktes Pushen auf `main` ist nicht erlaubt.
- Aenderungen gelangen nur ueber Pull Requests nach `main`.
 
### Feature-Branches
- Fuer jede neue Aufgabe oder Aenderung wird ein eigener Branch erstellt.
- Namenskonvention:
  - `feat/Name` fuer neue Funktionen oder Aufgaben
  - `fix/Name` fuer Fehlerbehebungen
  - `docs/Name` fuer Dokumentationsaenderungen
 
Beispiele:
- `feat/Hauptseite`
- `feat/Automatisierung`
- `fix/login-fehler`
 
### Arbeitsablauf
1. Aktuellen Stand von `main` holen
2. Neuen Branch erstellen
3. Aenderungen im Branch umsetzen
4. Commit erstellen
5. Branch pushen
6. Pull Request nach `main` erstellen
7. Pull Request pruefen und mergen
 
### Pull Requests
- Jede Aenderung wird ueber einen Pull Request eingebracht.
- Vor dem Merge soll geprueft werden, ob die Aenderung korrekt ist.
- Nach erfolgreichem Merge kann der Arbeitsbranch geloescht werden.
 
### Releases und Versionen
- Stabile Meilensteine werden mit Git Tags markiert.
- Beispiel: `v1.0`
 
## Vorteile dieser Strategie
- `main` bleibt geschuetzt und stabil
- Aenderungen sind klar nachvollziehbar
- Konflikte werden reduziert
- Teamarbeit wird strukturierter
- Releases koennen sauber markiert werden
