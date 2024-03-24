# Journal de création

## Semaine 1
### Préproduction et préparation

Cette semaine a été consacrée à repenser le projet et adapter la préproduction.

La majorité de la semaine fût occupée par des rencontres d'équipes plutôt productives qui nous on permis de complètement revoir le projet et d'avoir une meilleure idée de la direction du projet.
(Photo à changer)
![medias/exemple_general.jpg](https://github.com/Iteration6/Effet-Papillon/blob/bff25fd46ef8aaab2b5f28a35b97eb95d7b22ec0/docs/journaux/medias/bolduc_s1_brainstorm.jpg)

Nous avons également prit le temps de parler avec les TTPs et Guillaume pour cibler les défis à relever pour la mise en espace. Il semble que le positionement actuel des projecteurs posera problème et devra être revu. Plusieurs pistes ont été nommées dont une impliquant des miroirs qui seront testés dans les prochaines semaines.
(Photo à changer)
![medias/exemple_photoshop.jpg](https://github.com/Iteration6/Effet-Papillon/blob/bff25fd46ef8aaab2b5f28a35b97eb95d7b22ec0/docs/journaux/medias/grand_studio_setup_01.jpg)

La journée de jeudi était réservé pour tous afin de trouver le thème et le titre de l'exposition. Le titre final choisi fût finalement Crescentia, qui signifie "Croissance" en grec, une idée d'un membre de l'équipe. Toutes les équipes ont été chargées de produire des textes pour la semaine suivante decrivant par exemple comment leur installation apportais au thème général.

Finalement, quelques médias ont été crées comme une image d'inspiration qui a mené à l'installation, un modèle 3D de l'espace et de la structure principale et un environnement sonore.
(Photo à changer)
![medias/exemple_projector.jpg](https://github.com/Iteration6/Effet-Papillon/blob/bff25fd46ef8aaab2b5f28a35b97eb95d7b22ec0/docs/journaux/medias/art_petit_studio.png)

Nous sommes bien heureux de ce qui a été accompli et avons hâte de voir comment le projet évoluera! À la semaine prochaine!

## Semaine 2
### Préparation et mise en place

La deuxième semaine a été marquée par une phase d'arrangement final de la préproduction. Également, la création de la vidéo d'intention qui a été écrit, filmé et monté lors de cette semaine. L'équipe s'est concentrées sur plusieurs aspects du projet notamment les premiers essais afin de créer la structure qui supportera les écrans mais aussi trouver comment envoyer des images/vidéos en NDI dans les écrans grâce à TouchDesigner.
![NDI écrans](medias/pi-ndi.jpg)

Il y avait une problèmatique liées à la structure qui était au milieu de la projection qui nous a amené à tester des possibilité de projection soit à l'aide de deux projecteurs ou à l'aide d'un miroir redirigé la projection. Notre choix s'est arrêté sur l'utilisation de deux projecteurs.
![Installation des projecteurs](medias/instal-projecteurs.jpg)

Maintenant d'un point de vue technique, nous avons installé les quatres projecteurs et les quatres enceintes nécessaires. Des tests à l'aide des logiciels arduino et hyperhdr ont été fait afin de comprendre le fonctionnement des fairylights soudés aux M5Stack atom.
![Test de fairylights](medias/fairylight1.jpg)

Finalement, l'ambiance sonore du projet a été conçu afin d'avoir notre bande son ainsi que de s'assurer que celle-ci allait avec notre direction artistique.

## Semaine 3
### Affinage des détails visuels et techniques

La troisième semaine a été une semaine de premiers tests. Pour le côté lié à l'installation, nous avons fait les premiers arrangement sur les keystones des projecteurs afin qu'ils soient semblable au mur et que la projection soit de la bonne taille. L'accrochage d'une fairylight a également été effectué afin de pouvoir commencer la scénarisation de celle-ci.
![Test de fairylights](medias/une_fairylight.jpg)

Les premiers visuels d'essais ont été créés afin de pouvoir programmer et essayer de les ajouter à notre programme dans TouchDesigner. Notre programme qui a d'ailleeurs vu son objet "Delay" remplacer par un "Timer" puisque celui-ci correspond mieux à notre projet. Ce qui nous a permis de connecter notre objet "Timer" avec nos premiers visuels d'essais afin de programmer le tout.
![Test de structure](medias/structure-test.jpg)

Malheureusement, lors de cette semaine, notre coéquipier William Morel a fait une chute lors d'une sortie en extérieur. Il a attrapé une commotion en début de semaine ce qui est venu donner un coup au moral de l'équipe et donc nous a ralenti sur notre projet. 

En conclusion, cette semaine a été plus difficille ce qui ne nous a tout de même pas empêcher de bien commencer les premiers essais avec notre programme. Nous souhaitons à William un bon rétablissement et nous espérons qu'ils reviennent en force la semaine prochaine!

## Semaine 4
### Intégration et ajustements

La quatrième semaine a été dédiée à l'intégration des différents éléments du projet et à la réalisation d'ajustements pour l'expérience.

Tout d'abord, du code en arduino a été effectué afin que nos objets envoit des messages en osc et quee l'on puisse les reecevoir dans notre programme dans TouchDesigner. De nouveaux sons et de nouveaux visuels ont également été intégré à notre programme eet aussi les vidéos afin de contrôler les fairylights. L'organisation du moment final a également été programmé.
![Système connecté-osc](medias/bolduc_semaine4_1.png)

L'accrochage de la majorité des fairylights a été effectué. D'ailleurs, nous avons trouver une alternative à la soudure. À la place, nous avons simplement besoin d'utiliser des Unit VH3.96 afin d'asssurer la liaison avec les atom poe. De plus, nous avons rendus les fairylights adressable.
![Test de fairylights](medias/fairylight_accrocher.jpg)

Pour la séquence de fin projeter sur les murs, nous avons discuter en équipe et effectuer un storyboard afin qu'on soit tous d'accord sur la direction que l'animation allait prendre. Nous avons commencer la modélisation et le rigginf d'un cerf. Les effets ont aussi commeencer à être effectués dans Houdini.
![Storyboard](../journaux/medias/storyboard.png)

En résumé, la programmation, l'installation et la modélisation de l'installation avance très bien! Nous sommes impatients de continuer le tout la semaine prochaine.

## Semaine 5
### Finalisation et résolution des problèmes

Pour cette cinquième semaine, nous avons travaillé sur l'ajustement des intéractions et la mise en espace. Aussi, nous avons commencé à intégrer les sons et les visuels finaux dans l'espace. Chacune des personnes de l'équipe ont effectués leurs tâches assignés.

Pour ce qui est des intéractions, des ajustements ont été apportés pour résoudre un problème technique lié au fonctionnement du slider et de la poulie. Aussi nous avons installé la switch pour les ports internet ce qui facilite la connectivité réseau.

Par ailleurs, nous avons travailler sur la mise en espace final des intéractions pour une optimisations de l'expérience.

Pour finir cette semaine, nous avons ajouter des visuels finaux dans les écrans des RasberryPI, comme la pluie, et nous avons fait des tests des visuels des arbres sur les projecteurs.

Au cours de cette semaine, l'accent a été mis sur la résolution des problèmes de dernière minute et sur l'optimisation de l'ensemble de l'installation. L'équipe a travaillé avec détermination pour atteindre les objectifs fixés et assurer le succès de l'événement.

## Semaine 6
La sixième semaine a été une semaine lors dee laquelle nous avons commencé à voir le résultat final venir. Nous avons également fait plusieurs corrections. Au niveau des visuels, nous avons fait des rendus de l'arbre afin de et de l'herbe afin de pouvoir les tester au niveau de la projection. La projection de particule qui vient créer l'explosion a également été créer et tester avec les projecteurs. Nous avons également pensé et créer de nouveaux visuels afin de diffuser davantage de vidéos sur nos écrans.
![geo_eau](/docs/journaux/medias/lapierre_s6_geo_eau.png)

Pour le côté teechnique, nous avons installer et programmer avec le système les lumières DMX qui permettent d'indiquer la prochaine étape. Nous avons réorganiser les écrans installés sur la pôle. Nous avons également refait les keystones suite à l'installation des rideaux qui ont été fait cette semaine. Le système de redémarrage lorsque l'installation reste 5 minutes à une étape.
![DMX](medias/dmx.png)

Finalement, les fairy lights ont entièrement été accrochés et filés dans les tuyaux de caoutchouc. Les décorations reçues ont également été posées.

## Semaine de rattrapage
Pour la semaine de rattrapage, nous avons fini tous les visuels liés au écrans afin  qu'ils aient tous une cohérence et nous les avons ajoutés au système dans TouchDesigner. Pour la séquence de fin, le court-métrage a eu des finissions ainsi que la coloristaion a été effectuée. Puis, le résultat a été testé sur les projecteurs.
![colorisation mini-film](/docs/journaux/medias/lapierre_sr_minifilm.png) 

Pour les objets, nous avons trouvé une solution pour rendre stable le slider sans que celui-ci soit relié à la structure principale. Les ampoules et les light switch ont été positionné, finalisé et programmer. Certaines fairy lights ont eu beesoin de modifications du à certains problèmes.
![slider_02](../journaux/medias/slider_02.jpg)

Finalement, nous avons ajouter un feedback lorsque les objets sont utilisés au mauvais moment. Il ne nous reste qu'une seule semaine alors la semaine prochaine sera probablement chargé pour l'équipe!

## Semaine 7

Comme prévu, la dernière semaine de travail a été plutôt chargé.

Tout d'abord, plusieurs modifications ont été effectués suite aux commentaires de l'équipe sur le court-métrage de la fin, et le son qui l'accompagne. Nous avons aussi ajouter et finaliser tout ce qui est en lien avec la séquence de fin afin de l'intégrer à notre système. Nous avons également intégrer la version finale des particules projetés lors de l'expérience.
![test_particules](../journaux/medias/test_proj_particules.jpg)

Pour le côté plus physique, nous avons dû rajouter du contrepoids sur notre système de poulie suite à l'ajout de la pomme. Nous avons dû stabiliser les interrupteurs et créer une nouvelle valve. 
![Inteerrupteurs](medias/interrupteur.jpg)

Certains problèmes techniques ont été résolues comme les glitchs audio et le mapping que nous avons décider de faire directement dans TouchDesigner.

Finalement, un grand ménage du petit studio, l'installation d'un rideau afin de cacher la régie et des lumières à l'entrée du studio nous as permis de rendre le tout très propre et présentable pour les présentations.

## Semaine 8

## Semaine 9






