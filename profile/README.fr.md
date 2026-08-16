<div align="center">

# NORD LABS

**Logiciels · IA · Open Source**  
La division logicielle d'ISO NORD — Québec.

Français · [English](README.md)

[ Réalisations choisies ](#réalisations-choisies) · [ En chemin ](#en-chemin) · [ Comment nous bâtissons ](#comment-nous-bâtissons) · [ Nous joindre ](#contact)

</div>

---

## Le laboratoire

NORD LABS, c'est là qu'[ISO NORD](https://iso-nord.ca) bâtit ses logiciels. La division concentre le côté ingénierie de la marque : outils de développement, produits IA, infrastructure de trading, interfaces vocales et open source.

ISO NORD est la marque parente de technologie créative indépendante de Québec — logiciels, image et travail cinématographique sous une même pratique. NORD LABS en est le code. Les deux côtés partagent un même standard : utile avant d'impressionner, compréhensible avant d'être ingénieux, travaillé de l'architecture interne jusqu'au pixel final.

Le travail couvre Swift, SwiftUI, TypeScript, Go, Python, les graphiques web, la vision par ordinateur, les modèles locaux et les outils d'agents. La pile technologique change selon le problème. Les principes, non.

## Ce que nous bâtissons

- **Outils de développement et infrastructure d'agents** — les systèmes de support autour du travail assisté par IA : orchestration, observabilité, acheminement et contrôle natif de l'ordinateur.
- **Produits IA** — de l'intelligence appliquée avec des défauts local-first et axés sur la confidentialité, des notes vocales en temps réel à la recherche biométrique.
- **Infrastructure de trading** — Hurst, un cadre de trading algorithmique en TypeScript conçu pour le backtest, le papier et l'exécution réelle.
- **Open source** — des outils publiés quand l'ouverture les rend plus utiles, avec des étiquettes de maturité honnêtes et des licences claires.

## Réalisations choisies

Les projets ci-dessous sont des expériences et des versions publiques. Certains vivent dans l'organisation NORD LABS ; d'autres sont publiés sous le compte du fondateur. Chaque lien pointe vers le dépôt canonique.

### [Hurst](https://github.com/nord-labs/hurst-framework)

**Un cadre de trading algorithmique en TypeScript — écrivez une stratégie une fois, exécutez-la en backtest, papier et réel.**

Hurst est le projet d'infrastructure phare de l'organisation : un moteur de trading hexagonal pour Interactive Brokers et au-delà. Les stratégies s'écrivent une fois et s'exécutent sans modification en modes backtest, papier et réel, avec des sous-portefeuilles isolés, des métriques Sharpe/Sortino/drawdown et une CLI. La Phase 1 (le moteur de backtest, les adaptateurs CSV+Parquet, 72 tests réussis) est implémentée et publiée sur npm sous le nom [hurst-framework](https://www.npmjs.com/package/hurst-framework).

L'écosystème s'étend sur des dépôts ciblés — adaptateurs de courtiers, importateurs de données, bibliothèque de 55 stratégies, superposition de gestion du risque, empaquetage Docker avec IB Gateway, interface terminale avec assistant IA et site web compagnon. Le projet est honnête sur sa maturité : ce qui est bâti, ce qui est ébauché et ce qui vient ensuite est écrit noir sur blanc.

### [Folia](https://github.com/nord-labs/folia)

**Notes vocales IA en temps réel. Tu parles, Folia écrit.**

Folia structure ta voix en notes propres, résumés, tâches, mathématiques et diagrammes pendant que tu parles — puis te laisse chercher, rejouer, modifier et discuter avec tout ce que tu as enregistré. Le pari : la structuration en direct plutôt que la transcription après coup. La valeur apparaît pendant l'enregistrement, pas cinq minutes plus tard.

Le projet est en développement précoce, avec une [spécification](https://github.com/nord-labs/folia-docs) ouverte. Le but du design : de la papeterie qui se trouve être vivante — calme, éditoriale, rien qui ressemble à un outil de productivité.

### [Nova Computer Use](https://github.com/theodorebeaupre-prog/nova-computer-use)

**Utilisation native et locale de l'ordinateur pour Codex, sur Mac Intel et Apple Silicon.**

Nova explore ce que ressemble le contrôle d'ordinateur quand il appartient au Mac. Écrit en Swift et publié sous AGPL, il est conçu autour de l'opération locale et de l'intégration système native plutôt que d'un service d'automatisation distant. Supporter Intel et Apple Silicon compte : le matériel capable ne devrait pas devenir obsolète simplement parce qu'un outil suppose la machine la plus récente.

Le projet se situe à l'intersection des API d'accessibilité, des outils d'agents et de l'automatisation digne de confiance. Sa question plus large est simple : une IA peut-elle opérer un ordinateur pendant que l'utilisateur garde un sens clair de où réside la capacité et comment elle se comporte ?

### [Agentbar](https://github.com/theodorebeaupre-prog/agentbar)

**Le centre de contrôle des agents de codage, dans la barre de menus macOS et le terminal.**

Agentbar donne aux flux de travail lourds en agents un endroit natif où vivre. Gratuit, local, et conçu sans télémétrie. Plutôt que de traiter les agents de codage comme des processus d'arrière-plan invisibles, il rend leur présence et leur activité plus accessibles depuis l'interface système que les développeurs utilisent déjà toute la journée.

L'observabilité devrait être assez légère pour rester ouverte, pas un autre tableau de bord qui exige une attention constante.

### [PhotoCull](https://github.com/theodorebeaupre-prog/photocull)

**Triage de photos sur l'appareil, pour macOS.**

PhotoCull applique la vision par ordinateur à une des réalités les moins cinématographiques de la photographie : trier une grande séance. Il détecte le flou et les yeux fermés, groupe les rafales et écrit des sidecars XMP qui s'intègrent aux flux Lightroom. L'analyse reste sur l'appareil.

Le but n'est pas de laisser un algorithme choisir la photo finale. C'est de faire remonter rapidement les problèmes techniques et les images répétées, pour que le photographe passe plus d'attention à l'expression, au timing, à l'histoire et aux images qui méritent un second regard. PhotoCull est gratuit, open source, écrit en Swift et licencié sous MIT.

### [MCP Deck](https://github.com/theodorebeaupre-prog/mcp-deck)

**Un tableau de bord natif macOS pour les serveurs Model Context Protocol.**

À mesure que plus d'outils de développement dépendent de MCP, la configuration devient de l'infrastructure. MCP Deck apporte des vérifications de santé, des contrôles d'activation et de désactivation par client, et des journaux en direct dans une application ciblée de barre de menus. Il est bâti pour répondre aux questions opérationnelles qui apparaissent après la première démo réussie : Quel serveur tourne ? Quel client peut le voir ? Qu'est-ce qui vient d'échouer ?

Le projet est open source sous MIT et traite l'infrastructure d'agents comme quelque chose qui mérite une vraie surface de contrôle.

### [Usher](https://github.com/theodorebeaupre-prog/usher)

**Une commande. Le bon agent de codage. À tout coup.**

Usher est un routeur en ligne de commande écrit en Go pour les abonnements Claude Code, Codex et Gemini. Il sélectionne un agent approprié pour la tâche sans demander aux utilisateurs de rebâtir leur flux de travail autour de clés API. L'idée est intentionnellement petite : les développeurs ont déjà des outils puissants, mais les choisir et les invoquer de façon cohérente crée de la friction.

Usher transforme ce choix en infrastructure. C'est une porte, pas une pièce de plus.

### [Hangar](https://github.com/theodorebeaupre-prog/hangar)

**Le centre de contrôle du bâtisseur IA solo.**

Hangar est une famille de skills Claude Code en Python pour préparer, ravitailler et lancer une flotte d'agents de codage. Où Usher se concentre sur l'acheminement, Hangar se concentre sur le flux de travail : établir le contexte, créer des patrons d'opération répétables et aider un bâtisseur seul à coordonner plus de travail sans perdre le fil.

Son langage aéronautique n'est pas de la décoration. Les bons lancements dépendent de la préparation, des vérifications, des rôles clairs et de savoir quand le véhicule n'est pas prêt à voler.

### [CoMotion](https://github.com/theodorebeaupre-prog/comotion)

**Un chemin auto-hébergé du brief à la vidéo d'infographie animée.**

CoMotion combine un skill Claude Code, un serveur MCP et une CLI en un pipeline local de génération vidéo. Il peut transformer un brief en infographie animée avec voix hors champ tout en gardant le rendu auto-hébergé. Le projet explore un flux créatif où l'IA coordonne les étapes de production sans forcer tout le processus dans une plateforme de génération fermée.

La partie intéressante des médias génératifs, ce n'est pas une sortie surprenante isolée, mais un système qui peut être inspecté, dirigé, répété et intégré à une vraie production.

### [ISO OS — Open Source](https://github.com/theodorebeaupre-prog/iso-os-oss)

**Un jumeau numérique urbain axé sur la confidentialité et une plateforme cinématographique de visualisation urbaine.**

ISO OS explore la ville comme interface. Son édition open source réunit la pensée géospatiale, les graphiques web temps réel, la confidentialité et une approche cinématographique de l'observation. Au lieu de réduire un lieu à des tableaux de bord abstraits, il demande comment l'infrastructure numérique peut préserver l'atmosphère et la compréhension spatiale.

Le projet est bâti en TypeScript et reste expérimental. C'est à la fois une direction de plateforme et une surface de recherche pour visualiser l'information urbaine complexe sans perdre l'échelle humaine des rues en dessous.

### [Aura](https://github.com/theodorebeaupre-prog/Aura)

**Personnalisation réversible de macOS 26 Tahoe.**

Aura est un utilitaire Swift en développement précoce pour les presets Liquid Glass, les contrôles d'animation et d'autres ajustements d'apparence système. Son mot central : réversible. La personnalisation ne devrait pas exiger des ajustements risqués à sens unique ni laisser les utilisateurs deviner comment revenir à un état stable.

Aura est open source sous MIT et aborde la personnalisation comme du design de produit plutôt qu'une collection de commandes cachées.

### [Garmin GCD Toolkit](https://github.com/theodorebeaupre-prog/garmin-gcd-toolkit)

**Inspecter, extraire et rechercher les conteneurs de firmware Garmin.**

Le Garmin GCD Toolkit documente un format de conteneur de firmware et fournit une CLI Python pour l'analyse. Il a grandi à partir de reverse engineering pratique et d'un intérêt pour l'interopérabilité : comprendre comment un appareil existant stocke et déplace son logiciel, puis transformer cette compréhension en outillage reproductible.

Tous les projets ne commencent pas avec une nouvelle interface. Parfois, le travail valable est l'observation soignée, l'analyse binaire, la documentation et le fait de laisser le chemin plus clair pour le prochain chercheur.

### [CoPad Server](https://github.com/theodorebeaupre-prog/copad-server)

**Transformer un iPad en surface de contrôle physique pour Claude Code.**

CoPad Server connecte un flux Mac à une interface iPad, créant quelque chose de plus proche d'un Stream Deck pour le développement agentique. Il explore la dimension physique des outils logiciels : boutons, état, proximité, et la valeur de sortir les contrôles importants de l'écran principal encombré.

C'est une expérience pratique pour rendre les flux IA tangibles.

### [ISO NORD Claude Code Starter](https://github.com/theodorebeaupre-prog/iso-nord-claude-code-starter)

**Un point de départ plus sûr pour le développement assisté par agents.**

Ce starter combine un hook de garde contre les commandes dangereuses, des templates `CLAUDE.md` réutilisables et un guide d'écriture. Il se concentre sur la partie de l'outillage d'agents la plus facile à ignorer : la qualité des instructions et des limites qui entourent le modèle.

Le dépôt est gratuit et volontairement accessible. De meilleurs flux d'agents ne devraient pas exiger de découvrir personnellement chaque mode de défaillance.

## En chemin

Les projets suivants sont privés ou en développement. Ils sont inclus ici comme des directions, pas des promesses. Il n'y a pas de dates bêta annoncées, et les détails peuvent changer à mesure que le travail devient plus clair.

### kitty — En développement

kitty est la couche d'argent des conversations de groupe pour le Canada : un lien, tout le monde contribue, personne ne se fait courir après. Il coordonne les achats de groupe via Interac e-Transfer — confirmations, suivi des participants, transparence — sans jamais détenir, déplacer ni mettre en fiducie des fonds. L'argent passe directement entre les participants sur des rails qu'on n'opère pas, et cette limite est traitée comme une ligne de conformité dure, pas une fonctionnalité.

Un produit volontairement petit avec une frontière volontairement claire.

### VISO ID — Recherche / aperçu privé

VISO ID investigate la vérification biométrique locale et axée sur la confidentialité pour iPhone et Mac. La recherche porte sur la vérification d'identité ou de présence tout en gardant le traitement biométrique sensible près des appareils de l'utilisateur et en rendant les limites du système compréhensibles.

La biométrie est un domaine de haute confiance. Le projet est donc traité comme de la recherche avant le produit : modèles de menace, stockage, vivacité, transport, inscription, récupération et compréhension utilisateur comptent autant que la performance de reconnaissance.

### ISO OS — En développement

Le travail privé ISO OS étend les idées visibles dans l'édition open source : un jumeau numérique urbain avec un langage visuel cinématographique et des fondations axées sur la confidentialité. Il explore comment une plateforme peut connecter l'information spatiale, les systèmes urbains, l'observation et la narration sans transformer les gens ou les lieux en une couche de données extractive.

Le dépôt open source est la fenêtre publique. Le produit plus large reste en développement.

### Nocturne — Aperçu privé

Nocturne est une archive cinématographique d'observation nocturne en WebGL, bâtie avec Astro, Lenis et Three.js. Les plans d'image pilotés par shaders restent synchronisés avec le document, permettant à l'interface de préserver le rythme de la navigation éditoriale tout en introduisant profondeur, mouvement et atmosphère.

C'est un point de rencontre entre archive photographique, ingénierie web et cinématographie nocturne — moins un gabarit de galerie qu'une expérience sur la façon dont l'espace numérique peut porter une mémoire visuelle.

### Cairn — En développement

Cairn est une application SwiftUI de navigation administrative pour les grandes transitions de vie au Québec. Sa prémisse : les moments importants — déménager, changer de statut, commencer un nouveau chapitre — créent souvent une carte confuse de formulaires, d'institutions, d'échéances et de dépendances.

Le nom réfère à un marqueur qui aide quelqu'un à trouver son chemin dans un terrain difficile. Le produit est développé avec la même intention : rendre la bureaucratie lisible sans prétendre qu'elle est simple.

## Comment nous bâtissons

Nous choisissons la technologie à partir des contraintes, vers l'extérieur.

Pour le travail natif Apple, cela signifie souvent Swift, SwiftUI, Vision, les frameworks système et l'intégration directe de la plateforme. Pour des outils en ligne de commande durables, Go ou Python peuvent créer une histoire de distribution et de maintenance plus claire. TypeScript connecte les interfaces web, les systèmes MCP, les graphiques temps réel et les pipelines créatifs. Astro et Three.js supportent le travail visuel où le navigateur est à la fois document et scène.

À travers les piles, nous préférons quelques qualités constantes :

- **Local par défaut quand la tâche le permet.** Les données ne devraient pas voyager sans raison.
- **Opérations réversibles.** Les utilisateurs ont besoin d'un chemin de retour sûr.
- **Comportement observable.** Journaux, état et échecs devraient être compréhensibles.
- **Petits outils composables.** Une CLI ciblée ou un protocole peut survivre à une grande interface.
- **Affordances natives là où ça compte.** Barres de menus, fichiers, métadonnées, raccourcis et accessibilité font partie du produit.
- **La documentation comme fonctionnalité.** Un système n'est pas complet si seul son auteur peut l'opérer.
- **Étiquettes de maturité honnêtes.** Recherche, aperçu, développement précoce et version signifient des choses différentes.
- **Design avec atmosphère, pas décoration.** L'identité visuelle devrait soutenir l'orientation et le sens.

L'IA fait partie de l'atelier, pas l'auteur officiel. Les modèles peuvent accélérer la recherche, l'implémentation, les tests et l'itération. Le jugement reste humain : décider quoi bâtir, vérifier ce qui est vrai, reconnaître ce qui cloche, protéger l'information privée et assumer la responsabilité du résultat publié.

## Travail ouvert, portes ouvertes

Les dépôts publics de NORD LABS sont des objets de travail. Certains sont des utilitaires complets ; d'autres des expériences actives. Les issues, les pull requests ciblées, les rapports de bogues soignés, les améliorations de documentation et les commentaires du monde réel sont bienvenus là où un dépôt les supporte.

Avant de contribuer, lis le README et la licence du projet. Chaque outil a des limites différentes. Une application native macOS, un toolkit de recherche de firmware et une famille de skills d'agents ne devraient pas être forcés dans le même processus de contribution.

Si tu utilises un des outils, le commentaire le plus valable est concret : ce que tu essayais de faire, quel environnement tu utilisais, ce qui s'est passé, ce à quoi tu t'attendais, et si le problème peut être reproduit. Si tu étends un projet, explique le cas d'usage avant l'implémentation. Une intention claire accélère la révision technique.

Nous croyons aussi que le savoir inachevé peut être utile. Une contrainte documentée, une approche infructueuse ou une petite note d'interopérabilité peut sauver des jours à quelqu'un d'autre. Le open source devient plus fort quand les dépôts préservent le raisonnement, pas seulement le code final.

## Bâti à Québec

NORD LABS est basé à Québec, au Canada, et fait partie d'ISO NORD.

Le Nord dans le nom n'est pas une revendication de distance ou de sévérité. C'est une contrainte de design et une source de caractère. Bâtir pour des conditions changeantes. Faire des systèmes qui restent utiles. Respecter le matériel.

Nous sommes tôt, indépendants, et encore en train de définir la forme complète du lab. C'est un avantage. Ça laisse la place de connecter les disciplines avant que les frontières organisationnelles ne durcissent autour d'elles. Ça rend possible qu'un outil de firmware, une app de tri de photos, une plateforme urbaine et un tableau de bord d'agents se renseignent l'un l'autre.

## Contact

Pour de la collaboration, des questions de projet ou des conversations sur ce que nous bâtissons :

- **Courriel :** [info@theo-picture.com](mailto:info@theo-picture.com)
- **GitHub :** [@nord-labs](https://github.com/nord-labs)
- **Fondateur :** [@theodorebeaupre-prog](https://github.com/theodorebeaupre-prog)
- **ISO NORD :** [iso-nord.ca](https://iso-nord.ca)

Si tu écris au sujet d'un projet open source précis, utilise le issue tracker de ce dépôt quand possible. Ça garde le contexte technique public et utile à la prochaine personne.

---

<div align="center">

**NORD LABS**  
Logiciels · IA · Open Source  
Une division d'ISO NORD

</div>
