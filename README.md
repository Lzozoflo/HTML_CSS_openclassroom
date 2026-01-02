*This project has been created by Florent Cretin.*
<!-- 𝔸 𝔹 ℂ 𝔻 𝔼 𝔽 𝔾 ℍ 𝔾 𝕁 𝕂 𝕃 𝕄 ℕ 𝕆 ℙ ℚ ℝ 𝕊 𝕋 𝕌 𝕍 𝕎 𝕏 𝕐 ℤ -->
<!-- 🗎 🖋 👀 🗣 🕑 -->
[tagMarkdown]: https://github.com/Lzozoflo/Markdown

<!-- doc -->
[tagMozillahtml]: https://developer.mozilla.org/fr/docs/Web/HTML
[tagMozillacss]: https://developer.mozilla.org/fr/docs/Web/CSS
[tagW3schools]: https://www.w3schools.com/html/default.asp

<!-- open classrooms -->
[tagOpenClassroomsCours-Basic]: https://openclassrooms.com/fr/courses/1603881-creez-votre-site-web-avec-html5-et-css3
[tagOpenClassroomsCours-AnimationCss]: https://openclassrooms.com/fr/courses/5919246-creez-des-animations-css-modernes
[tagOpenClassroomsCours-siteAccessible]: https://openclassrooms.com/fr/courses/6691451-codez-un-site-web-accessible-avec-html-css/6964630-creez-un-contenu-solide-et-accessible#/id/r-6939939



# HTML CSS

### [📘 Cours HTML & CSS][tagOpenClassroomsCours-Basic]

- #### [📘 Cours bonus pour faire des animation css (grosse envie de comprendre comment ca fonctionne)][tagOpenClassroomsCours-AnimationCss]
- #### [📘 Cours bonus pour l'accessibilité des site web (pas fait mais a faire)][tagOpenClassroomsCours-siteAccessible]


<h2 id="summary">🗓 𝕊ummary</h2>

