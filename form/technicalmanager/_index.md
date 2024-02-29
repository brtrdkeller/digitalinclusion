---
title: Digital Accessibility (TUM & THOP)
type: form
description: |-
  Je vous propose de partager quelques informations pour une enquête sur l'accessibilité numérique chez HI. 
  
  Cette enquête a pour but de réaliser un panorama des : enjeux, pistes, manques, possibles, en fonction des secteurs techniques, des programmes,... 
  
  Savoir comment développer une offre accessibilité numérique adaptée aux activités de HI, et pouvoir développer cette compétence en interne. 
form:
  - title: Pour commencer, parlez-nous de vous
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
      - label: Quelle fonction occupez-vous à HI ?
        name: jobtitle
        type: text
        placeholder: Nom de la fonction
      - label: Vos pays d'activité
        name: countries
        type: text
        placeholder: Ouganda, Niger, Mali
        help: "(Inscrivez des noms de pays séparés par des virgules)"
  - title: Les enjeux de l'accessibilité numérique
    questions:
      - label: Quel est, selon vous, votre niveau de connaissance concernant l'accessibilité numérique ?
        name: estimated-knowledge-accessibility
        type: radio
        help: (Ex. Prise en compte des différents handicaps dans vos activités, connaissance des lois qui s'appliquent dans votre contexte, impacts sur les bénéficiaires...)
        element:
          - label: aucune
          - label: réduite
          - label: moyenne
          - label: importante
          - label: majeure
      - label: L’accessibilité digitale fait-elle partie des projets mis en œuvre actuellement ou par le passé sur votre programme ?
        name: mission-issue-present
        type: radio
        element:
          - label: Oui
          - label: Non
      - label: Si oui, dans quel secteur ?
        name: mission-issue-sector
        type: text
        placeholder: Nom des secteurs
        help: "(Lister tous les secteurs HI, séparés par des virgules)"
      - label: Aimeriez-vous développer des composantes d’accessibilité digitale dans vos projets ?
        name: mission-issue-will
        type: radio
        element:
          - label: Oui
          - label: Non
      - label: Quels sont les principaux freins/obstacles pour développer l’accessibilité digitale sur votre programme ?
        name: mission-block
        type: textarea
        placeholder: Incrivez vos réponses
        help: "(D'ordre humain, financier, sociétale, d'organisation...)"
      - label: De quoi auriez-vous besoin pour développer / renforcer l’accessibilité digitale ?
        name: mission-develop
        type: textarea
        placeholder: Incrivez vos réponses
        help: "(D'ordre humain, financier, sociétale, d'organisation...)"
---
