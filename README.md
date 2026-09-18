# IPT1 · Lernsession 03 · GitHub-Flow & Markdown

> **Name:** _Alisa Kurylenko_  
> **Datum:** _14.09.2026_

## Ziel

Ich kann die wichtigsten Begriffe rund um **Git**, **GitHub**, den **GitHub-Flow** und **Markdown** kurz erklären und meinen Lernfortschritt mit einem eigenen README dokumentieren.

> **Hinweis:** Ersetze die Platzhalter `DEINE ANTWORT` durch deine eigenen kurzen Antworten. Committe die ausgefüllte Datei anschliessend mit einer aussagekräftigen Commit-Nachricht.

---

## 1 · Git und GitHub verstehen

### 1. Was ist Git?

**Meine Antwort:** Ein verteiltes Versionssteuerungssystem.

### 2. Was ist GitHub?

**Meine Antwort:** Eine cloudbasierte Plattform, die auf Git aufbaut. Man kann Git-Projekte auf GitHUb speichern und mit anderen teilen.

### 3. Was ist der wichtigste Unterschied zwischen Git und GitHub?

**Meine Antwort:** Git ist ein lokales Programm. GitHub ist eine cloudbasierte Plattform

### 4. Funktioniert Git auch ohne GitHub?

**Meine Antwort:** Ja, das ist lokales Programm.

### 5. Was ist ein Repository (Repo)?

**Meine Antwort:** Ein Projektordner, der alle Dateien und Versionsverlauf enthält.

### 6. Was ist der `main`-Branch?

**Meine Antwort:** Der Hauptzweig mit dem fertigen Code des Projekts.

### 7. Was ist Markdown?

**Meine Antwort:** Eine Markupsprache, mit der man Texte mit Symbolen formatieren kann.

### 8. Was bedeutet GitHub-Flavoured Markdown (GFM)?

**Meine Antwort:** Eine erweiterte Markdown-Version von GitHub, die mehrere Funkionen bietet.

---

## 2 · GitHub-Flow

### 9. Bringe die Schritte in die richtige Reihenfolge

`Commit · Issue · Pull Request · Branch`

**Meine Antwort:** Issue -> Branch -> Commit -> Pull Request

### 10. Was ist ein Issue?

**Meine Antwort:** Issue werden verwendet, um Ideen, Feedback, Aufgaben oder Fehler für die Arbeit auf GitHub nachzuverfolgen.

### 11. Was ist ein Branch?

**Meine Antwort:** Eine Kopie des Projekts, auf der man arbeitet kann, ohne den Hauptcode (main) zu verändern. 

### 12. Warum arbeitet man für eine Änderung häufig auf einem eigenen Branch?

**Meine Antwort:** Auf einem Branch kann man arbeiten, ohne den Hauptcode zu verändern. Man kann verschiedene Sachen da ausprobieren, ohne den Hauptcode zu beschädigen. Dank Branch können mehrere Personen gleichzeitig an einem Projekt arbeiten, ohne sich gegenseitig zu stören, da sie an separaten Kopien des Projekts arbeiten.

### 13. Was ist ein Commit?

**Meine Antwort:** Ein Speicherpunkt (Checkpoint) in einem Projekt. Man speichert Änderungen an einer oder mehreren Dateien in einem Branch.

### 14. Wozu dient eine Commit-Nachricht?

**Meine Antwort:** Um die Änderungen zu erklären. Es hilft bei der Orientierung im Projekt, wenn man hat viele Commits und Branches.

### 15. Was ist ein Pull Request?

**Meine Antwort:** Eine Anfrage, Commits aus einem Branch in einen anderen Branch zusammenzuführen (mergen).

### 16. Was bedeutet Review?

**Meine Antwort:** Die Kontrolle eines Codes durch ein Teammitglied in einem Pull Request, bevor er freigegeben und übernommen wird.

### 17. Was bedeutet Merge?

**Meine Antwort:** Das ist Integrierung der Änderungen aus einem Branch in einen anderen Branch. (Zwei Branches zusammenzuführen.)

### 18. Wann sollte ein Pull Request gemergt werden?

