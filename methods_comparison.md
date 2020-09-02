# Comparaison des méthodes de modélisation des cheveux
Ce document liste les différentes méthodes existentes et les compare dans un tableau.
## Méthodes
---
## Basé géométrie
Représentation paramérique avec des surfaces, mèches et cylindres. Les surface 2D permettent de représenter des groupes de cheveux tandis que le reste permet de contrôler la position et la forme des cheveux.

Ces méthodes sont simples et rapides, mais permettent seulement des coiffures basiques.
## Basé physique
Génération de cheveux basée sur des simulations physiques à l'aide d'équations physiques.

Les résultats sont bon mais il est difficile de trouver les paramètres permettant d'obtenir un résultat souhaité.
## Basé image
1. Approches avec une seule vue
- Champs d'orientation
A partir d'une image un champs vectoriel est créé et on trace les brins de cheveux à partir du cuir chevelu en suitvant les directions du champs.
- Data driven 
2. Approches avec une plusieur vues (image/vidéo)


## Critères
---
- Forme
    - Long/bouclé/ondulé vs court/raide 
- Mouvement
    - Robuste aux mouvements complexes
- Priorité
    - Temps réel, fidélité visuelle ou balance
- Exigences matérielles
    - Nécessite des fonctionnalités GPU ou a des contraintes matérielles
- Contrôle utilisateur
    - Degré de contrôle et d'intuitivité
- Propriétés
    - Supporte différent types de cheveux (humide, épais, raide, etc)

## Comparaison
---
| Méthode | Forme | Mouvement | Performance | Fidélité visuelle | Exigences matérielles | Contrôle utilisateur | Propriétés |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| Méthode A |  |  |  |  |
| Méthode B |  |   |  |  |
| Méthode C |  |   |  |  |
| Méthode D |  |   |  |  |
| Méthode E |  |   |  |  |
| Méthode F |  |   |  |  |
| Méthode G |  |   |  |  |

## Références
<a id="1">[1]</a> 
Kelly Ward, Florence Bertails, Tae-Yong Kim, Stephen R. Marschner, Marie-Paule Cani, et al.. A Survey on Hair Modeling: Styling, Simulation, and Rendering IEEE Transactions on Visualization and Computer Graphics, Institute of Electrical and Electronics Engineers, 2007, 13 (2), pp.213-234.
ff10.1109/TVCG.2007.30
