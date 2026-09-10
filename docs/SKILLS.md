# Skills und Nutzung

Die 15 bestehenden Fachrollen haben jeweils einen BESS-Market-Spezialskill. Zwei gemeinsame Skills unterstützen Quellenprüfung und Lernen. Alle 17 Skills liegen versioniert in .agents/skills/; die eindeutige Zuordnung steht in [skill-map.json](../marketing-team/skill-map.json).

| Rolle | Primärer Skill |
|---|---|
| [SEO und Suchintention](../marketing-team/agents/marketing-seo-specialist.md) | [bess-seo-audit](../.agents/skills/bess-seo-audit/SKILL.md) |
| [Technischer BESS-Content](../marketing-team/agents/marketing-content-creator.md) | [bess-technical-content](../.agents/skills/bess-technical-content/SKILL.md) |
| [LinkedIn-Fachkommunikation](../marketing-team/agents/marketing-linkedin-content-creator.md) | [bess-linkedin-editorial](../.agents/skills/bess-linkedin-editorial/SKILL.md) |
| [KI-Sichtbarkeit messen](../marketing-team/agents/marketing-ai-citation-strategist.md) | [bess-ai-visibility](../.agents/skills/bess-ai-visibility/SKILL.md) |
| [Markt- und Regulierungsrecherche](../marketing-team/agents/product-trend-researcher.md) | [bess-market-research](../.agents/skills/bess-market-research/SKILL.md) |
| [Funnel und KPI-Analyse](../marketing-team/agents/support-analytics-reporter.md) | [bess-funnel-analytics](../.agents/skills/bess-funnel-analytics/SKILL.md) |
| [Maschinenlesbare Inhalte](../marketing-team/agents/marketing-aeo-foundations.md) | [bess-machine-readable-content](../.agents/skills/bess-machine-readable-content/SKILL.md) |
| [B2B-Suchkampagnen](../marketing-team/agents/paid-media-ppc-strategist.md) | [bess-paid-search](../.agents/skills/bess-paid-search/SKILL.md) |
| [Werbemittel und Tests](../marketing-team/agents/paid-media-creative-strategist.md) | [bess-ad-creative](../.agents/skills/bess-ad-creative/SKILL.md) |
| [Lifecycle-E-Mails](../marketing-team/agents/marketing-email-strategist.md) | [bess-lifecycle-email](../.agents/skills/bess-lifecycle-email/SKILL.md) |
| [Fachpresse und PR](../marketing-team/agents/marketing-pr-communications-manager.md) | [bess-pr-communications](../.agents/skills/bess-pr-communications/SKILL.md) |
| [Account-Recherche und Ansprache](../marketing-team/agents/sales-outbound-strategist.md) | [bess-account-research](../.agents/skills/bess-account-research/SKILL.md) |
| [Conversion-Experimente](../marketing-team/agents/marketing-growth-hacker.md) | [bess-growth-experiments](../.agents/skills/bess-growth-experiments/SKILL.md) |
| [Compliance-Vorprüfung](../marketing-team/agents/support-legal-compliance-checker.md) | [bess-compliance-triage](../.agents/skills/bess-compliance-triage/SKILL.md) |
| [Ergebnis- und Quellenprüfung](../marketing-team/agents/testing-reality-checker.md) | [bess-quality-review](../.agents/skills/bess-quality-review/SKILL.md) |

## Verwendung

Starte die Agenten-Aufgabe im Checkout dieses Repositorys. Lies AGENTS.md, den Auftrag und das zugehörige Profil. Lade dessen Primärskill, weitere Skills nur passend zur Aufgabe. Beispiel:

> Nutze den SEO Specialist und bess-seo-audit für docs/PILOT.md. Prüfe passende validierte Einträge in memory/INDEX.md. Liefere belegte Befunde, Datenlücken und priorisierte nächste Schritte.

Codex kann repositorylokale Skills unter .agents/skills entdecken; andere Werkzeuge können die SKILL.md-Dateien ausdrücklich als Arbeitsanweisung lesen. Dies installiert keine Kontozugriffe und startet keine autonomen Dienste. In einer Aufgabe außerhalb dieses Repositorys ist dessen Skill-Verfügbarkeit nicht automatisch zugesichert. Siehe [offizielle Skill-Dokumentation](https://learn.chatgpt.com/docs/build-skills).

## Auswahl und Weiterentwicklung

Die Skills sind speziell für die vorhandenen Aufgaben geschrieben und haben konkrete Eingaben, Methoden und Abnahmebedingungen. Keine unbekannten Drittanbieter-Skripte oder globalen Installationen sind nötig. Die Upstream-Personas behalten ihre MIT-Lizenz.

Quellenprüfung und hilfreiche Fachinhalte orientieren sich unter anderem an [Google Search Essentials](https://developers.google.com/search/docs/essentials) und [People-first Content](https://developers.google.com/search/docs/fundamentals/creating-helpful-content), eingesehen am 2026-09-10. Aktuelle Plattformdetails müssen bei konkreten Aufgaben erneut geprüft werden.

[Senior-Standard](SENIOR-STANDARD.md), [Lernprozess](../.agents/skills/bess-learning/SKILL.md) und [Erprobung](SKILL-EVALUATION.md) legen fest, wie Qualität nachgewiesen und verbessert wird. Es gibt noch keinen Nachweis, dass die Skills bessere Geschäftsergebnisse erzielen. Die Fälle sind für die erste Erprobung vorbereitet.
