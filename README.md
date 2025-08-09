
# Ládanyilvántartó – Supabase (közös adatbázis)

## Fontos
- A TS hiba (`ImportMeta.env`) a `src/vite-env.d.ts`-szal javítva.
- Nincs `vercel.json`, így nem lesz "unused-build-settings" figyelmeztetés.

## Lépések
1) Supabase projekt → másold ki Project URL + anon key
2) Supabase → SQL → futtasd a `schema.sql`-t
3) Vercel → Settings → Environment Variables
   - `VITE_SUPABASE_URL`
   - `VITE_SUPABASE_ANON_KEY`
   (Production + Preview + Development pipálva)
4) Deploy (Upload ZIP) → Framework: Vite → Build: `npm run build` → Output: `dist`
5) Domain hozzákötés, hard refresh
