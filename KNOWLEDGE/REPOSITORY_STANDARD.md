# REPOSITORY STANDARD
## Asphalt Burn™ Repository Governance Standard

**Version:** 1.0.0  
**Status:** RELEASED  
**Classification:** GOVERNANCE  
**Owner:** Thomas Ridderskamp

---

# Purpose

Dieser Standard definiert den strukturellen Aufbau, die Organisation und die Verwaltung des gesamten Asphalt Burn™ Repositories.

Das Repository bildet die zentrale Wissens-, Dokumentations- und Arbeitsplattform des ABMS.

---

# Repository Principles

Das Repository muss jederzeit:

- logisch aufgebaut
- reproduzierbar
- nachvollziehbar
- wartbar
- versionierbar

sein.

---

# Repository Structure

Das Repository besteht aus drei Ebenen:

## Level 1

Kernel

- ABMS_MASTER.md

---

## Level 2

Governance

- KNOWLEDGE/

Hier befinden sich ausschließlich die verbindlichen Standards.

Diese Ebene ist nach Freigabe als unveränderlicher Governance-Bereich zu behandeln.

---

## Level 3

Runtime

- PROJECTS/
- PRODUCTS/
- SUPPLIERS/
- RELEASES/
- INCIDENTS/
- METRICS/
- AUDITS/
- RISKS/

Hier findet die tägliche operative Arbeit statt.

---

# Directory Rules

Jeder Ordner besitzt einen klar definierten Zweck.

Neue Verzeichnisse dürfen nur angelegt werden, wenn:

- ein fachlicher Bedarf besteht
- keine bestehende Struktur verwendet werden kann
- die Erweiterung dokumentiert wird

---

# File Naming

Dateinamen verwenden ausschließlich:

- Großbuchstaben für Standards
- eindeutige Produkt-IDs
- eindeutige Projekt-IDs
- keine Leerzeichen
- Unterstriche als Trenner

Beispiele:

BRAND_STANDARD.md

AB-CAP-001

ABMS-2026-BRAND-001

---

# Version Control

Alle Änderungen erfolgen über Git.

Versionen werden nachvollziehbar dokumentiert.

Releases werden mit semantischer Versionierung versehen.

Beispiele:

v1.0.0

v1.1.0

v2.0.0

---

# Documentation

Jede strukturelle Änderung dokumentiert mindestens:

- Datum
- Verantwortlicher
- Beschreibung
- Begründung

---

# Repository Hygiene

Nicht zulässig sind:

- doppelte Dateien
- temporäre Dateien
- Betriebssystemdateien
- nicht dokumentierte Strukturen
- ungenutzte Ordner ohne Zweck

---

# Backup

Das Repository wird regelmäßig gesichert.

Backups dürfen niemals das produktive Repository ersetzen.

---

# Runtime Reference

Operative Daten werden ausschließlich innerhalb von:

RUNTIME/

verwaltet.

Governance-Dateien befinden sich ausschließlich in:

KNOWLEDGE/

---

# Governance Rules

1. Strukturänderungen dokumentieren.
2. Keine doppelten Dateien.
3. Standards niemals vermischen.
4. Runtime und Governance strikt trennen.
5. Dateinamen konsistent halten.
6. Git-Versionierung verwenden.
7. Repository regelmäßig prüfen.

---

# Change Policy

Änderungen erfolgen ausschließlich gemäß CHANGE_STANDARD.md.

---

**Status:** RELEASED
