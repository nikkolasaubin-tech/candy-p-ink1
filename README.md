# Candy p.ink — maquette V2

Site statique (HTML + CSS + un peu de JavaScript, sans build) pour le studio de tatouage fine line à Lyon.

## Lancer en local

Ouvrir `index.html` dans un navigateur. Aucune dépendance à installer.

## Pages

| Fichier | Contenu |
|---|---|
| `index.html` | Accueil : hero avec logo, univers, réalisations, flashs, premier tatouage, déroulé, parcours de réservation |
| `tatouages.html` | Galerie avec filtres par style (JavaScript) |
| `flashs.html` | Flashs numérotés, étapes de réservation |
| `a-propos.html` | Présentation (texte à rédiger) |
| `faq.html` | Questions fréquentes, repliables |
| `contact.html` | Formulaire (projet ou flash), infos pratiques |
| `tarifs.html` | Critères de prix, délais, flashs |
| `avis.html` | Témoignages (emplacements, aucun avis inventé) |
| `coulisses.html` | Galerie de coulisses avec filtre visuel |
| `mentions-legales.html` | Modèle à compléter |
| `404.html` | Page d'erreur (GitHub Pages l'utilise automatiquement) |

Toutes les pages prévues sont présentes. Les textes légaux, les photos et les témoignages restent à fournir.

## Design

- Logo : `img/logo.png`, utilisé dans l'en-tête, le hero et le pied de page.
- Palette : rose vif `#F83391`, bubblegum `#F78AB9`, blush `#FFD9EA`, butter `#FFDB62`, plum `#2A1823`, milky `#FFF8F9`. Elle reprend la charte V1 et les couleurs du logo, à valider.
- Typographies : Lobster Two (titres signature), Montserrat (titres), DM Sans (texte). Choix provisoire.
- Style « sticker » : bordures épaisses, ombres décalées, étoiles animées, bandeau défilant. Les animations sont désactivées si l'utilisateur préfère moins de mouvement.

## À compléter avant mise en ligne

- Adresse, horaires et email (marqués « À compléter »).
- Présentation de la tatoueuse (page À propos).
- Photos réelles : les emplacements « Photo à venir » et « Dessin à venir » sont à remplacer.
- Mentions légales (lien provisoire vers `#`).
- Adresse email réelle : constante `STUDIO_EMAIL` dans `contact.html`.
- Handle Instagram : `@barbieink.lyon` est encore utilisé partout, à remplacer par le compte lié au nouveau nom.

## Points à vérifier

- Nom « Candy p.ink » : aucune marque ni studio trouvé dans ma recherche, mais il reste à vérifier à l'INPI et sur les réseaux.
- Logo : vérifier son origine et les droits d'utilisation commerciale avant publication.
- Domaine : barbie.ink contient la marque Barbie (Mattel). À remplacer par un domaine lié à « Candy p.ink », par exemple candypink.fr, à vérifier sur whois.afnic.fr.
