---
layout: page
mathjax: true
permalink: /integration/
---

- [les différentes enjeux techniques](#ia)
- [Les approches envisageables](#voitures)

<a name='ia'></a>

## les différentes enjeux techniques

<div class="fig figcenter fighighlight">
  <img src="/imgs/enjeux.png">
</div>

Ci-dessous les différentes enjeux techniques qu’on veut résoudre en utilisant l’IA:
- Localisation et cartographie: où suis-je? et à quoi ressemble mon environnement ?
  La Localisation et cartographie simultanées, connue en anglais sous le nom de SLAM (simultaneous localization and mapping) ou CML (concurrent mapping and localization), consiste, pour un robot ou véhicule autonome, à simultanément construire ou améliorer une carte de son environnement et de s’y localiser.

- Compréhension des scènes: où/qui/quoi/pourquoi?
  La compréhension de la scène est une condition préalable importante pour de nombreuses applications intérieures et extérieures, y compris la conduite autonome, la navigation, la cartographie intérieure et extérieure ainsi que la localisation. Étant donné une entrée de grande dimension (p. ex., une image ou un flux vidéo), la tâche consiste à extraire une représentation riche mais compacte qui est facilement accessible pour les étapes de traitement ultérieures. Les sorties typiques comprennent des informations sémantiques ou des informations 3D sur la forme et la pose des objets dans la scène.

- Planification des mouvements: comment je peux aller de A jusqu’à B.
  La planification du trajet consiste à trouver un trajet sûr, confortable et efficace pour manœuvrer autour de la circulation.
- Interaction homme-robot: quel est l'état physique et mental du conducteur ?
   Ces dernières années, malgré de nombreuses recherches et progrès dans le domaine de l'intelligence artificielle, nous avons été témoins de nombreux accidents impliquant des voitures autonomes. Pour que la conduite automobile ait un impact positif potentiel sur la sécurité routière, il faut un modèle d'interaction homme-robot (HRI) différent qui fournisse un mécanisme d'algorithme d'apprentissage permettant de reconnaître les autres véhicules, non seulement comme un objet en mouvement, mais comme un véhicule contrôlé de manière intelligente par un conducteur humain.
   
- Communiquer: comment communiquer une intention au monde extérieur
  V2X (Vehicle-to-Vehicle ou Vehicle-to-Infrastructure) est une forme de technologie qui permet aux véhicules de communiquer avec les objets mobiles du système de circulation qui les entourent. L'un des composants de V2X est V2V, ou véhicule à véhicule, qui permet aux véhicules de communiquer entre eux. Un autre composant est V2I, ou véhicule à l'infrastructure, permet aux véhicules de communiquer avec des systèmes externes tels que les feux de circulation, les bâtiments, et même les cyclistes ou les piétons.


<a name='voitures'></a>

## Les approches envisageables

Deux types de systèmes d'IA envisageable:

**A1 : Autonomie centrée sur l'homme** : Quand l’IA n'est pas entièrement responsable. L'être humain est responsable de son comportement.
<div class="fig figcenter fighighlight">
  <img src="/imgs/hca.png">
</div>

Les voitures autonomes ont le potentiel d'améliorer considérablement la sécurité et l'efficacité routières. Cependant, s'ils ne sont pas capables d'interagir et de communiquer facilement avec les gens à l'intérieur et autour d'eux, la technologie peut avoir de la difficulté à être adoptée à grande échelle.
<div class="fig figcenter fighighlight">
  <img src="/imgs/human_needed.png">
</div>

Construire des véhicules autonomes efficaces, agréables et sûrs est beaucoup plus difficile qu'on ne l'a toujours pensé. La raison est que, tout simplement, un véhicule autonome doit interagir avec des êtres humains. Cette interaction n'est ni un problème de robotique, ni un problème d'apprentissage machine, ni un problème psychologique, ni un problème économique, ni un problème politique. Tous ces problèmes ne font qu'un. Elle remet en question nos suppositions sur les limites de l'être humain à son pire et sur les capacités des systèmes d'intelligence artificielle à leur meilleur. 


 
**A2 : l’IA est entièrement responsable**. Lorsque l'homme reçoit le système, il fait trop confiance au système. Plus le système s'améliore, moins les humains y prêteront attention.
<div class="fig figcenter fighighlight">
  <img src="/imgs/full_auto.png">
</div>
Cette approche traditionnelle des véhicules autonomes consiste à ne pas tenir compte de l'être humain dans son ensemble et à se concentrer sur le perfectionnement de la cartographie, de la perception, de la planification et d'autres problèmes. En pratique, compte tenu des capacités matérielles et algorithmiques de pointe actuelles, cette approche met l'accent sur une cartographie avec une définition très précise, des ensembles de capteurs robustes et des politiques de conduite plus conservatrices.
D'un point de vue juridique, le constructeur automobile est responsable du comportement.
Problèmes techniques et éthiques.