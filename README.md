![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Exercice guidé - IronSkydive 💪 - éléments de niveau bloc et inline

<br>

## Introduction

Au cours de ce module, vous vous familiariserez avec HTML et CSS. Les deux technologies combinées vous offrent tous les outils dont vous avez besoin pour créer un site web. HTML sans CSS est laid, et CSS sans HTML est... eh bien, rien !

C'est pourquoi vous travaillerez sur cet exercice à plusieurs reprises au cours de ce module. Notre objectif final est de créer un site web HTML & CSS de base, où vous pratiquerez les différents concepts au fur et à mesure de votre apprentissage.

<br>

## IronSkydive | Le site web de l'entreprise

Ironhack adore la programmation, mais nous aimons aussi pratiquer les sports extrêmes. Dans une nouvelle ligne de produits, nous avons créé une nouvelle entreprise appelée _IronSkydive_. Nous offrons une expérience complète de parachutisme.

Nous espérons que vous pourrez nous aider à créer notre site web car nous sommes débordés à lancer l'entreprise et en nous assurant que tous nos papiers sont en règle. :see_no_evil:

Comme mentionné précédemment, vous travaillerez sur cet exercice au cours des prochaines leçons, mais en fin de compte, votre objectif est:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_1f30ebb21258466ca36702d7cdaa0cad.png)

<br>

Vous travaillerez sur un nouveau pen, alors rendez-vous sur [CodePen](https://codepen.io/) et créez maintenant un nouveau pen. Prêt à sauter?

<br>

![](https://media.giphy.com/media/xT5LMrGIfLuDtRSAMg/giphy.gif)

<br>

### Partie 1 - Éléments bloc

Dans cette partie de l'exercice, vous allez travailler avec les éléments de bloc que vous avez appris. Vous avez vu comment les éléments de bloc sémantiques nous aident à mieux comprendre la composition de notre site web. Commençons par créer la structure HTML de base, qui sera la suivante:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_8f778c8cd703db596d5bb22dae089716.jpg)

<br>

Plus tard, dans l'exercice, nous allons distinguer les différentes sections que nous avons. Maintenant, ajoutons quelques éléments de bloc supplémentaires à l'intérieur de chaque élément.

### Nav

À l'intérieur de `<nav>`, créez une balise `<ul>` avec trois éléments:

- Day Structure
- Team
- Schedule

Ce seront nos options de menu.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_ace26745798b17492d307e0d0c817ea4.png)

<br>

### Header

Vous devez créer deux choses différentes ici :

- tout d'abord, créez une balise `<h1>` avec le texte "IronSkydive", puis
- sous cette balise, créez une balise `<h2>` avec le texte "Let the trip begin” et enfin
- sous ces balises, créez une balise `<aside>` qui contiendra une citation.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_3c0c7f97d3804c728475f52c89f0ec85.png)

<br>

### Section 1

Cette section a un fond sombre qui couvrira toute la largeur du site web. Vous ajouterez la couleur de fond plus tard, donc pour l'instant, pas besoin de s'inquiéter à ce sujet.

Elle contiendra trois balises `<article>` pour ajouter les informations sous le header.

À l'intérieur de chaque `<article>`, ajoutez une balise `<h3>` pour les différents titres, et un paragraphe pour le texte blanc. Le résultat ressemblerait à ceci:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_f004e36a2b2bb0dfc02ac008e5d5c97e.png)

<br>

### Section 2

Cette section est assez similaire à la précédente. Dans ce cas, la section contiendra un titre `<h3>` avec le texte "How do we structure the day?”, puis un `<div>` avec quatre balises `<article>` différentes.

À l'intérieur de chaque balise _article_, pour le moment, nous allons avoir une balise `<h4>` avec le titre de l'article, et une balise `<p>` avec le contenu de l'article.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_c810d2f904e4c4e72ad8b9ed055e4b37.png)

<br>

### Section 3

Ce cas est le même que **Section 1** - il aura un fond sombre, et, comme dans les sections précédentes, vous devez ajouter un titre `<h3>` et un `<p>` avec une brève description.

