# xtg-webtech

XTG WebTech Frontend rendered by Jekyll.

El objetivo es poder documentar *posts* y *articles* a través de github como hace Azure:
- https://azure.microsoft.com/en-us/documentation/articles/active-directory-b2c-setup-msa-app/

Hay git repos privados y publicos esté toda la documentación:

Separamos contenido en diferentes repos:
- http://jry.io/posts/make-your-jekyll-blog-awesome-with-git-submodules/
- Utilizamos git submodules para incluir este contenido

Estructura de directorios y repos:
- *_articles_pub*: https://github.com/XML-Travelgate/xtg-content-articles-pub -> (Publico) Articulos abiertos a todo el publico
- *_articles_pr*: https://github.com/XML-Travelgate/xtg-content-articles-pr   -> (Privado) Articulos que solo pueden leer los collaborators del proyecto https://github.com/XML-Travelgate/xtg-content-articles-pr
- *_posts*: https://github.com/XML-Travelgate/xtg-content-posts-pub -> (Publico) Blog

Canal de slack:
- https://xtgtech.slack.com/messages/prj-documentation/


Temas pendientes:
* Utilizar formateador Markdown que renderice igual que *git-hub* pages: (p.ej. que acepte '''ruby para syntax de codigo ruby)
* Utilizar modulo de seguridad https://github.com/benbalter/jekyll-auth para gestionar repo privado
* Finalizar CI/CD con Jenkins / Docker / PrivateRepo  
* Utilizar algún template opensource para organizar tipo https://labs.spotify.com/:
    * Todos los posts con Disqus
    * Stream de Twitter
    * Stream de Slack
    * Los posts/tags con tags