- [𝔻escription](#description)
- [𝕆bjectives](#objectives)
- [🕑 𝕃earning ℙrogression](#learningprogression)
- [🛠  ℝequirements](#requirements)
- [𝕌sage](#objectives)
- [𝕃earning Notes](#learning-notes)
- [ ℝesources](#resources)
- [🖋 𝔸uthor](#author)


<h2 id="description">𝔻escription</h2>

suivi d'un petit cours openclassroom sur html
pour but de fare ensuite leur cours javascript avec leur base donne dans ce cours ci

<br>

- [🗓 𝕊ummary](#summary)

<br>

---

<br>

<h2 id="objectives">𝕆bjectives</h2>

javais quelque connaissance basic en html CSS avant ce cours je l'ai fait dans le but de remettre le nez dans l´html simplement avec un cours "reconnue"

revoir des base comme comment mettre du texte en italic en gras voir surligne ce que je ne connaisais pas
les list ordonner, non ordonner
hypelink qui redirige faire un id ou vers des lien extern 
img, alt
et bien d'autre ... 

et au passage faire mon 1er projec avec un essaie de documentation [Markdown][tagMarkdown] sourcer touver ma facon de faire des readme ma typo mon visuel... 

<br>

- [🗓 𝕊ummary](#summary)

<br>

---

<br>

<h2 id="learningprogression">🕑 𝕃earning ℙrogression</h2>

```mermaid
---
config:
  logLevel: debug
  theme: default
  themeVariables:
    cScale0: "#ff0000"
    cScaleLabel0: "#ffffff"
    cScale1: "#00ff00"
    cScale2: "#0000ff"
    cScaleLabel2: "#ffffff"
---
timeline
    title Learning Progression

    %%  section Part 1 – HTML Basics<br>(Part_1_HTML_Basics/index.html,<br>Part_1_Basics/italics_bold_highlight.html)
    %%  Header elements
    %%  Paragraph text formatting:
    %%      Italic<br><em></em>: Bold<br><strong></strong>: Highlight<br><mark></mark>
    %%  Lists:
    %%      Ordered (1, 2, 3, …): Unordered (• • •)

    %%  section Part 2 – HTML Anchors<br>(Part_2_HTML_Anchor/)
    %%      ID attributes on different headers
    %%      Anchor tag<br><a href="...">: Link within the same page using an ID: Link to another local HTML file: Link to an external URL
    %%      Target attributes: _blank

    %%  section Part 3 – HTML Images<br>(Part_3_HTML_Images_Alt/)
    %%      Images<br><img src="" alt="">:
    %%      src<br>the link of the images with:<br>a path,<br>url:
    %%      alt<br>the accessibility for all user

    %%  section Part 4 – CSS Basics<br>(Part_4_CSS_Basics/)
    %%      import CSS<br><link rel="stylesheet" href="style.css">

    %%  section Part 5 – CSS modify font text<br>(Part_5_font_text/)
    %%      font:
    %%          size:
    %%          family:
    %%          weight
    %%      text:
    %%          decoration:
    %%          align

    %%  section Part 6 – CSS Background modify<br>(Part_6_CSS_Background/)
    %%      Super Balise "background":
    %%          background-image:
    %%          background-color (linear-gradient):
    %%          background-attachment:
    %%          background-size

    %%  section Part 7 – CSS Border Shadow<br>(Part_7_CSS_Border_Shadow/)
    %%      Super Balise "border":
    %%          border-radius:
    %%          border-width:
    %%          border-top<br>"3px color type; dotted" :
    %%          border-right<br>"3px color type; double" :
    %%          border-bottom<br>"3px color type; dashed" :
    %%          border-left<br>"3px color type; solid" "
    %%      Shadow:
    %%          box-shadow:
    %%          text-shadow

    %% section Part 8 – CSS Dynamique<br>(b/c means balise or class)<br>(Part_8_CSS_Dynamique/)
    %%     pseudo-classe:
    %%         "b/c":hover{css..}:
    %%         "b/c":active{css..}:
    %%         "b/c":focus{css..}:
    %%         "b/c":visited{css..}
    %%     les sélecteurs avancés:
    %%         * {css..}:
    %%         "b/c" "b/c"{css..}:
    %%         "b/c" + "b/c"{css..}

    %% section Part 9 – HTML Organisation<br>(Part_9_HTML_Organisation/)
    %%     Balise délimitant les zone de la page html:
    %%         "header":en-tête :
    %%         "footer":pied de page :
    %%         "nav":liens principaux de navigation :
    %%         "section":section de page :
    %%         "aside":informations complémentaires :
    %%         "article":article indépendant.
    %% section Part 10 – CSS margin padding<br>(Part_10_CSS_margin_padding/)
    %%     Element CSS qui permet de cree un espace une bordure dans tout type de balise html:
    %%         margin<br>margin-...<br>(top-right-bottom-left) :
    %%         border<br>margin-...<br>(top-right-bottom-left) :
    %%         padding<br>margin-...<br>(top-right-bottom-left)

    section Part 11 – CSS display..<br>(Part_11_CSS_display_flex_grid/)
        display; flex:
          mise en page unidirectionnel

        display; grid:
          mise en page bidirectionnel
    section Part 12 – CSS display hover<br>(Part_12_CSS_display_hover/)
        display; none:
          masque toute les composant de la class

        Melange de hover et display pour faire apparaitre des composant

    section Part 13 – CSS display hover<br>(Part_13_HTML_CSS_table/)


    section bonus my research - no Part..
        Correction de décalage<br>padding,margin,gap,etc<br>A cause de la scroll-bar:
            scrollbar-gutter:stable<br>alloue la place de la scroll-bar dans page html meme si non active


```

<br>

- [🗓 𝕊ummary](#summary)


<br>

---

<br>

<h2 id="requirements">🛠 ℝequirements</h2>

- un nagigateur pour afficher la 'NAMEFILE.html'
- aucune base en html besoin pour suivre le cours
<br>

- [🗓 𝕊ummary](#summary)

<br>

---

<br>

<h2 id="resources">ℝesources</h2>

- [W3schools doc/tutorial HTML][tagW3schools]
- [Mozilla documentation HTML][tagMozillahtml]
- [Mozilla documentation CSS][tagMozillacss]
<br>

- [🗓 𝕊ummary](#summary)

<br>

---

<br>

<h2 id="author">🖋 𝔸uthor</h2>

All implementation decisions and documentation were written and validated by the project author.

<br>

- [🗓 𝕊ummary](#summary)
