---
title: Analyses des critères à retenir
---

End-to-end testing, also known as E2E testing, is a way to make sure that applications behave as expected…. This type of testing approach starts from the end user’s perspective and simulates a real-world scenario.

### Critère réduits Opquast

### 20 critères de Brajnik

1.1.1, 1.2.3, 1.3.1, 1.3.2, 1.3.3, 1.4.1, 1.4.3, 1.4.4, 2.1.1, 2.2.2, 2.4.1, 2.4.3, 2.4.4, 2.4.5, 2.4.10, 3.1.5, 3.2.1, 3.2.2, 3.3.2, 4.1.2

### 20 critères de Brajnik

1.1.1, 1.2.2, 1.2.3, 1.3.1, 1.3.2, 1.3.3, 1.4.1, 2.1.1, 2.1.2, 2.2.1, 2.2.2, 2.3.1, 2.4.1, 2.4.2, 2.4.3, 2.4.4, 3.1.1, 3.2.1, 3.2.2, 3.3.2, 4.1.1, 4.1.2


### Score de certitude de certains critères WCAG

| Critères | Score  |  Garde  |
|----------|--------|---------|
|1.1.1     |     88 |    OK   |
|1.2.1     |     60 |         |
|1.2.2     |     96 |    OK   |
|1.2.3     |    100 |    OK   |
|1.3.1     |     12 |         |
|1.3.2     |     53 |         |
|1.3.3     |     88 |    OK   |
|1.4.1     |     24 |         |
|1.4.2     |     96 |    OK   |
|2.1.1     |     60 |         |
|2.1.2     |     88 |    OK   |
|2.2.1     |     53 |         |
|2.2.2     |     64 |         |
|2.3.1     |     70 |         |
|2.4.1     |     35 |         |
|2.4.2     |     82 |    OK   |
|2.4.3     |     6  |     ?   |
|2.4.4     |     64 |         |
|3.1.1     |     47 |         |
|3.2.1     |     96 |    OK   |
|3.2.2     |     88 |    OK   |
|3.3.2     |     18 |         |
|4.1.1     |     75 |         |
|4.1.2     |     18 |         |

#### Numéro des critères Opquast
3,15,67,69,74,77,78,85,90,98,105,112,113,116,119,120,131,132,135,143,151,160,161,163,177,189,192,198,216,219,220

### Critères de Vitaly Friedman

1. Évitez les messages qui disparaissent : laissez les utilisateurs les fermer.
1. Évitez les gestes de glissement longs et fins et la précision.
1. Évitez les étiquettes flottantes et utilisez plutôt des étiquettes de champ statiques.
1. Ne vous fiez pas uniquement aux icônes : ajoutez des étiquettes descriptives.
1. Demandez une confirmation explicite pour les actions destructrices.
1. Ajoutez un lien "Précédent" en plus du bouton "Précédent" du navigateur.
1. Dans les formulaires, présentez une question ou un sujet par écran.
1. Utilisez des contrastes suffisants (les nuances de bleu/violet et de jaune/vert peuvent être difficiles à distinguer).
1. Faites en sorte que les messages d'erreur soient utiles et indulgents.

Source : https://www.smashingmagazine.com/2024/02/guide-designing-older-adults/

### Checklist Design Accessible

https://design-accessible.fr/checklist

###

1. CAPTCHA - images présentant un texte utilisé pour vérifier que vous êtes un utilisateur humain
1. Les éléments interactifs tels que les menus, les onglets et les boîtes de dialogue ne se comportent pas comme prévu.
1. Liens ou boutons qui n'ont pas de sens
1. Les écrans ou parties d'écran changent de manière inattendue.
1. manque d'accessibilité au clavier
1. Images dont la description (texte alt) est manquante ou inadéquate
1. Formulaires complexes ou difficiles à remplir
1. Titres manquants ou inappropriés
1. Trop de liens ou d'éléments de navigation
1. Tableaux de données complexes
1. Fonctionnalité de recherche inaccessible ou manquante
1. Absence de liens "passer au contenu principal" ou "passer à la navigation".

### Blog Accessibility Checklist:

https://sheknowsseo.co/blog-accessibility-checklist/

**Site Wide:**

 * Loads quickly
 * Disable timed sessions (i.e., logged out after 1 minute)
 * Allow right clicking, copying, and highlighting text
 * Allow users to zoom into text. Don’t disable “viewport zoom”
 * Use ARIA landmarks (included automatically with Gutenberg blocks)
 * Users can navigate site with just a keyboard
 * Mobile responsive – both horizontally and vertically on mobile
 * Allow third-party content to access the site, like screen readers
 * Use correct semantic HTML elements for structure (i.e., “H1” for title, “H3” for headers) and elements (i.e., navigation, header, footer). Automatically done in WordPress.
 * Avoid mouse-only interactions, like “hover to display”
 * Use “lang” attribute to set the language of the site, so screen readers can accurately pronounce words (mine is set in Rankmath)
 * Multiple ways for users to navigate the site (navigation, HTML sitemap, search bar)
 * Use a simple, straightforward layout
 * Keep navigation consistent across the site to avoid user confusion
 * For large navigation sections that fill the whole first contentful paint, offer a “skip to content” link/button
 * Leave space between interactive elements so users can easily click the right one

**Colours:**

 * Ensure high contrast between all colours, especially text vs. background and link vs. background
 * Check content is readable in inverted and high contrast colour settings

**Text:**

 * Font size 18px+
 * 1.2 em line spacing minimum
 * Plain, easy to read font
 * Test that content is readable at 200% enlarged
 * Use left-aligned text for easier reading
 * Content is written at a 5th-8th grade level. Check with Hemingway
 * Define abbreviations and acronyms when first used
 * Provide text in text format, not images

**Headers:**

 * Unique H1 (your title) for every page/post
 * Use clear, descriptive headings to break up text
 * Use a logical descending order for headings (i.e., H1, H2, H3, H4, H2, H3, H4)

**Links:**

 * Use 2 ways of showing links: colour + text decoration, like an underline
 * Check that links are discoverable in greyscale
 * Show that a link opens in a new tab. Link Whisper has a setting for this under “Advanced”.
 * Use descriptive anchor text, or explain before the link, so users know where they’re going when they click

**Images:**

 * Every image has alt text
 * Alt text should describe the visual of the image AND its purpose/relevance on the page
 * Provide text alternative for images of data, such as infographics (as caption or alt text)
 * Include any text on images in the alt text and/or caption

**Videos / Audio:**

 * Ensure videos don’t autoplay
 * Ensure no audio autoplays
 * Have captions
 * Have transcripts
 * Allow users to adjust speed (speed up and slow down)
 * Remove seizure triggers, like strobe effects and flashing
 * Provide written instructions, not just visual or audio
 * Avoid videos with no descriptive voice over or explanatory text a screen reader can see
 * Make content easy to hear (loud + clear). iMovie can do this for free.
 * Ensure content is pause-able, even if it’s a background video
 * Sign language option available (especially if live and in person)
 * Low or no background audio

**Dynamic Content:**

 *  Forms need an error message specifically telling users what inputs to fix
 *  Clear input labels on forms (i.e., Name, Email)
 *  Buttons large enough on mobile to read and click
 *  Clickable targets/elements are at least 44 x 44px
 *  Pop-ups have a clear way to be closed
 *  Caption tables to help users understand the table’s purpose/message
 *  Use clear headers within tables
 *  Use list elements for listed content (i.e., a numbered or bullet point list block in WordPress)


## Outils

 1. https://github.com/mbusigin/yaml-runner