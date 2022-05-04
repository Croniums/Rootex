Etape 1 récupérer le fichier et le lire
Pour cela je vais utiliser le logiciel wireshark afin de pouvoir lire cette session d’authentification de Twitter ce qui va me permettre d’afficher les échange qui se sont produit l’ors de cette connexion et d’en extraire le mot de passe
Etape 2 chercher dans les échange l’élément voulu
Une fois le fichier extrait nous allons pouvoir avoir une multitude de choix que nous pouvons explorer. Cependant nous voulons récupérer un mot de passe autrement dis un texte qui va être rentré dans une zone de texte sur notre page internet. Donc nous allons nous intéresser à l’onglet « Hypertext Transfer Protocol »

<img src="/Image1.png" alt="My cool logo"/>
 

Nous pouvons dès a présent dérouler un peut tout les onglets présent afin d’avoir une vue global sur notre section.
Mais si nous faisons attention un des onglet est intéressant.
 
<img src="/Image2.png" alt="My cool logo"/> 

L’onglet « Authorization » qui nous permet d’accéder à l’information transmises par le site internet, comme notamment …

<img src="/Image3.png" alt="My cool logo"/> 
 
Notre mot de passe a rentrer sur root me ! (En rouge)
Et on peut même récupérer le nom d’utilisateur si on le souhaite (en vert)
