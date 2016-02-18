# xtg-webtech

XTG WebTech Frontend rendered by Jekyll.

El objetivo es coger documentar posts y articles a través de github como hace azure:
- https://azure.microsoft.com/en-us/documentation/articles/active-directory-b2c-setup-msa-app/

Tendremos repos privados y publicos en github donde esté toda la documentación, separados en:

Separamos contenido en diferentes repos:
- http://jry.io/posts/make-your-jekyll-blog-awesome-with-git-submodules/
- Utilizamos git submodules para incluir este contenido

Estructura de directorios y repos:
- _articles_pub: https://github.com/XML-Travelgate/xtg-content-articles-pub -> (Publico) Articulos abiertos a todo el publico
- _articles_pr: https://github.com/XML-Travelgate/xtg-content-articles-pr   -> (Privado) Articulos que solo pueden leer los collaborators del proyecto https://github.com/XML-Travelgate/xtg-content-articles-pr
- _posts: https://github.com/XML-Travelgate/xtg-content-posts-pub -> (Publico) Blog

Temas pendientes:
- Utilizar formateador Markdown que genere codigo compatible con git-hub pages: (p.ej. que acepte '''ruby para syntax de codigo ruby)
- Utilizar modulo de seguridad https://github.com/benbalter/jekyll-auth para gestionar repo privado  