Ensuite, vous créerez une balise `<div>` et ajouterez trois balises `<article>` vides qui contiendront les informations de chaque membre de l'équipe. Il suffit d'avoir un texte indiquant les différents articles:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_4bf21e881db9707b671a812c022db35f.png)

<br>

### Section 4

Dans cette section, nous avons une table qui contient le calendrier.

Commençons par ajouter deux en-têtes `<h3>` différents avec le texte:

- Schedule (Calendrier)
- Schedule a Time Slot (Programmer un créneau horaire)

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_cdeeac1a34e5b4f5785ec6f203632b7c.png)

<br>

Ajoutez maintenant un tableau sous la première balise `<h3>`, qui contient le texte "Schedule”. En effet, ce tableau va contenir le calendrier IronSkydive pour la semaine. Le format du tableau est le suivant:

| Time          | Monday | Tuesday | Wednesday | Thursday | Friday | Saturday |
| ------------- | ------ | ------- | --------- | -------- | ------ | -------- |
| 9:00 - 11:00  |        |         | X         |          | X      | X        |
| 12:00 - 14:00 |        |         |           |          | X      | X        |
| 15:00 - 17:00 |        |         | X         | X        | X      | X        |

Créez le tableau et ajoutez le contenu nécessaire pour obtenir ce résultat:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_5c089d05a9df991db3784ba81a880835.png)

<br>

Rappelez-vous, en plus de la balise `<table>`, vous devez utiliser `<thead>` avec six balises `<th>` pour les lignes d'en-tête (six jours où IronSkydive opère), puis à l'intérieur du corps du tableau (`<tbody>`) vous devez définir des lignes avec des balises `<tr>`. En fin de compte, vous devez utiliser des balises `<td>` pour le contenu à l'intérieur des lignes.

### Footer (Pied de page)

Enfin, la section du pied de page doit contenir un seul élément `<section>`. À l'intérieur de cette balise `<section>`, vous devez ajouter plusieurs éléments dans l'ordre suivant :

- `<h5>` avec le titre "Contact Information" ("Informations de contact").
- Élément [`<address>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/address), avec les informations correctes :
  _IronSkydive 33 Rue la Fayette, 75009 Paris, France +33 (0) 619 193 088_
- `<h5>` avec le titre "Follow Us" ("Suivez-nous").
- Liste `<ul>` avec trois éléments:
  - Twitter.
  - Facebook.
  - Instagram.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_661b4572e673afb0ce5a419ae78b9ce8.png)

<br>

### Partie 2 - Éléments inline

Dans la deuxième itération de notre exercice, vous allez travailler avec les éléments inline que vous avez appris. Vous avez vu que nous utilisons différentes balises avec des objectifs différents. Rappelez-vous, voici notre structure de projet actuelle:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_8f778c8cd703db596d5bb22dae089716.jpg)

<br>

Vous allez ajouter différents éléments inline à toutes les sections que nous avons déjà.

### Nav

La balise `<nav>` est utilisée pour envelopper les liens sur notre site Web. Pour l'instant, nous avons juste une liste d'éléments. Changeons cela en ajoutant des _liens_ dans chaque élément de liste.

Vous devez créer trois liens différents qui pointeront respectivement vers `#structure`, `#team` et `#schedule`:

:bulb: Spoiler: les liens sont des balises ancre représentées par la balise `<a>` et ont besoin de l'attribut `href`. :wink:

```html
<a href="#structure">Day Structure</a>
```

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_53837d5c2b9d5e3c537a87079080151e.png)

<br>

### Header (En-tête)

L'en-tête du projet est incomplet. Tout d'abord, vous devez ajouter un logo à l'en-tête. Ajoutez également une _citation de témoignage_ où vous avez actuellement du texte de remplissage.

**Tout d'abord, le logo**. Ajoutez une image à l'intérieur de la balise `<h1>` qui charge l'image suivante:

`https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironhack-skydive-logo.png`.

N'oubliez pas d'ajouter un texte alternatif descriptif, au cas où l'image ne se chargerait pas. Une bonne option serait "Logo IronSkydive".

