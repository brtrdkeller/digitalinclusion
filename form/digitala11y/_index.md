---
title: Digital Accessibility
type: form
description: "Je vous propose ce questionnaire pour recueillir des éléments pour une enquête sur l'accessibilité numérique. Cette enquête a pour but d'avoir un panorama des : enjeux, pistes, manques, possibles,... Afin de savoir comment développer une offre accessibilité numérique, et pouvoir développer cette compétence en interne." 
form:
  - title: Informations
    questions:
      - label: Votre Nom
        name: name
        type: text
        placeholder: Prénom Nom
        required: true
      - label: Avez vous un poste à responsabilité ?
        name: job
        type: radio
        help: (ex. chef de secteur, chef d'équipe, chef d'entreprise...)
        element:
          - label: Oui
          - label: Non
      - label: Quel est, selon vous, votre connaissance concernant l'accessibilité numérique ?
        name: estimated-knowledge-accessibility
        type: radio
        help: (Prise en compte des différents handicaps dans le cadre de l'utilisation de services numériques
        element:
          - label: aucune
          - label: réduite
          - label: moyenne
          - label: importante
          - label: total
      - label: Quel est, selon vous, le degré de prise en compte de l'accessibilité numérique dans vos projets ?
        name: estimated-action-accessibility
        type: radio
        help: (Ex. Un processus en place pourla conception ou le contrôle)
        element:
          - label: aucune
          - label: réduite
          - label: moyenne
          - label: importante
          - label: total
      - label: L'accessibilité est-il en enjeu dans vos missions actuelles ?
        name: mission-issue
        type: radio
        element:
          - label: Oui
          - label: Non
      - label: L'accessibilité sera-il en enjeu majeur dans vos missions futures ?
        name: mission-issue
        type: radio
        element:
          - label: Oui
          - label: Non
  - title: Expériences Numériques
    questions:
      - label: Si je vous dis numérique, quel premier mot vous vient à l'esprit ?
        name: first-word
        type: text
        placeholder: 1 mot
      - label: Selon vous, quel est le plus grand freins pour engager une démarche d'accessibilité numérique
        name: first-block
        type: text
        placeholder: L'administration, les connaissances, les GAFAM
      - label: Citer de 1 à 3 choses à mettre en place pour garantir (le plus possible) de prendre en compte les sujets d'inclusion
        name: first-win
        type: text
        placeholder: L'administration, les connaissances, les GAFAM
      - label: Pouvez vous classer ces trois termes par ordre d'importance, dans le cadre d'une politique de transformation (numérique) ?
        name: idea
        type: text
        placeholder: Culture, Formation, Conformité
      - label: Pouvez vous citer une expérience numérique dans laquelle vous avez été bloqué et qui vous a donné l'impression d'être discriminé ?
        name: experience-personnal
        type: textarea
        placeholder: Description de mon expérience
      - label: Pouvez vous citer une expérience dans laquelle vous avez été témoin d'une personne bloquée et qui vous a donné l'impression que cette personne était discriminé ?
        name: experience-other
        type: textarea
        placeholder: Description de mon expérience
      - label: Pouvez vous nous citer une expérience numérique que vous avez vécu dans des pays autre que la France, si possible hors d'Europe ?
        name: experience-abroad
        type: textarea
        placeholder: Description de mon expérience
---
  