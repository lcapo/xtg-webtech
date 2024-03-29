# xtg-webtech

XTG WebTech Frontend rendered by Jekyll.

## Objetivo
El objetivo es poder documentar *posts* y *articles* a través de github tal como hace Azure:
- https://azure.microsoft.com/en-us/documentation/articles/active-directory-b2c-setup-msa-app/

## Organización
Se separan los repos (github) de documentación y del site. También hay repos públicos y repos privados:
- http://jry.io/posts/make-your-jekyll-blog-awesome-with-git-submodules/
- Utilizamos git submodules para incluir este contenido

Estructura de directorios y repos:
- *_articles_pub*: https://github.com/XML-Travelgate/xtg-content-articles-pub -> (Publico) Articulos abiertos a todo el publico
- *_articles_pr*: https://github.com/XML-Travelgate/xtg-content-articles-pr   -> (Privado) Articulos que solo pueden leer los collaborators del proyecto https://github.com/XML-Travelgate/xtg-content-articles-pr
- *_posts*: https://github.com/XML-Travelgate/xtg-content-posts-pub -> (Publico) Blog

## Tareas pendientes
* Utilizar formateador Markdown que renderice igual que *git-hub* pages: (p.ej. que acepte 3 apostrofes para renderizar codigo, '''ruby para syntax de codigo ruby)
* Utilizar modulo de seguridad https://github.com/benbalter/jekyll-auth para gestionar repo privado
* Finalizar CI/CD con Jenkins-Docker-PrivateRepo  
* Organizar estructura de repos como https://github.com/Azure/azure-content (Por directorios dinámicos)
* Utilizar template opensource para organizar información tipo https://labs.spotify.com/:
* Organizar estructura de home como https://azure.microsoft.com/en-us/documentation/articles/active-directory-b2c-setup-msa-app/   
    * Pagina inicio con posts en el centro, Stream de Twiter y Disqus
    * Menú con link a articulos publicos organizados como (https://azure.microsoft.com/en-us/documentation/articles/active-directory-b2c-setup-msa-app/)
    * Link a area privada (login required) con los articulos privados organizados como los públicos
* Migrar documentación API (ahora con Readthedocs) a articulos publicos
* Migrar wiki Redmine a articulos privados

## Slack Channel:
* https://xtgtech.slack.com/messages/prj-documentation/