Il est courant de trouver des citations en _italique_ dans différents endroits, c'est donc ce que nous allons faire. Ajoutez la citation en italique (en utilisant des éléments en ligne) à l'intérieur de la balise `<aside>`, avec le texte "The best experience of our lives" ("La meilleure expérience de notre vie").
Sur une nouvelle ligne, cette fois en utilisant un élément _bloc_ (`<p>`), ajoutez les noms des auteurs. Les noms seront "Ariel Quiñones & Gonzalo Manrique, Fondateurs d'Ironhack".

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_0f0563ef2d64bd9a7bdf5d401bca9c16.png)

<br>

### Section 1

Dans la première section, nous avons trois articles différents. Chacun a une balise `<h3>` et une balise `<p>` à l'intérieur. Ajoutons un lien sous chaque paragraphe. Ce lien n'a pas besoin de pointer quelque part.

<br>

:::info
Nous pouvons créer un lien sans URL spécifique en fournissant un dièse dans l'attribut `href`:
<br>

```html
<a href="#">Link text</a>
```

:::

<br>

Ajoutez trois liens, un dans chaque section, dans cet ordre:

- Learn More
- Watch Video
- Register

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_016b92205b14c5a93d86d324547cf86e.png)

<br>

### Section 2

Dans cette section, nous avons quatre articles différents qui contiennent des informations sur la façon dont une journée typique chez IronSkydive est structurée. Ajoutons des icônes descriptives à chaque section.

Les différentes icônes, dans le bon ordre, sont:

- `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-training.png`
- `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-get-ready.png`
- `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-fly.png`
- `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-jump.png`

N'oubliez pas d'ajouter un texte alternatif descriptif dans l'attribut alt. Chacune des sections aura ce format avec des images différentes:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_3aa54eab8bec42f35381b704d5c7b06e.png)

<br>

### Section 3

Ajoutons les informations de l'équipe dans cette section. Vous devriez avoir trois articles différents sans aucune information. À l'intérieur de chaque article, vous ajouterez le nom du membre de l'équipe en **gras** (mais c'est quelque chose dont vous vous occuperez lorsque nous en viendrons au style). Vous pouvez utiliser la balise de niveau bloc, `<h4>` pour envelopper chaque nom. Sous le nom, vous devrez ajouter la photo du membre de l'équipe. Vous pouvez trouver les images ici:

- **Harold Rothstein**, `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_c18b1c463b80090894237a262dfdfbad.jpg`
- **Susan Phillips**, `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_a18d6123a7c8e75f7e70a4e59b941093.jpg`
- **Taylor Roberts**, `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_7104a331530d1b0611da55093b7dc421.jpg`

N'oubliez pas d'ajouter un texte alternatif au cas où l'image ne se charge pas. Ces images sont assez grandes, mais nous les gérerons plus tard grâce à CSS.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_845dbf46e21d7bb275bdb5b23ff17aa6.gif)

<br>

Pour terminer cette section, ajoutons un `<hr>` entre le paragraphe et les informations des membres de l'équipe.

### Section 4

_Rien à ajouter!_

### Footer (Pied de page)

Tout d'abord, formatez l'adresse. Pour l'instant, toutes les informations sont sur une seule ligne. Utilisons des balises `<br>` pour séparer les différentes sections de l'adresse.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_cf1a7806a1a921e018aa46c428d67a17.png)

<br>

Enfin, ajoutez des liens vers tous les réseaux sociaux où les utilisateurs peuvent suivre IronSkydive. Vous pouvez créer des liens vides (avec le dièse dans l'attribut `href`), ou ajouter des liens vers les réseaux sociaux. Dans les deux cas, un nouvel onglet doit s'ouvrir lorsque les utilisateurs cliquent sur les liens.

<br>

:::info
:bulb: Utilisez l'attribut [`target`](https://html.com/attributes/a-target/) de l'ancre pour ouvrir un lien dans un nouvel onglet. (le mot target est cliquable, alors n'hésitez pas à explorer un peu - rappelez-vous, vous n'avez pas besoin de mémoriser quoi que ce soit, sachez où trouver les réponses dont vous avez besoin.)
:::

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_27057afe7732d2b6f26ce69eb00a63ec.png)

<br><br>

:heart: **Happy coding!**
