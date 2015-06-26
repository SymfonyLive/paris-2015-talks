# [Symfony Live - Paris 2015](http://paris2015.live.symfony.com/) talks

- All talks are in **french**.
- Comment and rate talks on [joind.in](https://joind.in/event/sflive-paris-2015)

## 10 ans déjà... quid de Symfony 3.0 ?

<dl>
  <dt>Description</dt>
  <dd>La première version Open-Source de Symfony est sortie il y a 10 ans en octobre 2005. La sortie de Symfony 3.0 est prévue pour fin novembre 2015. Comment la core team gère-t-elle cette nouvelle version ? Comment pouvez-vous rendre vos applications "compatibles" avec Symfony 3.0 dès aujourd'hui ? Qu'attendre de cette nouvelle version majeure ? Autant de questions auxquelles j'apporterai des réponses.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Fabien Potencier](https://connect.sensiolabs.com/profile/fabpot)  
![github](icon/github.png) [@fabpot](https://github.com/fabpot)  
![twitter](icon/twitter.png) [@fabpot](https://twitter.com/fabpot)

---

## Développer avec le SyliusResourceBundle

<dl>
  <dt>Description</dt>
  <dd>Au cours de son développement Sylius, l'équipe s’est rendu compte qu’elle dupliquait énormément de code pour gérer ses CRUDs. Ne voulant pas réinventer Symfony ou utiliser un admin generator, elle décida de créer un bundle simple et flexible: SyliusResourceBundle. Je présenterai comment gérer ses CRUDs avec ce bundle en écrivant le minimum de code et, surtout, sans en dupliquer! Il a été pensé afin de pouvoir supporter plusieurs types de drivers (DoctrineORM, PHPCR). De plus, il permet de construire rapidement une API grâce au FOSTRestBundle. Je mettrai en avant l’ensemble des composants utilisés par ce bundle comme Doctrine. Il facilite la configuration le ResolveDoctrineTargetEntitiesPass ainsi que la création de MappingDriver. Il utilise aussi l’EventDispatcher: des évènements sont soulevés lorsque une action est exécutée sur une ressource. Il apporte aussi de nouveaux FormType ou FormExtension comme la CollectionExtension qui permet de gérer ses forms collection (js inclus).</dd>
</dl>

[Slides](https://slideshare.net/ArnaudLanglade/dvelopper-avec-le-sylius-resourcebundle)  
[Video](https://youtu.be/O8jzsNVFQHg)

By [Arnaud Langlade](https://connect.sensiolabs.com/profile/arn0)  
![github](icon/github.png) [@aRn0D](https://github.com/aRn0D)  
![twitter](icon/twitter.png) [@_arn0d](https://twitter.com/_arn0d)

---

## Repousser les limites : HTTP cache et utilisateurs connectés

<dl>
  <dt>Description</dt>
  <dd>Tu utilises le cache HTTP mais tu te heurtes à ses limites ? Nous présenterons différentes manières de cacher du contenu personnalisé. Au travers du concept du "user context", nous verrons comment mutualiser du cache entre des utilisateurs connectés et partageant le même profil de permission. Nous étudierons également les Edge Side Includes (ESI) et comment cacher des fragments différemment. Ces concepts sont rendus possibles avec Varnish et le composant HttpCache de Symfony, grâce à FOSHttpCacheBundle, que des projets comme le CMS Open Source eZ Publish utilisent.</dd>
</dl>

[Slides](http://lolautruche.github.io/ez/going-crazy-with-caching.html)  
[Video](https://youtu.be/XD9OVkb__wk)

By [David Buchmann](https://connect.sensiolabs.com/profile/dbu)  
![github](icon/github.png) [@dbu](https://github.com/dbu)  
![twitter](icon/twitter.png) [@dbu](https://twitter.com/dbu)

And [Jérôme Vieilledent](https://connect.sensiolabs.com/profile/lolautruche)  
![github](icon/github.png) [@lolautruche](https://github.com/lolautruche)  
![twitter](icon/twitter.png) [@jvieilledent](https://twitter.com/jvieilledent)

---

## Meetic backend mutation with Symfony

<dl>
  <dt>Description</dt>
  <dd>Comment Meetic opère son changement technologique sur son SI. De la création d’API jusqu’à la mise en place d’une démarche qualité tout en passant par l'adoption du Behavior Driven Development, vous saurez tout sur notre parcours, sur les problématiques que nous avons rencontrées, les solutions que nous avons mises en place ainsi que sur le chemin qu'il nous reste à parcourir afin d’appréhender l’avenir avec la plus grande des sérénités. Les thèmes abordés seront : - Comment aborder des changements majeurs sur notre SI sans impacter notre performance globale ? - Migration d'un code monolithique vers des API REST en Sf2, - Exemple de microservices : AB Test, GEO, Permission, Configuration. - Déploiement avec Composer, Satis, Sf2 et Capistrano sur des centaines de serveurs, - Démarche Qualité (Back, Front, App) : nos métriques, outils du marché, outils interne, gestion aux changements. - Méthodologie : Agilité, DevOps, TDD, BDD. - Next steps : Kafka, Continuous Delivery.</dd>
</dl>

[Slides](https://slideshare.net/meeticTech/meetic-backend-mutation-with-symfony)  
[Video](https://youtu.be/IH9mk7E7qP8)

By [Joris Calabrese](https://connect.sensiolabs.com/profile/lks)  
![github](icon/github.png) [@lks](https://github.com/lks)  
![twitter](icon/twitter.png) [@joriscalabrese](https://twitter.com/joriscalabrese)

---

## Faites plaisir à vos utilisateurs : surveillez votre prod

<dl>
  <dt>Description</dt>
  <dd>Développer une application Symfony est maintenant chose commune, mais en connaissez-vous vraiment le comportement en production ? Combien de “fatal error” avez-vous générées aujourd'hui ? Quel est le temps de réponse moyen ? Quelle est la charge absorbée ? Au programme : des éléments sur la gestion des erreurs en prod, la configuration et la customisation de Monolog, le stockage des logs avec elastic search et la visualisation kibana, l’alerting avec sentry et enfin la télémétrie avec graphite, pour vous donner des pistes et savoir où intervenir avant que trop d'utilisateurs ne se plaignent, ou pire, vous abandonnent.</dd>
</dl>

[Slides](https://speakerdeck.com/lyrixx/symfony-live-2015-paris-monitorer-sa-prod)  
[Video](https://youtu.be/XrnK4D1SJqo)

By [Grégoire Pineau](https://connect.sensiolabs.com/profile/lyrixx)  
![github](icon/github.png) [@lyrixx](https://github.com/lyrixx)  
![twitter](icon/twitter.png) [@lyrixx](https://twitter.com/lyrixx)

---

## Symfony Debug et VarDumper, ou comment debugger comfortablement

<dl>
  <dt>Description</dt>
  <dd>Il n'y a que des bugs faciles à résoudre ...quand on a de quoi les cerner ! Le développeur PHP dispose de toute une panoplie d'outils pour tracker les situations les plus rocambolesques. Depuis ses débuts, Symfony n'a eu de cesse d'améliorer l'expérience du développeur en proposant des solutions d'accompagnement robustes et génériques. Les connaissez-vous suffisament ? Lors de cette présentation, je vous donnerai les clefs des mécanismes de debugging présents dans Symfony : VarDumper, Web Debug Toolbar, logs, gestionnaire d'erreur fatales et d'exceptions, etc.</dd>
</dl>

[Slides](http://slideshare.net/nicolas.grekas/symfony-debug-vardumper)  
[Video](https://youtu.be/bkklq2ikm4M)

By [Nicolas Grekas](https://connect.sensiolabs.com/profile/nicolas-grekas)  
![github](icon/github.png) [@nicolas-grekas](https://github.com/nicolas-grekas)  
![twitter](icon/twitter.png) [@nicolasgrekas](https://twitter.com/nicolasgrekas)

---

## Construire des applications API-centric avec Symfony

<dl>
  <dt>Description</dt>
  <dd>Au cours de ce talk, je présenterai une architecture moderne qui permet de construire des applications performantes, évolutives et interopérables : un modèle de données dérivé du vocabulaire Schema.org généré avec PHP Schema ; une API REST hypermedia et auto-découvrable (JSON-LD + Hydra) réalisée avec DunglasJsonLdApiBundle (sa première version sera dévoilée lors du Symfony Live) ; sérialisation et validation avancées des données grâce aux nouvelles fonctionnalités du composant Serializer de Symfony 2.7 et du Validator ; authentification stateless (cookie-less) avec JSON Web Token et LexikJWTAuthenticationBundle ; clients divers et variés avec AngularJS, Guzzle, Twig, des applications mobiles natives, des logiciels métiers etc ; BDD et web acceptance testing avec Behat, Mink et Behatch Le talk sera didactique et accessible aux développeurs Symfony de tous niveaux. La construction d'une micro-application suivant cette architecture sera présentée pas à pas.</dd>
</dl>

[Slides](http://dunglas.fr/slides/sf-live-2015/)  
[Video](https://youtu.be/uI8Dr-Kt6p4)

By [Kévin Dunglas](https://connect.sensiolabs.com/profile/dunglas)  
![github](icon/github.png) [@dunglas](https://github.com/dunglas)  
![twitter](icon/twitter.png) [@dunglas](https://twitter.com/dunglas)

---

## Le DIC, ce chef d'orchestre!

<dl>
  <dt>Description</dt>
  <dd>L'utilisation du conteneur d'injection de dépendances (DIC) se résume pour les applications les plus simple a créer des fichiers de configuration XML/YAML. Cependant sa force réside dans la flexibilité qu'il permet d'apporter à la configuration, et l'intégration d'un bundle dans une application. Dans cette présentation, nous reviendrons sur les caractéristiques importantes du conteneur d'injection de dépendance dans une application Symfony, puis nous verrons des exemples d'utilisation plus avancée. Je souhaite vous donner quelques clé pour créer de meilleurs bundles réutilisable et donner plus de flexibilité à votre application.</dd>
</dl>

[Slides](https://speakerdeck.com/adrienbrault/le-dic-ce-chef-dorchestre)  
~~Video~~

By [Adrien Brault](https://connect.sensiolabs.com/profile/adrienbrault)  
![github](icon/github.png) [@adrienbrault](https://github.com/adrienbrault)  
![twitter](icon/twitter.png) [@AdrienBrault](https://twitter.com/AdrienBrault)

---

## Docker dans le développement web et l'intégration continue

<dl>
  <dt>Description</dt>
  <dd>Les containers sont venus bousculer le monde de la virtualisation, et Docker est devenu un outil incontournable. Nous verrons comment l'utiliser avec Symfony et surtout comment l'ajuster pour résoudre les problèmes courants, améliorer les performances ainsi que l’expérience du développeur. Nous nous intéresseront également à son utilisation dans le processus d'intégration continue, nous verrons comment Docker peut simplifier et améliorer l’exécution des tests fonctionnels.</dd>
</dl>

[Slides](http://slides.com/jeremyderusse/docker-dev)  
~~Video~~

By [Jérémy Derussé](https://connect.sensiolabs.com/profile/jderusse)  
![github](icon/github.png) [@jeremy-derusse](https://github.com/jeremy-derusse)  
![twitter](icon/twitter.png) [@jderusse](https://twitter.com/jderusse)

---

---

---

# Lightning Talks

## Laisse pas traîner ton log !

<dl>
  <dt>Description</dt>
  <dd>Dites stop aux fichiers de logs qui traînent sur vos machines ! Nous verrons comment faire pour tirer pleinement parti de vos logs grâce à Monolog et surtout à la stack ELK (Elasticsearch / Logstash / Kibana).</dd>
</dl>

[Slides](https://speakerdeck.com/odolbeau/logs-hunting)  
~~Video~~

By [Olivier Dolbeau](https://connect.sensiolabs.com/profile/odolbeau)  
![github](icon/github.png) [@odolbeau](https://github.com/odolbeau)  
![twitter](icon/twitter.png) [@odolbeau](https://twitter.com/odolbeau)

---

## Retour d’expérience : attention chérie, ça va trancher

<dl>
  <dt>Description</dt>
  <dd>Vous vous sentez comme un membre d’équipage dont le navire est sur le point de se briser ? Votre environnement de travail est si triste que vous n’avez plus confiance en l'humanité ? Google vous propose une solution : http://goo.gl/I4jM4n Notre histoire, se déroule au sein d’une équipe technique au bord de l'apoplexie tant en terme humain que technique. Elle va progressivement remonter la pente et gagner ses lettres de noblesses pour enfin brandir son glaive et s’écrier “For The Victory!”. Comment passer d’un monolithe à une architecture microservices (à base de composants Symfony2) ? En quoi l’arrivée d’un chef de projet et de nouveaux process nous a sauvé la mise ? En quoi l’attention porté sur l'humain a favorisé l’émergence d’un collectif technique ? Comment favoriser l’insertion d’une nouvelle personne dans l’équipe ? En quoi l'utilisation pragmatique de technologies reconnues et émergeantes (elk, docker) nous a aidé au jour le jour.</dd>
</dl>

[Slides](https://speakerdeck.com/mediaparttech/attention-cherie-ca-va-trancher)  
~~Video~~

By [Bastien Jaillot](https://connect.sensiolabs.com/profile/bastnic)  
![github](icon/github.png) [@bastnic](https://github.com/bastnic)  
![twitter](icon/twitter.png) [@bastnic](https://twitter.com/bastnic)

---

## Symfony et Sonata Project chez Canal+

<dl>
  <dt>Description</dt>
  <dd>La présentation abordera l’usage de Symfony2, l’organisation du code et l’usage du projet Sonata chez Canal+ pour répondre aux enjeux de la refonte d’une partie de la plateforme web. La plateforme présente de nombreux challenges techniques: SDK, API privée, API publique restful+hal, création de contenus riches, 5 applications différentes avec une base de code commune, etc … Nous expliquerons également comment il a été possible d’améliorer certaines parties de Sonata ainsi que l’approche choisie pour la création de certains composants transverses.</dd>
</dl>

[Slides](https://slideshare.net/3k1n0/thomas-rabaix-symfonylivecanal)  
~~Video~~

By [Thomas Rabaix](https://connect.sensiolabs.com/profile/rande)  
![github](icon/github.png) [@rande](https://github.com/rande)  
![twitter](icon/twitter.png) [@th0masr](https://twitter.com/th0masr)

---

## ElasticSearch dans une infrastructure Symfony2

<dl>
  <dt>Description</dt>
  <dd>Durant cette présentation je vous parlerai d'ElasticSearch avec Elastica et son intégration dans Symfony2. Je commencerai par une présentation de la technologie puis je présenterai nos cas d'utilisations qui ne se limitent pas uniquement à une fonctionnalité de recherche en ligne, j'y intégrerai les nouvelles fonctionnalités d'ElasticSearch comme les Aggregations et Suggester. J'aborderai aussi les problématiques d'ETL via une commande Symfony2, toujours basé sur notre retour d'expériences et notre besoin de performances.</dd>
</dl>

[Slides](https://speakerdeck.com/nicolasbadey/elasticsearch-with-elastica-in-symfony2-architecture)  
~~Video~~

By [Nicolas Badey](https://connect.sensiolabs.com/profile/nico-b)  
![github](icon/github.png) [@NicolasBadey](https://github.com/NicolasBadey)  
![twitter](icon/twitter.png) [@nicolasbadey](https://twitter.com/nicolasbadey)

---

## OpenClassrooms - Le pattern View Model avec Symfony2

<dl>
  <dt>Description</dt>
  <dd>Le pattern View Model est un pattern simple qui permet d’apporter des solutions à beaucoup de problèmes : - Découpler la logique métier de la présentation - Permettre le refactoring - Faciliter les tests - Permettre de paralléliser le travail front et back - Construire des ressources api ... Nous verrons pourquoi et comment utiliser le pattern View Model avec Symfony2 et comment nous l'utilisons chez OpenClassrooms</dd>
</dl>

[Slides](https://slideshare.net/RomainKuzniak/le-pattern-view-model-avec-symfony2)  
~~Video~~

By [Kuzniak Romain](https://connect.sensiolabs.com/profile/romainkuzniak)  
![github](icon/github.png) [@romainkuzniak](https://github.com/romainkuzniak)  
![twitter](icon/twitter.png) [@TurnItUpMethod](https://twitter.com/TurnItUpMethod)

---

## Une API et une admin en moins de 10 minutes ? Challenge accepted!

<dl>
  <dt>Description</dt>
  <dd>Créer une API REST... Une mission simple en apparence, mais pouvant s'avérer chronophage, et ce même avec certains bundles reconnus tels le FOSRestBundle. Heureusement, d'autres bundles existent, privilégiant les conventions par delà la configuration, ce qui est le cas du [StanLemon/RestBundle](https://github.com/stanlemon/rest-bundle). Développons ensemble, en une dizaine de minutes, une API REST pleinement fonctionnelle, et implémentons y une interface d'administration basée sur [ng-admin](https://github.com/marmelab/ng-admin).</dd>
</dl>

[Blog post](http://marmelab.com/blog/2015/02/24/ngadmingeneratorbundle-create-javascript-admin-panel-rest-api-symfony2-in-minutes.html)  
~~Video~~

By [Jonathan Petitcolas](https://connect.sensiolabs.com/profile/jpetitcolas)  
![github](icon/github.png) [@jpetitcolas](https://github.com/jpetitcolas)  
![twitter](icon/twitter.png) [@Sethpolma](https://twitter.com/Sethpolma)

---

## Retour d'expérience sur l'édition d'un "Enterprise Software" basé sur Symfony

<dl>
  <dt>Description</dt>
  <dd>Akeneo PIM est un outil de gestion de catalogue produits open-source basé sur Symfony et Doctrine. Le développement a démarré il y a deux ans, l'équipe produit a évolué de 2 à 12 personnes, nous proposons une version communautaire et une version entreprise, utilisées par des clients grands comptes au sein de leur SI. En tant qu'éditeur, nous nous concentrons sur le développement des nouvelles fonctionnalités et la maintenance, les développements spécifiques étant réalisés par un réseau de partenaires intégrateurs. Durant cette conférence, sous la forme d'une rétrospective, nous souhaitons présenter notre retour d'expérience technique et méthodologique sur la création de ce produit. Nous présenterons les avantages d'utiliser Symfony comme socle technique, comment rendre une application extensible et maintenable, les écueils techniques que nous avons rencontrés ainsi que les choix techniques que nous ferions aujourd'hui avec l'expérience acquise.</dd>
</dl>

[Slides](https://slideshare.net/nidup/edition-of-an-enterprise-software-feedback)  
~~Video~~

By [Nicolas Dupont](https://connect.sensiolabs.com/profile/nidup)  
![github](icon/github.png) [@nidup](https://github.com/nidup)  
![twitter](icon/twitter.png) [@duponico](https://twitter.com/duponico)

---

## Symfony pour construire des sites e-commerce de nouvelle génération

<dl>
  <dt>Description</dt>
  <dd>Le modèle très populaire "catalogue de produits en ligne" est largement adressé par des solutions génériques telles que Magento, Prestashop ou Shopify. Depuis quelques années sont arrivés des services tels que AirBnB ou Uber qui représentent la nouvelle génération de sites e-commerce. Ces projets sont des applications connectées de commerce électroniques, elles sont au cœur d'un écosystème e-commerce complexe comprenant les terminaux mobiles, des systèmes de réservation, des objets connectés,.. Or, ces sites innovants sont développés from scratch car les solutions génériques proposent une réponse pour le plus grand nombre mais n'offrent pas la flexibilité et l'interopérabilité attendue. Thelia, en intégrant des composants Symfony, permet à la fois d'avoir les briques nécessaires pour un site ecommerce tel que la gestion du catalogue ou du panier. Mais il permet aussi d'étendre ses capacités grâce à l'ajout du container Symfony ou de l'Event Dispatcher.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Manuel Raynaud](https://connect.sensiolabs.com/profile/mraynaud)  
![github](icon/github.png) [@lunika](https://github.com/lunika)  
![twitter](icon/twitter.png) [@manuraynaud](https://twitter.com/manuraynaud)

---

## BackBee - The NextGen Content Manager

<dl>
  <dt>Description</dt>
  <dd>Backbee est un CMS reposant sur des composants Symfony et Doctrine. Il offre aux contributeurs des sites une expérience ergonomique inédite leur assurant une prise en main rapide et une large autonomie de mise à jour de leurs contenus. La définition souple des droits, des processus de publication et la mise en version systématique des contenus leur assure de plus une grande sécurité éditoriale. BackBee est distribué sous licence open source GPL3.</dd>
</dl>

[Slides](https://speakerdeck.com/mickaelandrieu/backbee-the-next-gen-content-manager-symfonylive-2015)  
~~Video~~

By [Mickaël Andrieu](https://connect.sensiolabs.com/profile/mickaelandrieu)  
![github](icon/github.png) [@mickaelandrieu](https://github.com/mickaelandrieu)  
![twitter](icon/twitter.png) [@mickael_andrieu](https://twitter.com/mickael_andrieu)

And [Charles Rouillon](https://connect.sensiolabs.com/profile/crouillon)  
![github](icon/github.png) [@crouillon](https://github.com/crouillon)

---

---

---

### They wrote about the talks

- on [jolicode.com](http://jolicode.com/blog/symfony-live-2015) by [Loïck Piera](https://connect.sensiolabs.com/profile/pyrech)
- on [blog.eleven-labs.com](http://blog.eleven-labs.com/symfony-live-10-ans-deja/) by [Thierry Thuon](https://connect.sensiolabs.com/profile/lepiaf)
- on [elao.com](http://www.elao.com/fr/blog/symfony-live-2015) by [Richard Hanna](https://connect.sensiolabs.com/profile/supertanuki)
- on [blog.naoned.fr](http://blog.naoned.fr/symfony-live-paris-2015-nous-etions/) by [Jean-Baptiste Delhommeau](https://connect.sensiolabs.com/profile/jbdelhommeau) and [Nicolas Marniesse](https://connect.sensiolabs.com/profile/nmarniesse)
- on [remibarbe.fr](http://remibarbe.fr/blog/2015/04/09/symfony-live-2015-mes-notes/) by [Rémi Barbe](https://connect.sensiolabs.com/profile/remiii)  
- on [obtao.com](http://obtao.com/blog/2015/04/symfony-live-paris-2015-cetait-comment-2/) by [Grégory Quatannens](https://connect.sensiolabs.com/profile/gscorpio)  
- on [michaelperrin.fr](http://www.michaelperrin.fr/2015/04/15/retour-sur-la-symfony-live-2015/) by [Michaël Perrin](https://connect.sensiolabs.com/profile/michael.perrin)
