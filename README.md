# hacf-theme
Theme Hugo pour HACF.fr

Basé sur Bootstrap et front wesome

## Fait
* [X] Convertit les images en WebP ou jpg (pour safari) et 
* [X] Créé plusieurs tailles  et propose la plus adaptée.
* [X] Ajouter site propulsé dans footer
* [X] Ajouter la modification via GitHub
* [X] link : Render-Link
* [X] link : Ajouter target_blank dans partial RS rel="noreferrer"

* [X] Images : Ajouter shortcodes Gallery + image processing `{{< gallery folder="infos" >}}` infos=le nom du dossier contenant les images
* [X] single : Shortcode Alerte. `{{< alert "Message **succees**" success >}}` danger/sucess/warning/info.
* [X] single : Shortcode de citation `{{< quote "Message **citation**" "artiste **anonyme**" >}}`
* [X] Shortcode liens HA repositories et BluePrint `{{< haautoconfig bp "url" >}}` option `bp` pour blueprint ou `depot` pour repositories.
* [X] Shortcode user HACF et HACF `{{< userha "user" haoff >}}` option `hacf` ou `haoff`.
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



* [ ] Categories : hauteur constante
* [ ] theme : Ajouter les options (affichage menu etc [ici](https://github.com/razonyang/hugo-theme-bootstrap/tree/master/layouts/partials/sidebar))
* [ ] single : Ajout du Head personalisé en fonction de la page (description et mots clés)
* [ ] single : Correction de l'affichage des keywords (suppression [] remplacé par une ", ")
* [ ] index : Exclure Page de la liste d'article
* [ ] Image voir pour redimenssion max de la taill d'origine.

## A faire
* [ ] Workflow : transfert vers ftp site officiel [Deploy ftp](https://github.com/marketplace/actions/ftp-deploy)
* [ ] Single afficher HeroImg du Front Matter
* [X] List Afficher HeroImg du Front Matter
* [ ] Vérifier les cookies.Aucun pour le moment
* [ ] Analyse via [Matomo](https://fr.matomo.org/) presentation [ici](https://zestedesavoir.com/tutoriels/2508/matomo-analytics/)
* [ ] Verifier la modification via GitHub des Submodules
* [ ] Redimensionner Avatar
* [X] Section HA Off
* [ ] Section Historique ameliorer (chemin)
* [ ] Hero TOHA
* [X] Projets TOHA (Github Dev)
* [ ] Derniers Post
* [ ] Page Association
* [ ] Page Reglement
* [ ] Monitoring Via [UpTimeRobot](uptimerobot.com)
* [ ] single : Ajouter les [articles en relation](https://bout2code.fr/tutos/creer-un-site-avec-hugo/comment-creer-un-site-avec-hugo-partie-7-ajouter-du-contenu-en-relation/)
* [ ] Page Statut
* [ ] Page Protection
* [X] Page A-propos
* [ ] Page Protection des données
* [ ] Page Liens Affilies
* [ ] Awesome (submodule)
* [ ] Developpeur (submodule)