**Meine Antwort:** Wenn der Code kontrolliert wurde, gut funktioniert und keine Fehler hat.

---

## 3 · Wichtige Git-Begriffe und Befehle

### 19. Was bedeutet Push?

**Meine Antwort:** Es bezeichnet das Hochladen lokaler Änderungen aus einem Git-Repository in ein Remote-Repository auf GitHub.

### 20. Was bedeutet Pull?

**Meine Antwort:** Es bezeichnet das Herunterladen und Zusammenführen von Änderungen aus einem Remote-Repository in ein lokales Repository.

### 21. Was ist der Unterschied zwischen Commit und Push?

**Meine Antwort:** Commit speichert die Änderungen des Projekts im lokalen Git-Repository. Push übertragt gespeicherte Änderungen im  lokalen Git-Repository in das entfernte Repository.

### 22. Was ist der Unterschied zwischen Pull und Pull Request?

**Meine Antwort:** Pull synchronisiert die Änderungen aus einem Remote-Repository und übernimmt sie direkt in das lokale Repository. Pull Request ist die Anfrage um Änderungen von einem Branch in einen Hauptbranch (main) zu übernehmen (vor der Code überprüfung).

### 23. Was bedeutet Clone?

**Meine Antwort:** Das ist eine lokale Kopie eines Remote-Repositories von GitHub, die auf dem Computer gespeichert wird.

### 24. Was macht `git status`?

**Meine Antwort:** Es zeigt den aktuellen Status des Git-Repositories an.

### 25. Was macht `git add`?

**Meine Antwort:** Es fügt geänderte oder neue Dateien dem Staging-Bereich (Index) hinzu und bereitet sie für den nächsten Commit vor.

### 26. Was ist die Staging Area?

**Meine Antwort:** Das ist ein Zwischenspeicher in Git. Sie sammelt vorbereitete Änderungen vor dem nächsten Commit.

### 27. Was macht `git log`?

**Meine Antwort:** Es zeigt die Historie von Commits in einem Git-Repository an.

### 28. Was bedeutet Branch wechseln?

**Meine Antwort:** Das Arbeitsverzeichnis auf den Stand eines bestimmten Branches zu aktualisieren.

### 29. Speichert `git add` bereits eine neue Version?

**Meine Antwort:** Nein, `git add` speichert keine neue Version im Repository. Es bereitet die Änderungen für den nächsten Commit vor. 'git commit' speichert diese Änderungen als neue Version.

### 30. Speichert `git push` deine noch nicht committeten Dateiänderungen?

**Meine Antwort:** Nein, `git push` überträgt bereits committete Änderungen. Uncommittete Änderungen im Arbeitsverzeichnis oder im Staging-Bereich bleiben lokal und werden nicht auf den Server hochgeladen.

---

## 4 · GitHub-Flow praktisch erklären

### 31. Erkläre den GitHub-Flow in einem kurzen Satz.

**Meine Antwort:** Das ist ein leichtgewichtiger, branch-basierter Workflow für die kollaborative Entwicklung. Er hält den Hauptzweig (main) stabil, um Änderungen am Code sicher zu testen, im Team zu besprechen und zu veröffentlichen.

### 32. Ordne die Begriffe zu

| Bedeutung | Git-/GitHub-Begriff |
|---|---|
| Aufgabe | Issue |
| Arbeitszweig | Branch |
| Speicherpunkt | Commit |
| Änderungsantrag | Pull Request |
| Zusammenführen | Merge |

### 33. Welche Richtung beschreibt Push?

**Meine Antwort:** Vom lokalen Repository zum Remote-Repository.

### 34. Welche Richtung beschreibt Pull?

**Meine Antwort:** Vom Remote-Repository zum lokalen Repository.

### 35. Warum sind mehrere sinnvolle Commits oft besser als ein einziger riesiger Commit?

**Meine Antwort:** Um Änderungen leicht zu verfolgen, Fehler schneller zu finden, einzelne Schritte rückgängig zu machen und den Code einfacher zu prüfen.

### 36. Nenne ein Beispiel für eine gute Commit-Nachricht.

