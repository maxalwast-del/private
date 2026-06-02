# ⚙️ Automatisierte Coaching-Workflows

Dieses Dokument enthält vordefinierte Befehlsketten. Kopiere die Prompts bei Bedarf und füttere sie in Claude Code.

## 1. Das Sonntags-Review & Wochenplanung
Führe den Workflow "Wochen-Audit" aus. 
Schritte:
1. Lies logs/journal.md der letzten 7 Tage aus.
2. Gleiche die Performance mit identity/values.md (Jahresziele) ab.
3. Identifiziere den größten Engpass der Woche.
4. Erstelle mir einen konkreten Fokus-Fahrplan für die kommewe Woche inklusive 3 Kernaufgaben, die in identity/bio.md (Standard-Tagesablauf) eingeplant werden können.
```

## 2. Der "Krisen-Modus" (Überforderung / Prokrastination)
Führe den Workflow "Anti-Overwhelm" aus.
Ich bin gerade blockiert/überfordert.
Schritte:
1. Scanne identity/bio.md nach meinen Energieräubern und identity/values.md nach meiner Core-Motivation.
2. Brich mein aktuelles Problem (ich werde es dir gleich nennen) in 3 absolut lächerlich kleine, sofort ausführbare Mikro-Schritte herunter (Dauer je < 5 Min).
3. Gib mir ein direktes, ungeschöntes Feedback, warum ich gerade blockiere.


## 3. Daily Kick-off (Morgen-Briefing)
Führe den Workflow "Daily Kick-off" aus.
Meine heutige Energie liegt bei [1-10], mein Fokus bei [1-10]. Ich habe heute [X] Stunden Zeit für Deep Work.
Schritte:
1. Scanne identity/bio.md, um meine ideale Tagesstruktur (Default Architecture) abzugleichen.
2. Prüfe areas/career_growth.md nach den aktuellen Fokus-Skills/Projekten, die heute Relevanz haben.
3. Erstelle mir einen harten, realistischen Stundenplan für den heutigen Tag. Pass die Komplexität der Aufgaben an meine heutige Energie an (bei Energie < 5: Fokus auf administrative/leichte Aufgaben).

## 4. Post-Work Shutdown & Log
Führe den Workflow "Shutdown" aus.

Schritte:
1. Frage mich nach meinem rohen Gedanken Dump.
2. Analysiere meinen Dump und extrahiere die harten Fakten (Highlights, Engpässe, Metriken).
3. Formatiere das Ergebnis exakt nach der Markdown-Vorlage aus logs/journal.md.
4. Hänge diesen neuen Eintrag automatisch ganz oben an die Historie in logs/journal.md an und committe die Änderung im Git-Repo mit der Commit-Nachricht "daily log [Datum].