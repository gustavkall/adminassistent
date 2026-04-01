# adminassistent — WORK QUEUE
*Prioritized list. Updated by Claude at session end. Max one ACTIVE item.*

---

## ACTIVE
*(nothing active)*

---

## READY — PRIORITY ORDER

### ACT-001 — Uppföljning Rickard Ekberg
**Priority:** HIGH
**When:** Efter kommunalstyrelsens klartecken onsdag 2026-04-08
**Description:** Boka call/möte sent v15 eller tidigt v16. Inled förhandling om fastigheten.

### ACT-002 — Kommunalstyrelsebeslut onsdag 2026-04-08
**Priority:** HIGH
**Description:** Bevaka och bekräfta att klartecknet ges. Vid positivt beslut: aktivera förhandlingsläge med Forshem Fastigheter och Rickard Ekberg.

### SETUP-001 — Supabase tables
**Priority:** MEDIUM
**Description:** Run scripts/setup-supabase.sql i Supabase SQL Editor. Lägg till env vars i Vercel.

### SETUP-002 — First deploy
**Priority:** MEDIUM
**Description:** Push till main, verifiera Vercel deploy, testa /api/state endpoint.

### SETUP-003 — Seed initial data
**Priority:** LOW
**Description:** Kör scripts/seed.js för att populera initial session + learnings.

---

## COMPLETED

| ID | Task | Date | Outcome |
|----|------|------|--------|
| TEST-001 | Verifiera persistent memory | 2026-03-23 | ✅ End-to-end verifierat. Boot läser state-filer, write-back fungerar. |
| MAIL-001 | Draft till Rickard Ekberg / Vimpelkullen AB | 2026-04-01 | ✅ Draft skapad i Gmail-tråd. Inväntar sändning. |
