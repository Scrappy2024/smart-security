# Smart‑security.cz — statická „ve výstavbě“ stránka (GitHub Pages)

Tento balíček obsahuje homepage a tři podstránky:
- `/sluzby.html` — přehled poskytovaných služeb
- `/pusobnost.html` — oblasti působnosti
- `/kontakt.html` — kontaktní formulář (Formspree) + kontakty

## Rychlé nasazení
1. Nahrajte všechny soubory do kořene repozitáře (branch `main`).
2. V **Settings → Pages** zvolte *Deploy from a branch* → `main` → `/ (root)`.
3. V **Custom domain** nastavte `smart-security.cz` a zapněte **Enforce HTTPS**.

## Formspree (kontaktní formulář)
- V souboru `kontakt.html` (a na homepage) nahraďte `action="https://formspree.io/f/xjkolavy_FORM_ID"` svým Form ID (např. `f/abcdwxyz`).  
- Poté commitujte a otestujte odeslání (zobrazí se stavová hláška).

## Indexace (až bude web hotový)
- Změňte v `<head>` meta robots na `index,follow` a upravte/smažte `robots.txt` (odstranit `Disallow: /`).

© Smart‑security.cz


## Mapa působnosti
- Nahrajte soubor s mapou jako `mapa.png` do kořene repozitáře. Bude se zobrazovat na `/pusobnost.html`.
