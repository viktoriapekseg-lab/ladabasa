
# Ládanyilvántartó – Supabase (közös adatbázis) – Mobil carousel navigációval

## Újdonságok
- Mobilon **vízszintes carousel/scroll-snap** a fő nézetekhez (Mozgások / Egyenlegek / Partnerek / Beállítások).
- Asztali nézetben marad a **füles (tabs)** navigáció érzés (gombokkal), a tartalom a kiválasztott lap szerint jelenik meg.
- Alsó pager (pontok) és bal/jobb léptető nyilak mobilon.
- Megmaradtak a korábbi mobilos finomítások.

## Telepítés
1) Supabase → futtasd a `schema.sql`-t (ha még nem tetted).
2) Vercel → Env Vars: `VITE_SUPABASE_URL`, `VITE_SUPABASE_ANON_KEY` (Prod/Preview/Dev).
3) Build: Vite (`npm run build`) → Output: `dist`.

## Fejlesztés
`npm i` → `npm run dev`
