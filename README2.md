Mettre en prod avec github pages
Nécessite que le contenu de /build soit contenu dans un dossier /docs, avec tous les éléments de statics remontés à la racinde de /docs.
Il faut aussi changer les chemin de static/css et static/js par ./ dans le index.html du /docs pour que ça fonctionne !
Et changer les chemins vers les images : suivre p-e ça https://itnext.io/so-you-want-to-host-your-single-age-react-app-on-github-pages-a826ab01e48