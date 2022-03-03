# hacf-theme
Theme Hugo pour HACF.fr

Basé sur Bootstrap 5 et Font Awesome

### Gestion.
* [X] Bootstrap local
* [ ] Font Awesome local (via CDN pour le moment)
* [X] Workflow : Géneration, transfert vers FTP/SFTP.

### Optimisation.
* [ ] Organiser le theme.
* [X] link : Render-Link
* [X] Créé plusieurs tailles  et propose la plus adaptée.
* [X] Convertit les images en WebP ou jpg (pour safari)
* [ ] Image voir pour redimenssiomner au max de la taille d'origine et non argrandir.
* [X] Ajouter site propulsé dans footer
* [X] Ajouter la modification via GitHub
* [ ] Ajouter Modification GitHub pour Submodule.
* [X] Categories : hauteur constante (`classe="h-100"` ATTENTION non dispo pour `<a>`)
* [ ] (single) Page Article afficher HeroImg du Front Matter
* [X] (list) )Afficher HeroImg du Front Matter
* [ ] single : Ajouter les [articles en relation](https://bout2code.fr/tutos/creer-un-site-avec-hugo/comment-creer-un-site-avec-hugo-partie-7-ajouter-du-contenu-en-relation/)
* [ ] TOC (non fonctionnelle voir Markup Hugo Header)
  
#### Confidentialité
* [X] link : Ajouter target_blank dans partial RS rel="noreferrer"
* [ ] Vérifier les cookies.Aucun pour le moment
* [ ] Analyse via [Matomo](https://fr.matomo.org/) presentation [ici](https://zestedesavoir.com/tutoriels/2508/matomo-analytics/)


#### SEO
* [ ] single : Ajout du Head personalisé en fonction de la page (description et mots clés)
* [ ] single : Correction de l'affichage des keywords (suppression [] remplacé par une ", ")


#### Non urgent
* [ ] theme : Ajouter les options (affichage menu etc [ici](https://github.com/razonyang/hugo-theme-bootstrap/tree/master/layouts/partials/sidebar))
* [ ] Redimensionner Avatar (automatiquement)
* [ ] Integrer le resize image sur data/section.(Voir dans Assets https://mertbakir.gitlab.io/hugo/image-processing-in-hugo/)

### Shortcodes
#### Commun
* [X] Images : Ajouter shortcodes Gallery + image processing `{{< gallery folder="infos" >}}` infos=le nom du dossier contenant les images
* [X] single : Shortcode Alerte. `{{< alert "Message **succees**" success >}}` danger/sucess/warning/info.
* [X] single : Shortcode de citation `{{< quote "Message **citation**" "artiste **anonyme**" >}}`

#### HACF/McFlyPartages
* [X] Shortcode lien Forum HACF. 
```
Simple lien : 
{{< forumhacf "lien_vers_forum" "Titre_du_post">}} 
Multi liens : 
{{< multiforumhacf >}}
    {{< forumhacf "lien_vers_forum" "Titre_du_post">}}
    {{< forumhacf "lien_vers_forum" "Titre_du_post">}}
{{< /multiforumhacf >}}
```
* [X] Shortcode liens HA repositories et BluePrint `{{< haautoconfig bp "url" >}}` option `bp` pour blueprint ou `depot` pour repositories.
* [X] Shortcode user HACF et HACF `{{< userha "user" haoff >}}` option `hacf` ou `haoff`.