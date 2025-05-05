# 🎵 AI MUSICWORLD – HITPARADE Plattform / Platform

Willkommen beim offiziellen Repository für das Projekt **AI MUSICWORLD HITPARADE**.  
Welcome to the official repository for the **AI MUSICWORLD HITPARADE** project.

👉 Vorschau / Preview:  
[https://frisetti.github.io/ai-musicworld/hitparade.html](https://frisetti.github.io/ai-musicworld/hitparade.html)

---

## 💡 Projektidee / Project Idea

**Deutsch:**  
Diese Plattform ermöglicht das Hochladen, Bewerten und Weiterleiten von AI-generierter Musik und Videos.  
Ziel ist ein Wettbewerb, bei dem die Community über Songs abstimmt und Inhalte an Medien (Radio/TV) weitergeleitet werden.

**English:**  
This platform allows users to upload, vote on, and forward AI-generated music and videos.  
The goal is a contest-like system where the community votes and selected content is forwarded to media outlets (radio/TV).

---

## 🔐 Authentifizierung / Authentication

**Deutsch:**  
Benutzer sollen sich registrieren und anmelden können.  
Rollen: `admin`, `artist`, `user`

**English:**  
Users should be able to register and log in.  
Roles: `admin`, `artist`, `user`

---

## 🗃️ Datenbankstruktur / Database Structure

**Tabellen / Tables:**

| Tabelle / Table      | Beschreibung / Description                          |
|----------------------|-----------------------------------------------------|
| `users`              | Benutzerkonten / User accounts                      |
| `songs`              | AI-generierte Musik/Videos / Uploaded content       |
| `votes`              | Bewertungen von Nutzern / User votes                |
| `media_requests`     | Anfragen an Medien / Media forwarding requests      |
| `comments`           | Kommentare zu Songs / Comments on songs             |

---

### 📊 Diagramm / Diagram

![Datenbankstruktur](https://github.com/frisetti/ai-musicworld/blob/main/diagramm.png?raw=true)

---

## 🚀 MVP Ziele / MVP Goals

**Deutsch:**
- Login/Registrierung mit Supabase Auth
- Upload von Audio/Video-Dateien
- Öffentliche Songliste mit Voting
- Admin-Panel zur Moderation
- Export von Medienanfragen

**English:**
- Login/Signup via Supabase Auth
- Upload of audio/video content
- Public song list with voting feature
- Admin panel for moderation
- Export of media requests

---

## 🧑‍💻 Entwicklerhinweise / Developer Notes

Wir arbeiten mit externen Entwicklern (z. B. via Fiverr).  
Vorschläge zur Struktur und Erweiterung sind willkommen.

We are collaborating with external developers (e.g. via Fiverr).  
Suggestions for structure and improvements are welcome.

---
