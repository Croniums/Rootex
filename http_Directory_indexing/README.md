Etape 1 Trouver le chemin
Ici on va reprendre le même concept que le phpbb.
C’est-à-dire qu’on va tout simplement chercher à trouver dans le code un chemin qui nous emmènera sur le mot de passe à rentrer.
Donc on va inspecter simplement la page et on peut tomber sur ceci qui semble intéressant

<img src="/Image7.png" alt="My cool logo"/>
 
Cela semble une réponse gratuite de la part du site, mais en réalité ce chemin si pratique et facile se contente juste de nous rediriger vers un lien troll, ou l’on nous dit bien gentiment que ça serait trop simple sinon.
 
<img src="/Image8.png" alt="My cool logo"/>

J’ai cherché pendant plusieurs minute pour comprendre ou je pouvais trouver un chemin autre part mais il n’y en n’avait visiblement pas …
Etape 2 Chercher dans l’énoncée
Vu que je n’avais aucune piste et que scanner le site me soulais :’ ) je re regardé l’énoncé en quête d’indice.
Et en effet, j’ai bien fait !

<img src="/Image9.png" alt="My cool logo"/>
 
« La source te donnera l’indice… » un indice si simple qu’il pourrait passer pour inutile.
Mais en réalité la source n’est pas la source des fichier.
Mais du lien donné !
Reprenons notre lien blagueur.
http://challenge01.root-me.org/web-serveur/ch4/admin/pass.html
Ce dernier en le prenant a la source autrement dit le « /admin » nous permet de trouver des réponses à nos questions !

<img src="/Image10.png" alt="My cool logo"/>
 
Il nous uffit juste ensuite d’aller dans « backup/ » puis « admin.txt » et nous avons le mdp !
