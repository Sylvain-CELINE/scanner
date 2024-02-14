# scanner
Scanner de site HTTP 

## Scanner de redirection vers Okta

### Présentation
Le scan interroge l'url passée en paramètre et suis les redirections HTTP. Si le mot clé okta est trouvé dans les URL redirigées, Okta est considéré comme installé.

### Usage
./isokta.sh <url>

En sortie, une liste CSV avec l'url testé et un indicateur de redirection vers Okta.

Exemple : 
$ ./isokta.sh https://www.celine.com
https://www.celine.com, Pas d'Okta
