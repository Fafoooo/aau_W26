# 📚 AAU Klagenfurt — Wintersemester 2026/27

> Alpen-Adria-Universität Klagenfurt · Informatik & Technik

---

## 🗂️ Kurse & Repositories

| # | Kurs | Repo |
|---|------|------|
| 1 | **Lineare Optimierung** | [`aau_26W_Linear_Optimization`](https://github.com/Fafoooo/aau_26W_Linear_Optimization) |
| 2 | **Webtechnologien** | [`aau_26W_Webtechnologien`](https://github.com/Fafoooo/aau_26W_Webtechnologien) |
| 3 | **Logische Programmierung** | [`aau_26W_Logische_Programmierung`](https://github.com/Fafoooo/aau_26W_Logische_Programmierung) |
| 4 | **Rechnernetze** | [`aau_26W_Rechnernetze`](https://github.com/Fafoooo/aau_26W_Rechnernetze) |
| 5 | **Computerlinguistik** | [`aau_26W_Computerlinguistik`](https://github.com/Fafoooo/aau_26W_Computerlinguistik) |
| 6 | **Security Engineering** | [`aau_26W_Security_Engineering`](https://github.com/Fafoooo/aau_26W_Security_Engineering) |

Vorheriges Semester: [`aau_S26`](https://github.com/Fafoooo/aau_S26)

---

## 📋 Modalitäten

Was pro Fach erledigt werden muss. Details in den jeweiligen Repos, verbindlich ist Moodle.

### Lineare Optimierung

- [ ] *noch keine Infos*

### Webtechnologien

- [ ] **Anwesenheit**: prüfungsimmanent, vermutlich max. 2 Fehltermine
- [ ] **Übungsblätter**: ≥ 60 % aller Aufgaben (~8 % der Note)
- [ ] **Klausur 1**: bestehen
- [ ] **Klausur 2**: bestehen (beide Pflicht fürs Projekt)
- [ ] **Projekt** (4er-Gruppe, ab Dezember, Angular): ≥ 60 % der Punkte
  - [ ] Anfangspräsentation
  - [ ] Endpräsentation
  - [ ] Einzelgespräch
- [ ] **KI-Bericht**: pro Aufgabe mit KI-Nutzung ein PDF (Tool + Nutzung)

### Logische Programmierung

- [ ] **Abschlussprüfung**: ~50 % der Note
- [ ] **Tests**: Gewichtung offen
- [ ] **Projekt**: Details folgen
- [ ] **Beteiligung** (optional): Punkte fürs Vorstellen von Lösungen
- Hausaufgaben: keine Abgabe, keine Note, aber Prüfungsstoff
- Tutorials: freiwillig

### Rechnernetze

- [ ] *noch keine Infos*

### Computerlinguistik

- [ ] *noch keine Infos*

### Security Engineering

- [ ] *noch keine Infos*

---

## 🛠️ Setup

```bash
# Alle Repos auf einmal klonen
gh repo list Fafoooo --json name,url \
  -q '.[] | select(.name | startswith("aau_26W_")) | .url' \
  | xargs -I {} git clone {}
```

---

<p align="center">
  <sub>🎓 WS 2026/27 · Fafoooo</sub>
</p>
