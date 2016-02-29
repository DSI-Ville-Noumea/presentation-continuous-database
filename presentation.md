title: Convergence des outils et méthodes Dev&Ops
output: index.html
author:
  name: Adrien Sales/Mélanie Gault
controls: true
theme: sudodoki/reveal-cleaver-theme

--
<img src="img/highway-in-the-dark.jpg" alt="Drawing" style="width: 600px;"/>

--
# Convergence Dev/Ops
## Pratiques, méthodes et outils

<img src="img/convergence_change.jpg" alt="Drawing" style="width: 300px;"/>

--
# con·ver·gence
## /kənˈvərjəns/

    The process or state of converging.
    
    "The convergence of lines in the distance"
    
        The tendency of unrelated animals and plants to evolve superficially
		similar characteristics under similar environmental conditions.
        
        A location where airflows or ocean currents meet, characteristically
		marked by upwelling (of air) or downwelling (of water).


--
# Objectifs
## Pourquoi cette présentation

* Rappeler le chemin précédemment annoncé (dev et cloud, idd, puppet) et rappeler les concepts clés
* Présenter les avancées effectuées, l'alignement avec le SDSI
* Préciser le chemin restant
* Nouvelles perspectives et découvertes
* Négociation de moyens éventuels

--
# Fondations
## Le code de conduite

* Collaboration, empathie
* Respect, développement et reconnaissance des expertises
* On déploie avec du code ou on ne déploie pas
* Tout code/script déployé/exploité est versionné, sur GH
* Toute action fait l'objet d'un ticket sur le BugTracker (Redmine) auquel on rattache des commits, et que l'on commente

--
# Fondations
## Dev

* mavenisation
* dev sous linux
* composants libres et légers (base de données, tomcat/jetty embarqués) voir en containers
* exécution à la volée
* la compréhension et la volonté pemanente de converger vers des intérêts communs Dev et Ops
* présentation dev dans la cloud en 1 we

--
# Fondations
## Ops

* puppetisation
* départ sur git/gitlab
* présentation puppet, icinga, la stack complète

--
# Objectifs communs
## Dev collaboratif, qualité, valeurs communes...

* Le build continu
* Mesure de la qualité du code en continu (au commit près)
* Les sevices SaaS
* L'intégration
* Distribution continue
* Etre capable d'assurer plus de code,  coût égal
* Produire des indicateurs, au commit près
* Les lints (base de données, java, puppet, C#, js, html, xml)

--
# Un équipe
## Motivation et esprit d'équipe

![Equipe](img/convergence_sync.gif "Equipe") 

--
# Pofession de foi
## Code de conduite

* Partager son code et en discuter
* Travail en équipe
* Partage d'un même objectif
* Tout est source code
* Tout est versionné
* Souci de qualité permanente : viser l'excellence technique

--
# DevOps
## Les actes fondateurs de la convergence (1/2)

* Démo "dev dans le cloud"
* Démo stack infra puppet, ELK, ...
* Départ et migrations sur github : dev et premiers modules puppet
* Premier acte devops autour d'un module puppet développé par le SED et déployé par le SIE
* Build continu dans la cloud sur Travis

--
# DevOps
## Les actes fondateurs de la convergence (2/2)

* Communication sur slack
* Couverture de code coveralls
* Qualité du code SaaS : Code Climate
* Qualité du code : sonarq

--
# Risques

<img src="img/convergence_lost_someone.jpg" alt="Drawing" style="width: 600px;"/>

--
# Les concepts communs
## Les termes

* Commit
* Pull request
* Merge
* Couverture de code
* Lints
* Status GH d'une PR, et conditionnement

--
# Le Lint
## Définition

		In computer programming, lint is a Unix utility that flags some
		suspicious and non-portable constructs (likely to be bugs) in C
		language source code; generically, lint or a linter is any tool
		that flags suspicious usage in software written in any computer
		language.
		
		The term lint-like behavior is sometimes applied to the process
		of flagging suspicious language usage.
		
		Lint-like tools generally perform static analysis of source code. 



--
# GO !

<img src="img/convergence_fear.jpg" alt="Drawing" style="width: 600px;"/>

--
# Le départ
## Le partage des outils entre codeurs : Puppet/Travis

* Partage de compétences
* Emulation
* Objectifs SDSI
* Bénéfices et relations avec le code livré

--
# Les résultats
## Impacts en cours

* Conséquences sur les CCTP : simplification
* Mesure de la qualité en continu
* La disponibilité pour la revue de code et filtrer la qualité entrante

--
# Les résultats
## Très beau succès devops : module puppet liquibase

![liquibase](img/convergence_friends.gif "Liquibase") 


--
# Les résultats en cours
## DaaS : Distribution as a Service

* Livraison auto des artefacts depuis le commit (taggé)
* Cycle de vie et intégration avec les déploiements : le déploiement de demain

--
# Les résultats de demain
## Tout code est industrialisé

* Code C# de SCCM
* Le lien entre les tickets Hotline et le code
* Le BugTracker ?
* Le monitoring continu, les status page
* Le choix du code sur lequel investir
* Intégration continue

--
![victory](img/convergence_victory.jpg "Victory") 

 





