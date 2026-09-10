# BESS-Market: Agenten-Team auf GitHub

## Stand

Initiale Struktur für https://github.com/maasho/bess-market-ai-ops. Die 15 Rollen in agents/ sind Arbeitsanweisungen. Automatische Agentenläufe sind noch nicht eingerichtet.

## Organisation

GitHub sammelt Aufgaben, Arbeitsergebnisse und Reviews. Die konkrete Ausführung durch ein Agenten-Werkzeug wird nach Auswahl des Repositorys eingerichtet. Ein Issue allein startet noch keinen Agenten.

| Verantwortung | Rolle | Ergebnis | Übergabe |
|---|---|---|---|
| Prioritäten und Aufgabenbriefing | Owner / Teamleitung | Klarer Auftrag mit Abnahmekriterien | Zuständige Fachrolle |
| Technische Sichtbarkeit | SEO Specialist | Befund mit priorisierten Maßnahmen | Content oder Website-Umsetzung |
| Fachliche Grundlagen | Trend Researcher | Quellen mit Datum und belegten Aussagen | Content Creator |
| Wissensartikel DE/EN | Content Creator | Artikelentwurf und CTA | Reality Checker |
| LinkedIn | LinkedIn Content Creator | Post-Entwürfe zum geprüften Artikel | Owner |
| Wirkungsmessung | Analytics Reporter | KPI-Bericht mit Datenlücken | Teamleitung |
| Qualität | Reality Checker | Prüfergebnis und offene Mängel | Owner / zuständige Fachrolle |

Die weiteren Rollen aus `TEAM.md` kommen bei konkretem Bedarf dazu. Zum Start wird ein vollständiger Ablauf mit einem Thema durchgespielt.

## Arbeitsablauf

1. Owner legt ein Issue mit Ziel, verantwortlicher Rolle, erlaubtem Umfang und Abnahmekriterien an.
2. Die ausführende Rolle liest das Briefing, die betreffende Rollendatei und die Projektvorgaben. Tool-Namen in fremden Personas garantieren keine verfügbaren Zugriffe.
3. Ergebnisse werden als Bericht oder Änderung auf einem Aufgaben-Branch vorbereitet. Recherche nennt Quellen und Abrufdatum; fehlende Zugänge und Daten bleiben ausdrücklich als Lücken sichtbar.
4. Ein Pull Request verbindet Auftrag und Ergebnis. Bei Website-Änderungen wird im Website-Projekt `npm run build` ausgeführt; das Ergebnis wird dokumentiert.
5. Der Reality Checker prüft die Abnahmekriterien, Quellen, Sprache und gegebenenfalls die betroffenen Seiten.
6. Der Owner entscheidet über die Übernahme. Veröffentlichung, Versand und Werbeausgaben richten sich nach der ausdrücklichen Autorisierung des Owners.

Empfohlene Board-Spalten: Backlog → Bereit → In Arbeit → Review → Erledigt. Blockierte Aufgaben nennen die konkret fehlende Voraussetzung.

## Geplante Ablage im Ziel-Repository

```text
marketing-team/
  TEAM.md
  GITHUB-START.md
  agents/                 vorhandene Fachrollen
  reports/                Ergebnisse nach Fachbereich
  templates/              Briefing und Ergebnisvorlage
.github/
  ISSUE_TEMPLATE/          nach Repository-Auswahl einrichten
  pull_request_template.md
```

Falls das Ziel-Repository nur die Website enthält, wird dieser Team-Ordner dort ergänzt. Das fremde Repository `agency-agents` bleibt die Referenzsammlung und ist nicht das Ziel für BESS-Market-Änderungen.

## Erste Aufgaben

| Reihenfolge | Aufgabe | Abnahme |
|---|---|---|
| 1 | Ziel-Repository und ausführendes Agenten-Werkzeug festlegen | Repository-Link, Zugriff und Startweg dokumentiert |
| 2 | Rollen und Vorlagen übernehmen | Alle Rollen erreichbar; erstes Issue aus Vorlage angelegt |
| 3 | SEO-Ausgangslage erheben | Belegte Befunde, Datenlücken und drei priorisierte Maßnahmen |
| 4 | Einen Wissensartikel als Pilot erstellen | DE/EN, belastbare Quellen, CTA und Qualitätsprüfung |
| 5 | Zwei LinkedIn-Entwürfe ableiten | Fachlich konsistent zum geprüften Artikel; bereit zur Freigabe |
| 6 | Pilot auswerten und Wiederholung planen | Aufwand, Qualitätsmängel und nächster Auftrag dokumentiert |

Wiederkehrende Läufe werden erst nach dem Pilot konkret eingerichtet. Frequenzen aus `TEAM.md` sind dafür die Ausgangsbasis.