```text
Neues Feature.
```

### 37. Warum ist die Commit-Nachricht `update` wenig hilfreich?

**Meine Antwort:** Weil sie keine konkrete Information über Änderungen geben. 

---

## 5 · Markdown und README

### 38. Überschrift Ebene 1

Ergänze darunter eine Markdown-Überschrift der Ebene 1:

# Überschrift der Ebene 1

### 39. Ungeordnete Liste

Erstelle eine Liste mit mindestens drei Begriffen aus dieser Lernsession:

- Commit
- Pull Request
- Push

### 40. Link

Erstelle einen funktionierenden Markdown-Link zu GitHub oder Microsoft Learn:

[Microsoft Learn]([https://learn.microsoft.com](https://learn.microsoft.com/de-de/plans/50nptqtxxnr6mo?learnerGroupId=50eac53d-2c0e-4ee4-8787-65247fd217f6&source=docs))

### 41. Bild

Schreibe die Markdown-Syntax für ein Bild mit Alternativtext:

![GitHub-Logo](https://seeklogo.com/images/G/github-logo-7880D80B8D-seeklogo.com.png)

### 42. Inline-Code

Schreibe `git status` als Inline-Code in einem sinnvollen Satz:

Mit dem Befehl 'git status' kann den Zustand einer Dateien überprüfen werden.

### 43. Codeblock

Ergänze mindestens drei Git-Befehle in diesem Codeblock:

```bash
git status
git add
git log
```

### 44. Was sollte ein gutes Portfolio-README mindestens leisten?

**Meine Antwort:** Es sollte das Projekt klar beschreiben, den Zweck erklären und welche Technologien benutzt werden.

---

## 6 · Mein fachlicher Lernnachweis

### Was habe ich heute über Git und GitHub gelernt?

- Unterschied zwischen Git und GitHub
- Die wichtigsten Befehle von GitHub
- Wichtige Begriffe von GitHub
- Grundlagen der Mardown

### Was habe ich heute praktisch umgesetzt?

- Repository erstellen
- Übung "Kommunizieren mittels Markdown"

### Meine konkrete Verbesserung aus dem Selbst- oder Peer-Check

- Ich kann besser und einfacher in GitHub arbeiten
- Ich weis, wie ich Markdown benutzen kann

### Mein nächster Portfolio-Schritt

Lehrnjournal ausfüllen

---

## 7 · Microsoft Learn · Abschlusskontrolle

- [x] **Einführung in GitHub**: Übung, Modulbewertung und Zusammenfassung abgeschlossen
- [x] **Effektive Kommunikation auf GitHub mithilfe von Markdown** abgeschlossen
- [x] Ich habe meinen Lernfortschritt / meine Modulbewertung kontrolliert.

## 8 · Begriffe · deutsche Merkhilfe

Fülle die zweite Spalte mit einer kurzen deutschen Merkhilfe aus.

| Begriff | Deutsche Merkhilfe |
|---|---|
| Issue | Aufgabe |
| Branch | Zweig |
| Commit | Speicherung |
| Push | Hochladen |
| Pull | Herunterladen |
| Pull Request | Änderungsvorschlag |
| Review | Prüfung |
| Merge | Zusammenführung |
| Clone | Kopie |
| Repository | Projektordner |

---

## 9 · Selbstcheck

- [x] Ich kann **Git** und **GitHub** unterscheiden.
- [x] Ich kann **Issue → Branch → Commit → Pull Request → Merge** erklären.
- [x] Ich kenne den Unterschied zwischen **Commit** und **Push**.
- [x] Ich kenne den Unterschied zwischen **Pull** und **Pull Request**.
- [x] Ich kann Überschriften, Listen, Links, Bilder und Codeblöcke in Markdown verwenden.
- [x] Mein README wird auf GitHub korrekt gerendert.
- [x] Ich habe mindestens eine konkrete Verbesserung umgesetzt.
- [x] Ich habe meine Änderung mit einer aussagekräftigen Commit-Nachricht dokumentiert.

## Meine Commit-Nachricht für diese Abgabe

```Die Frage beantwortet und gelernte Information zusammengefast```
