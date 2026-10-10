# 📚 AAU Klagenfurt — Wintersemester 2026/27

> Alpen-Adria-Universität Klagenfurt · Informatik & Technik

---

## 🗂️ Kurse & Repositories

| # | Kurs | Repo |
|---|------|------|
| 1 | **Lineare Optimierung** | [`aau_26W_Linear_Optimization`](https://github.com/Fafoooo/aau_26W_Linear_Optimization) |
| 2 | **Webtechnologien** | [`aau_26W_Webtechnologien`](https://github.com/Fafoooo/aau_26W_Webtechnologien) |
| 3 | **Logische Programmierung** | [`aau_26W_Logische_Programmierung`](https://github.com/Fafoooo/aau_26W_Logische_Programmierung) |

Vorheriges Semester: [`aau_S26`](https://github.com/Fafoooo/aau_S26)

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
