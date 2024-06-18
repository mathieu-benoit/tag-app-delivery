---
title: Glossaire
description: "Définit les termes clés utilisés dans les écrits du groupe de travail sur les plateformes."
---

Voir également : [Glossaire Cloud Native](https://glossary.cncf.io/fr/)

Si vous souhaitez faire référence à ces définitions en dehors du cadre des documents du groupe de travail, veuillez noter qu'elles ont été rédigées dans le contexte CNCF et livraison d'applications.

## Plateforme
Ensemble de fonctionnalités, de documentations et d'outils qui supportent le développement, le déploiement, l'exploitation et/ou la gestion de la livraison de produits et de services. Une plateforme peut inclure des portails web, des Interfaces de Programmation d'Application (APIs), des CLIs, des définitions de protocole, de la documentation, des normes et/ou des modèles de fonctionnalités supportées. Lorsque les plateformes sont bien conçues, elles permettent une livraison plus rapide et plus fiable des applications et des services d'une organisation.

En fonction du périmètre et de l'audience d'une plateforme, elle peut parfois être appelée “Plateforme de Développement”, “Plateforme de Développement Interne (IDP)”, “Plateforme de Livraison”, “Plateforme d'Applications” ou même “Plateforme Cloud”. Le terme “Platform-as-a-Service (PaaS)” est également souvent utilisé pour décrire les plateformes achetées ou adoptées de l'extérieur d'une organisation, offrant une solution de plateforme plus gérée, mais souvent moins personnalisable.

## Ingénierie de Plateforme
La conception, la construction, l'exploitation et l'évolution d'une plateforme. Une façon de considérer la pratique est de la considérer comme une approche axée sur l'empathie en matière de conception organisationnelle technico-sociale<sup><a href="https://hazelweakly.me/talks/qcon-sf-2023/slides#22">1</a></sup>. Dans cette optique, il s'agit d'un processus continu par lequel une organisation apprend comment et où investir et miser sur des stratégies d'entreprise en interne, plutôt qu'en externe.

## Équipe de la Plateforme
Les personnes responsables de la construction et de la gestion de la ou des plateformes. Les membres de l'équipe de la plateforme comprennent des **ingénieurs de plateforme**, qui se concentrent sur la création de l'outil et des fonctionnalités qui composent les expériences de la plateforme. Il peut inclure des rôles de **Responsable produit de la plateforme** qui visent à répondre aux besoins des clients internes tout en soutenant les objectifs stratégiques plus larges de l'organisation. À mesure que la plateforme évolue, d'autres rôles spécialisés, tels que des exploitant, des analystes d'assurance qualité, des concepteurs d'interface (UI) et d'expérience (UX) utilisateurs, des rédacteurs techniques et des représentants des développeurs, peuvent être ajoutés aux équipes de la plateforme.

## DevOps
“Le DevOps est une méthodologie dans laquelle les équipent gèrent le processus complet du développement d'une application jusqu'aux opérations en production.”<sup><a href="https://glossary.cncf.io/fr/devops/">2</a></sup>. Bien que les pratiques DevOps puissent être mises en oeuvre par les équipes sans développer de plateforme dédiée, il peut être utile de considérer l'ingénierie de plateforme comme une approche permettant de faire évoluer les principes DevOps grâce à la livraison et à la gestion d'une plateforme unifiée qui sert l'ensemble de l'organisation. Cette plateforme partagée vise à rationaliser les processus de développement, de déploiement et d'exploitation, en fournissant un environnement standardisé et efficace pour la livraison d'applications. Bien que DevOps et l'ingénierie de plateforme convergent vers les objectifs d'optimisation de la livraison d'applications et des performances opérationnelles, l'ingénierie de plateforme se distingue par son accent mis sur la création d'une infrastructure concrète — la plateforme elle-même — pour faciliter ces objectifs.

## Utilisateurs de la Plateforme
Les personnes qui utilisent directement les fonctionnalités de la plateforme, y compris, mais sans s'y limiter, les développeurs d'applications, les opérateurs d'applications, les scientifiques de données - quiconque déploie des applications sur la plateforme, utilise ses fonctionnalités ou nécessite des informations sur son utilisation. Les utilisateurs de la plateforme peuvent inclure d'autres ingénieurs de plateforme créant des services de plateforme de niveau supérieur en plus des fonctionnalités de niveau inférieur.

## Portail
Une interface Web qui fournit un accès centralisé à une variété de ressources, d'outils et de services. Il peut servir de point de départ à un large éventail d'utilisateurs afin de gérer et d'interagir efficacement avec les fonctionnalités de la plateforme sous-jacente. Un portail existe pour améliorer l'expérience utilisateur grâce à une interface conviviale qui simplifie les processus complexes et favorise les fonctionnalités de libre-service.

## Fonctionnalités de la Plateforme
Les avantages spécifiques pour les utilisateurs, ou **_qu'est-ce qu'_** une plateforme fournit. Celles-ci ne doivent pas être confondues avec les qualités de la plateforme qui décrivent **_comment_** les fonctionnalités s'utilisent. Ces fonctionnalités peuvent se situer à différents niveaux d'abstraction (par exemple, une base de données unique par rapport à un environnement de test comprenant une base de données) et fournies par différents fournisseurs de fonctionnalités. À mesure que les plateformes mûrissent, elles aspirent généralement à offrir des fonctionnalités en libre-service, en commençant par la possibilité de découvrir les fonctionnalités disponibles et en incluant une cohérence de l'expérience entre les fonctionnalités. Les fonctionnalités elles-mêmes sont souvent assez durables tandis que les fournisseurs et leur mise en oeuvre peuvent évoluer plus rapidement. Par exemple, il est peu probable qu'une organisation cesse d'exiger des environnements de test, mais elle pourrait évoluer pour fournir des solutions conteneurisées au lieu de solutions basées sur des machines virtuelles.

## Fournisseur de fonctionnalités de la Plateforme
Un groupe de personnes qui développent et maintiennent une fonctionnalité offerte par la plateforme. Les fournisseurs peuvent être des organisations externes ou des équipes internes et, dans les petites organisations, il peut souvent s'agir des mêmes personnes qui développent également la plateforme plus large. À mesure que les plateformes mûrissent, elles bénéficient du maintien d'abstractions pour les fournisseurs afin de décourager le "verrouillage" et de continuer à progresser vers leur plateforme viable la plus petite (TVP).

## Qualités de la plateforme
Fait référence à **_comment_** la plateforme et ses fonctionnalités fonctionnent et ce à quoi on peut s'attendre en termes d'exigences fonctionnelles ou non fonctionnelles. Les exemples incluent la fiabilité ou les performances des services gérés qui peuvent être mesurées avec des objectifs de niveau de service (SLO), la sécurité qui peut être mesurée dans le temps pour atténuer les risques identifiés, ou l'observabilité qui peut être utilisée à la fois pour déboguer et créer des rapports sur l'utilisation de la plateforme. Les qualités sont souvent confondues avec les fonctionnalités, car certains concepts tels que l'observabilité, qui peuvent être proposés comme une fonctionnalité (par exemple, un opérateur OTel fourni pour collecter la télémétrie de l'application) et une qualité déclarée (par exemple, des métriques de plateforme pour mesurer et alerter sur la disponibilité de cette application fournies par l'opérateur OTel).

## Charge cognitive
Une quantification des coûts mentaux pour un utilisateur avant qu'il puisse bénéficier des fonctionnalités d'une plateforme. Il existe en fait trois types de charge cognitive : pertinente, intrinsèque et étrangère. Les organisations sont plus saines lorsque les plateformes permettent aux utilisateurs de se concentrer sur les défis pertinents (résolution de problèmes spécifiques à un rôle) tout en simplifiant les défis intrinsèques (intégration de nouvelles informations ou processus pour accomplir leur tâche) et en minimisant les charges superflues (distractions de la tâche ciblée, parfois surnommées “[rasage de yak](https://en.wiktionary.org/wiki/yak_shaving#:~:text=yak%20shaving%20(uncountable),pour%20solve%20a%20larger%20problem.)”).

## Plateforme viable la plus petite (TVP)
Un concept initialement défini dans le livre _Team Topologies_ par Matthew Skelton et Manuel Pais, qui encourage les organisations à trouver un équilibre judicieux entre une plateforme petite mais efficace. Ce faisant, ils peuvent accélérer et simplifier la livraison d'applications pour les équipes qui s'appuient sur la plateforme tout en atteignant leurs objectifs commerciaux plus larges. Ils encouragent les plateformes à se concentrer sur les exigences uniques de l'entreprise et à intégrer régulièrement des fournisseurs de fonctionnalités externes, ce qui peut réduire la complexité et les coûts opérationnels de la plateforme.