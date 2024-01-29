---
title: Digital Accessibility
type: form
description: |-
  Je vous propose ce questionnaire pour recueillir des éléments pour une enquête sur l'accessibilité numérique. Cette enquête a pour but d'avoir un panorama des : enjeux, pistes, manques, possibles, en fonction des secteurs techniques, des programmes, ... Afin de savoir comment développer une offre accessibilité numérique adaptée aux activités de HI, et pouvoir développer cette compétence en interne. 
  - 1
  - 2

  **gras** [hi](https://hi.org)
form:
  - title: Pour commencer, parlez-nous de vous:
    questions:
      - label: Votre Nom
        name: name
        type: text
        placeholder: Prénom Nom
        help: "(Vous pouvez répondre de manière anonyme : ne rien mettre dans ce champs)"
      - label: Votre secteur, si applicable
        name: sector
        type: text
        placeholder: Nom du secteur
        help: "(Donnez le nom du secteur)"
      - label: Quelle fonction occupez-vous à HI?
        name: jobtitle
        type: text
        placeholder: Nom de la fonction
      - label: Vos pays d'activité
        name: countries
        type: text
        placeholder: Ouganda, Niger, Mali
        help: "(Inscrivez des noms de pays séparés par des virgules)"
  - title: Connaissances (Estimation)
    questions:
      - label: Quel est, selon vous, votre connaissance concernant l'accessibilité numérique ?
        name: estimated-knowledge-accessibility
        type: radio
        help: (Ex. Prise en compte des différents handicaps sur vos services numériques métiers, pour les bénéficiaires, connaissance des lois...)
        element:
          - label: aucune
          - label: réduite
          - label: moyenne
          - label: importante
          - label: totale
      - label: Quel est, selon vous, votre prise en compte de l'accessibilité numérique dans vos projets ?
        name: estimated-action-accessibility
        type: radio
        element:
          - label: aucune
          - label: réduite
          - label: moyenne
          - label: importante
          - label: totale
        help: (Ex. Un processus est en place pour la rédaction, la conception ou le contrôle de conformité)
      - label: L'accessibilité numérique est-elle un enjeu dans vos missions actuelles ?
        name: mission-issue-present
        type: radio
        element:
          - label: Oui
          - label: Non
        help: (Ex. Demandes sur le sujet, contraintes légales,...)
      - label: L'accessibilité numérique sera-elle un enjeu majeure dans vos missions futures ?
        name: mission-issue-futur
        type: radio
        element:
          - label: Oui
          - label: Non
        help: (Ex. Obligation de bailleurs pour des offres)
  - title: Expériences Numériques (Retour rapide personnel)
    questions:
      - label: Si je vous dis numérique, quel est le premier mot vous vient à l'esprit ?
        name: first-word
        type: text
        placeholder: 1 mot
        help: (En positif ou négatif)
      - label: Selon vous, quel est le plus grand frein pour engager une démarche d'accessibilité numérique
        name: first-block
        type: text
        placeholder: L'administration, les connaissances, les GAFAM
        help: (Interne, externe, humain, matériel...)
      - label: Selon vous quelle action mettre en place pour démarrer la prise en compte les sujets d'inclusion numérique
        name: first-win
        type: text
        placeholder: Former, réunir les parties prenantes
        help: (Le truc indispensable au démarrage)
      - label: De ces 3 actions, laquelle vous semble la plus fondamentale en interne ?
        name: idea
        type: radio
        placeholder: Culture, Formation, Conformité
        element:
          - label: Culture
          - label: Formation
          - label: Conformité
        help: (Pour vous ou votre équipe)
      - label: De ces 3 actions, laquelle vous semble la plus fondamentale en externe ?
        name: idea
        type: radio
        placeholder: Culture, Formation, Conformité
        element:
          - label: Culture
          - label: Formation
          - label: Conformité
        help: (Pour vos bénéficiaires ou vos partenaires)
      - label: Pouvez vous citer une situation numérique qui vous bloque dans votre travail quotidien ?
        name: experience-personnal
        type: textarea
        placeholder: Description de mon expérience
      - label: Pouvez vous citer une situation numérique qui bloque vos interlocuteurs dans votre travail ?
        name: experience-other
        type: textarea
        placeholder: Description de mon expérience
---
  
