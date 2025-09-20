# Plantilla GitHub Pages — just-the-docs

Aquesta plantilla usa el tema **just-the-docs** (menú lateral, cerca integrada i disseny net).

## Com publicar
1. Crea un repo nou i puja-hi aquest contingut a la branca `main`.
2. A **Settings → Pages**:
   - Source: `Deploy from a branch`
   - Branch: `main` / folder: `/ (root)`
3. Desa i obre la URL que et dona GitHub, p. ex. `https://usuari.github.io/apunts-curs/`.

## Personalitza
- Edita `_config.yml` ► `title`, `description`, `aux_links` i enllaços.
- Afegeix pàgines i ordena-les amb `nav_order`.
- Crea subseccions amb `has_children: true` i `parent:` a les pàgines filles.
- Estils personalitzats a `assets/css/custom.css`.

> No cal `Gemfile` si només publiques amb GitHub Pages; el `remote_theme` ja funciona.