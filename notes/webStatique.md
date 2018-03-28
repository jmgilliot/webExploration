Web statique

# De quoi parle-t-on ?

Un site web statique est un site généré à partir d'une arborescence de contenu (textes et médias). À la différence d'un CMS, le contenu n'est pas modifiable directement sur le site. Il s'agit donc bien de sites de consultation, pas de site à vocation participative. Malgré tout, nombre de sites d'informations ont été développés avec des CMS, en tant que solution par défaut pendant de nombreuses années, solution considérée comme plus conviviale.
On peut faire l'analogie de la différence entre CMS et web statique avec la différence entre traitement de texte et Latex. Latex et Web statique redeviennent populaires de par leurs qualités intrinsèques, mais également du fait que les environnements de développement deviennent plus conviviaux.

>En quelques années, les gestionnaires de contenu statique, Jekyll en tête sont devenus très populaires, de Google à Netflix en passant par Mailchimp, Mapbox ou NodeJS, ils sont partout et sont devenus le choix de la raison pour les sites de contenus à fort trafic. Leurs usages évoluent et de nouveaux services dédiés viennent enrichir et faciliter l’expérience utilisateur des contributeurs et des développeurs.

>D'après [Frank Taillandier][mouvance statique]

Il facilite la cohérence et l'évolution de sites de documentation, en permettant de passer directement d'une structure cohérente basée sur des textes rédigés de manière structurée à un site agréable à consulter.

Il se base pour cela sur des outils de compilation, devenus matures, permettant d'alléger la rédaction, de gérer la structuration et la mise en page du site de manière explicite et découplée.

La maintenance est également facilitée puisqu'il n'est plus nécessaire de gérer la configuration et la mise à jour d'un CMS.

Il est possible de passer d'un [site basé sur un CMS à un site statique](https://www.netlify.com/blog/2016/03/10/go-static-without-losing-your-server/).

[mouvance statique]: https://frank.taillandier.me/2016/03/08/les-gestionnaires-de-contenu-statique/
[drupal statique]: https://www.netlify.com/blog/2016/03/10/go-static-without-losing-your-server/

## Comment faire ?
les [Pages Github][page github] sont un excellent exemple de création de web statique. Les pages écrites en Markdown déversées dans un répertoire spécifique sont automatiquement compilées et publiées sur un site statiques d'un utilisateur ou d'une institution.
Il est ensuite possible d'aller plus loin en utilisant toutes les fonctionnalités de l'outil qui assure cette publication, à savoir [Jekyll][jekyll]

[page github]: https://pages.github.com/
[jekyll]: https://jekyllrb.com/
