# Kairn (ex « Mes tickets »)

Outil de ticketing perso (projets, tâches, OP commerciales, calendrier, chronologie), inspiré de Wrike.

- Une seule page : `index.html`
- Données enregistrées sur Supabase (projet `mes-tickets`), chaque compte ne voit que ses propres données (RLS).
- La clé présente dans le code est la clé publique « anon » : elle est faite pour être dans le navigateur, la sécurité repose sur les règles RLS.

Mise en ligne : chaque push sur `main` met le site à jour (GitHub Pages ou Netlify).

Site : https://lamoongit.github.io/mes-tickets/
