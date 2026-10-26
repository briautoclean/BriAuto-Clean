# Photos avant / après retirées du site

Retirées du « Mur des exorcismes » le 26 octobre 2026. Les photos sont toujours dans le dossier `img/` :

| Photo | Avant | Après |
|---|---|---|
| Volant et commodos | `img/avant-volant-commodos.webp` | `img/apres-volant-commodos.webp` |
| Plancher arrière | `img/avant-plancher-arriere-sale.webp` | `img/apres-plancher-arriere-propre.webp` |
| Boîte à gants et tapis | `img/avant-boite-a-gants-rayee.webp` | `img/apres-boite-a-gants-et.webp` |

Pour en remettre une : copier sa ligne ci-dessous dans `index.html`, dans `<div class="grille-mur" id="murGrille">`.

```html
<button type="button" class="carte" aria-pressed="false" aria-label="Volant et commodos : voir l’après"><span class="retourne"><span class="face avant"><img src="img/avant-volant-commodos.webp" alt="" decoding="async"><span class="etiquette">Avant · volant</span><span class="appel">Touchez pour exorciser</span></span><span class="face apres"><img src="img/apres-volant-commodos.webp" alt="" decoding="async"><span class="etiquette">Après · volant</span></span></span></button>
<button type="button" class="carte" aria-pressed="false" aria-label="Plancher arrière : voir l’après"><span class="retourne"><span class="face avant"><img src="img/avant-plancher-arriere-sale.webp" alt="" decoding="async"><span class="etiquette">Avant · plancher</span><span class="appel">Touchez pour exorciser</span></span><span class="face apres"><img src="img/apres-plancher-arriere-propre.webp" alt="" decoding="async"><span class="etiquette">Après · plancher</span></span></span></button>
<button type="button" class="carte" aria-pressed="false" aria-label="Boîte à gants et tapis : voir l’après"><span class="retourne"><span class="face avant"><img src="img/avant-boite-a-gants-rayee.webp" alt="" decoding="async"><span class="etiquette">Avant · gants et tapis</span><span class="appel">Touchez pour exorciser</span></span><span class="face apres"><img src="img/apres-boite-a-gants-et.webp" alt="" decoding="async"><span class="etiquette">Après · gants et tapis</span></span></span></button>
```
