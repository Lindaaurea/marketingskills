# AI‑SEO / AEO (GEO/LLMO) Audit – myTalentscout.de
**Datum:** 2026‑03‑17  
**Scope:** `mytalentscout.de` (fokussiert auf AI‑Zitierungen in Google AI Overviews, ChatGPT, Perplexity, Claude, Gemini, Copilot)  
**Quellen:** Seiteninhalte aus der bereitgestellten Extraktion für [/why-us](https://mytalentscout.de/why-us) und [/collab-with-us](https://mytalentscout.de/collab-with-us) sowie `robots.txt`.

---

## 1) Executive Summary (kurz)

### Wichtigste Befunde
- **AI‑Crawler Zugriff**: `robots.txt` erlaubt alles (`User-agent: *` / `Allow: /`) → **kein offensichtliches Blockieren** von AI‑Bots.  
- **Sitemap**: `https://mytalentscout.de/sitemap.xml` und `https://www.mytalentscout.de/sitemap.xml` liefern **404** → **schneller technischer Win** (Sitemap bereitstellen + verlinken).
- **/why-us**: Sehr starke **Trust‑Signale** (viele Testimonials + harte Zahlen), aber zu wenig **extrahierbare Answer‑Blöcke** (Definition/FAQ/Struktur) → großes Potenzial für AI‑Zitate.
- **/collab-with-us**: Praktisch nur Formular, kaum Content → wird selten zitiert. Mit kurzem Intro + Mini‑FAQ wird die Seite „verständlich“ und kann trotzdem helfen (UX + AEO).

### Zielzustand
In AI‑Antworten nicht nur „auftauchen“, sondern **als Quelle zitiert** werden. Das erreichst du über:
- **Struktur (Extractability)**: klare, kurze Antwortblöcke (40–60 Wörter), Tabellen, nummerierte Steps, FAQ.
- **Authority (Cite‑worthiness)**: konkrete Zahlen + Quellen + Autor/Expertise + Aktualität.
- **Presence (Where AI looks)**: Drittquellen (Profiles/Reviews/Communities/YouTube) ergänzen.

---

## 2) Technische Checks

### robots.txt
- **Status:** erlaubt alles
- **URL:** `https://mytalentscout.de/robots.txt`
- **Inhalt:**
  - `User-agent: *`
  - `Allow: /`
- **Empfehlung:** Zusätzlich `Sitemap: https://mytalentscout.de/sitemap.xml` aufnehmen (sobald vorhanden).

### sitemap.xml
- **Status:** aktuell nicht unter den Standard-URLs erreichbar (404)
- **Empfehlung (hoch):**
  - Sitemap generieren und unter `https://mytalentscout.de/sitemap.xml` bereitstellen
  - In `robots.txt` referenzieren
  - Optional: in Google Search Console einreichen

---

## 3) AI‑SEO Framework (kurz, praktisch)

### 3.1 Struktur – Content „extractable“ machen
AI‑Systeme extrahieren **Passagen**, nicht „Seiten“. Bewährte Blöcke:
- **Definition‑Block** für „Was ist …?“
- **Step‑by‑step** (nummerierte Liste) für „Wie …?“
- **Vergleichstabellen** für „X vs Y“ / „Alternativen“
- **Pros/Cons** für Evaluationsfragen
- **FAQ** mit natürlich formulierten Fragen
- **Statistik‑Blöcke** mit Quelle und Datum

### 3.2 Authority – Content „citable“ machen
Starke Hebel:
- **Zahlen/Statistiken** (immer mit Datum)
- **Quellenlinks** (möglichst Primärquellen)
- **Expert Quotes** mit Name + Rolle + Firma
- **Autor‑Bio** (Recruiting‑Expertise)
- **Freshness** („Zuletzt aktualisiert …“)

### 3.3 Presence – dort auftauchen, wo AI zitiert
Für B2B/Recruiting oft relevant:
- Branchen‑Roundups / Gastbeiträge
- Review-/Profilseiten (falls passend)
- YouTube‑How‑to Content (wird häufig zitiert)
- Communities (authentisch, hilfreich; keine Promo‑Posts)

---

## 4) Seiten-Audit: `/why-us`
**URL:** [/why-us](https://mytalentscout.de/why-us)

### Was bereits sehr gut ist (weiter ausbauen)
- **Konkrete Zahlen**: „97% Passgenauigkeit“, „3,5% Drop-out Rate“, „seit 2017“, „>100 Projekte/Jahr“
- **Viele Kundenstimmen** mit Namen/Rollen/Firmen → starke E‑E‑A‑T‑Signale
- Klarer Fokus auf **Software** und **IT‑Infrastruktur**

### Hauptproblem aus AEO‑Sicht
Die Seite enthält viel überzeugenden Inhalt, aber zu wenig **kompakt strukturierte** Passagen, die KI leicht als „Zitat/Quelle“ nutzen kann.

### Konkrete Optimierungen (Priorität hoch)
1. **Definition‑Block in den ersten 40–60 Wörtern**
2. **Kernkennzahlen als eigener Statistik‑Block** (mit „Stand: Jahr“)
3. **FAQ‑Sektion** (3–6 Fragen)
4. **Überschriften als Suchfragen** formulieren (H2/H3)
5. **Freshness‑Signal**: „Zuletzt aktualisiert …“ sichtbar

### Textvorschläge zum Einfügen (Copy‑Paste)

#### A) Definition‑Block (ganz oben, direkt nach H1)
myTalentscout ist eine auf IT spezialisierte Personalberatung und Vermittlung für Software‑ und IT‑Infrastruktur‑Rollen. Wir unterstützen Unternehmen dabei, Entwickler:innen, DevOps‑ und Tech‑Profile zu finden – mit Fokus auf Passgenauigkeit, Speed und nachhaltiges Recruiting. Seit 2017 setzen wir jährlich über 100 Vermittlungsprojekte um.

#### B) Statistik‑Block („Kernkennzahlen“)
Kernkennzahlen (Stand: 2026): 97 % Passgenauigkeit der vermittelten Kandidat:innen und 3,5 % Drop‑out‑Rate in der Probezeit. Seit 2017 setzen wir pro Jahr über 100 Personalberatungs‑ und Personalvermittlungsprojekte erfolgreich um.

#### C) FAQ‑Vorschläge (kurz, extrahierbar)
**Wie schnell liefert myTalentscout erste Kandidatenprofile?**  
In der Regel erhältst du innerhalb von 2–3 Wochen nach Briefing erste passende Profile; je nach Rolle und Markt kann es schneller gehen.

**Für welche IT‑Rollen ist myTalentscout spezialisiert?**  
Schwerpunkt: Software‑Entwicklung (z. B. Fullstack) und IT‑Infrastruktur (z. B. DevOps), inklusive Remote‑Kontext.

**Warum ist das Team fachlich so passgenau?**  
Alle Recruiter:innen durchlaufen ein intensives IT‑Schulungsprogramm und lernen Programmieren sowie die Grundlagen unserer Spezialgebiete.

**Wie stellt ihr Qualität im Prozess sicher?**  
Wir arbeiten mit klaren Briefings, sorgfältiger Vorauswahl und transparentem Austausch, damit Profile wirklich zu Rolle, Tech‑Stack und Team passen.

### Schema/Structured Data (Empfehlung)
- **FAQPage** für die FAQ‑Sektion (nach Implementierung)
- **Organization** (siteweit)
- Optional (mit Vorsicht): **Review** / **AggregateRating** – nur wenn sauber modellierbar, ohne „fake reviews“

---

## 5) Seiten-Audit: `/collab-with-us`
**URL:** [/collab-with-us](https://mytalentscout.de/collab-with-us)

### Beobachtung
Seite ist nahezu vollständig ein Formular. Das ist okay für Conversion, aber schwach für SEO/AEO, weil kaum zitierbarer Text vorhanden ist.

### Ziele für diese Seite
- Nutzer:innen verstehen in 10 Sekunden: **Worum geht’s? Was passiert danach?**
- AI/SEO erhält **mindestens einen klaren Kontext‑Block** + Mini‑FAQ (optional)

### Konkrete Optimierungen (Priorität hoch)
1. **Kurzer Intro‑Absatz vor dem Formular** (2–4 Sätze)
2. **Mini‑FAQ unter dem Formular** (3–4 Fragen)
3. Optional: **Betreff als Dropdown** (bessere Lead‑Qualität)

### Textvorschläge zum Einfügen (Copy‑Paste)

#### A) Intro‑Absatz (vor dem Formular)
Du möchtest mit myTalentscout zusammenarbeiten? Beschreibe kurz, worum es geht – z. B. eine konkrete IT‑Position, eine langfristige Recruiting‑Partnerschaft oder ein erstes Kennenlernen. Wir melden uns in der Regel innerhalb von 1–2 Werktagen bei dir zurück.

#### B) Mini‑FAQ (unter dem Formular)
**Wie schnell antwortet myTalentscout?**  
In der Regel innerhalb von 1–2 Werktagen.

**Welche Infos sollte ich mitschicken?**  
Rolle(n), Standort/Remote, Tech‑Stack, Senioritätslevel, grober Zeitplan und Besonderheiten im Team/Projekt.

**Was passiert nach meiner Anfrage?**  
Wir klären in einem kurzen Gespräch Bedarf und Rahmenbedingungen und schlagen dann das passende Vorgehen vor.

### Schema/Structured Data (Empfehlung)
- **FAQPage** (nur wenn die Mini‑FAQ wirklich auf der Seite steht)

---

## 6) Nächste Schritte (empfohlen, 14 Tage)

### Woche 1 (schnelle Wins)
- Sitemap bereitstellen + in `robots.txt` verlinken
- `/why-us`: Definition‑Block + Statistik‑Block + „Zuletzt aktualisiert“-Zeile
- `/collab-with-us`: Intro‑Absatz ergänzen

### Woche 2 (Zitierbarkeit erhöhen)
- `/why-us`: FAQ + FAQ‑Schema
- 1–2 neue Seiten/Artikel erstellen, die AI oft zitiert:
  - „IT‑Recruiting: Definition, Prozess, Kosten, Zeitplan (2026)“
  - „Active Sourcing: Schritt‑für‑Schritt Prozess + Beispiele“
  - „Interne Recruiter vs IT‑Recruiting‑Agentur: Vergleichstabelle“

---

## 7) Links
- Website: `https://mytalentscout.de/`
- Why Us: `https://mytalentscout.de/why-us`
- Collab: `https://mytalentscout.de/collab-with-us`
- Robots: `https://mytalentscout.de/robots.txt`

