# Source du site Web du Réseau Coworking Grand Lyon

Bienvenue sur le dépôt du code source du [site Web du __Réseau Coworking Grand Lyon__](https://coworking-grandlyon.org/).
Vous êtes au bon endroit si vous souhaitez mettre jour le contenu, la mise en page, etc.

> *Si vous souhaitez plutôt commencer par rejoindre le réseau, contactez-nous : coworking.grandlyon@gmail.com !*

## Contribuer au site

Commencez par créer un compte sur [Framagit](https://framagit.org/users/sign_up).
> __Framagit__ est la forge logicielle sur laquelle vous êtes actuellement, hébergée par l'association [__Framasoft__](https://framasoft.org), qui nous permet à notre tour d'héberger le site du __Réseau Coworking Grand Lyon__.
> Le code est ouvert et tout le monde peut y participer, le partager, etc.

_NB : votre compte sera validé manuellement par un bénévole de Framasoft : soyez patient·e, car cela peut prendre quelques jours._

En attendant, si cela n'est pas déjà fait, vous pouvez déjà préparer votre nouvelle fiche espace (ou préparer vos modifications sur votre fiche existante).

### Préparer ma nouvelle fiche

Si vous ajouter un nouvel espace sur le site (bienvenue !), commencez par créer votre brouillon, par exemple en cliquant sur le lien suivant : https://pad.georgette.party/new?both

> Vous pouvez copier le contenu d'une page d'un autre espace dans votre brouillon pour l'utiliser comme modèle :
> - https://framagit.org/coworking-grand-lyon/coworking-grand-lyon.frama.io/-/raw/master/content/espace/locauxmotiv.md?ref_type=heads
> - https://framagit.org/coworking-grand-lyon/coworking-grand-lyon.frama.io/-/raw/master/content/espace/lacordee.md?ref_type=heads
> - https://framagit.org/coworking-grand-lyon/coworking-grand-lyon.frama.io/-/raw/master/content/espace/amabla.md?ref_type=heads

Ensuite, il est temps de mettre à jour le site avec votre nouvelle fiche !

### Mettre à jour le site

Une fois que votre compte __Framagit__ est validé, vous pouvez proposer une modification du contenu directement — pour intégrer les contenus de votre brouillon, ou pour faire des modifications sur l'existant.

**Tout le contenu des pages (accueil, charte…) est accessible dans le dossier [`content`](https://framagit.org/coworking-grand-lyon/coworking-grand-lyon.frama.io/-/tree/master/content?ref_type=heads)**.
Les fiches espaces sont dans le sous-dossier [`content > espace`](https://framagit.org/coworking-grand-lyon/coworking-grand-lyon.frama.io/-/tree/master/content/espace?ref_type=heads).

_Les images du site sont elles dans le dossier [`static > images`](https://framagit.org/coworking-grand-lyon/coworking-grand-lyon.frama.io/-/tree/master/static/images?ref_type=heads). NB : vous pouvez ajouter les images de votre espace (logo, illustration) sur le framagit, ou plus simplement utiliser des images déjà en ligne, sur votre site internet par exemple, en récupérant simplement leur lien (clic droit > copier le lien de l'image) pour l'intégrer dans votre contenu. Assurez-vous juste  dans tous les cas que la qualité soit suffisante, mais le fichier pas trop lourd quand même (ordre de grandeur de 300-500ko maximum) !_

> NB : dans la plupart des cas, une dernière confirmation manuelle de votre intervention par un mainteneur du site est nécessaire, votre modification n'apparaitra donc pas directement. Vous devriez cependant la retrouver dans la section [`Merge request`](https://framagit.org/coworking-grand-lyon/coworking-grand-lyon.frama.io/-/merge_requests)" (accessible dans la section `Code` du menu à votre gauche).

#### Ajouter une fiche
Pour ajouter une fiche, il suffit d'ajouter votre fichier .md (markdown) dans le dossier [`content > espace`](https://framagit.org/coworking-grand-lyon/coworking-grand-lyon.frama.io/-/tree/master/content/espace?ref_type=heads) (ou de le créer, et d'y copier-coller votre brouillon), via le bouton "+" en haut de la liste des fichiers. _Nommez bien votre fichier sur le format "nom-de-lespace.md"._
> Astuce : pour récupérer votre brouillon en .md depuis le "pad georgette", cliquez sur le "Menu" en haut à droite, puis "télécharger Markdown".

_**Attention**, votre fiche doit aussi être **ajoutée manuellement sur la carte** des espaces (affichée sur la page d'accueil). Retrouvez le lien d'édition dans le dossier `Communication > SiteWeb` du Drive (si vous ne savez pas y accéder, contactez-nous)._

#### Modifier un contenu existant
Pour mettre à jour un contenu existant, vous pouvez éditer le fichier concerné directement (menu bleu une fois le fichier ouvert en haut à droite, `Edit > Edit single file`, puis enregistrez en cliquant sur le bouton bleu en bas de page `Commit changes`), ou suivre le **mode d'emploi** (disponible sur le drive du réseau, dans Communication > SiteWeb — _si vous ne savez pas y accéder, contactez-nous_).

## FAQ

- __Je ne suis pas trop *geek*, comment ça marche ?__
Si vous voulez tenter quand même, vous pouvez retrouver un mode d'emploi à suivre dans le dossier "Communication > SiteWeb" du Drive CWGL. Vous pouvez aussi vous rapprocher d'un·e *geek* de votre espace pour vous aider dans cette tâche ! Ou encore faire appel au collectif, on pourra vous aider aussi :) 

- __J'ai repéré une erreur / une faute / un problème sur le site, mais je ne suis pas à l'aise pour corriger ça moi-même, que faire ?__
Merci de [déposer une "issue"](https://framagit.org/coworking-grand-lyon/coworking-grand-lyon.frama.io/-/issues/new) (un ticket) sur le projet (accessible dans la section `Plan` du menu de gauche). Un titre clair et une description détaillée si possible suffiront, ne vous embêtez pas avec les autres champs. Et on pourra vous aider à partir de là.

- __J'ai fait des modifications/ajouts, mais je ne les vois pas apparaitre sur le site web ?__ Pour éviter les mauvaise manipulations, il faut que les modifications soient confirmées par l'une des mainteneurs du site. Nous essayons de nous en occuper dans les plus brefs délais mais ça peut prendre un peu de temps… Merci de votre patience !

- __J'ai fait une erreur pendant une modification, que faire ?__ Pas de panique ! Si la modification n'a pas encore été confirmée par un mainteneur, vous pouvez l'annuler (ou mettre un commentaire pour signaler l'erreur aux mainteneurs) dans les [`Merge request`](https://framagit.org/coworking-grand-lyon/coworking-grand-lyon.frama.io/-/merge_requests). Sinon, Gitlab conserve toutes les versions d'un même fichier, donc on devrait toujours pouvoir revenir en arrière :) Déposez une [`Issue`](https://framagit.org/coworking-grand-lyon/coworking-grand-lyon.frama.io/-/issues/new) et on regardera ça ensemble !

## Technologies

- [Hugo]
- This project's static Pages are built by [GitLab CI][ci], following the steps
defined in [`.gitlab-ci.yml`](.gitlab-ci.yml).
- Markdown


### Développement

To work locally with this project, you'll have to follow the steps below:

1. Fork, clone or download this project
1. [Install][] Hugo
1. Preview your project: `hugo server`
1. Add content
1. Generate the website: `hugo` (optional)

Read more at Hugo's [documentation][].

### Preview your site

If you clone or download this project to your local computer and run `hugo server`,
your site can be accessed under `localhost:1313/hugo/`.

The theme used is adapted from http://themes.gohugo.io/beautifulhugo/.

[ci]: https://about.gitlab.com/gitlab-ci/
[hugo]: https://gohugo.io
[install]: https://gohugo.io/overview/installing/
[documentation]: https://gohugo.io/overview/introduction/
[userpages]: http://doc.gitlab.com/ee/pages/README.html#user-or-group-pages
[projpages]: http://doc.gitlab.com/ee/pages/README.html#project-pages
[post]: https://about.gitlab.com/2016/04/07/gitlab-pages-setup/#custom-domains
