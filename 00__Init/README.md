##################"
<center><image src="https://github.com/evgenkarlson/ALL_SCHOOL_42/raw/master/03_Norme____(%D0%9D%D0%BE%D1%80%D0%BC%D1%8B_%D0%B8_ %D0%9F%D1%80%D0%B0%D0%B2%D0%B8%D0%BB%D0%B0_%D0%A8%D0%BA%D0%BE%D0%BB%D1%8B)/ src/page1image3852832-small-13.png"></center>
</br>
<center><h2>Administration système et réseau</h1></center>
</br>
<center><h2>init</h2></center>
</br>
<center><i>Résumé : Introduction à l'administration système et réseau</i></center>
</br>
</br>
</br>

# Chapitre I.

## Avant-propos

</br>

Croyez-le ou non, ce projet est né un soir de beuverie. Oui, c'est vrai, quand nous avons décidé de lancer ces articles et cette dédicace, nous n'étions absolument rien.

Au siège de `Slash16` [Yellow Mad Monkey](https://www.yellowmadmonkey.com/), après que tout le monde dans l'équipe ait bu beaucoup de bouteilles, dont trois "Grey Goose", une "Absolut", deux " Jäger" et un "Havana Club" de sept ans (qui mérite d'être mentionné), nous avons eu une excellente idée : créer des sujets d'introduction sur l'administration système et réseau.

Donc, bien sûr, nous n'écrivions pas de sujets là-bas à l'époque, même si, en fait, nous le pouvions, nous finirions tous par nous saouler de toute façon, donc c'était une mauvaise idée ...

Quoi qu'il en soit, après tant de temps avec le narguilé, des mojitos frais et une bonne playlist [Trace Urban VocalTeknix](https://youtu.be/W0l81iYp6n4?list=PL8kREmwZBbARsIwdgZLVRcI8quzIIoySp) pour nous remonter le moral, voici - enfin - nous vous apportons notre résultat !

Nous espérons qu'il vous plaira et n'oubliez pas que ce n'est que le début !

Bisous et chocolats

Commande `Slash16`.


</br>
</br>
</br>

# Chapitre II.

## Buts

Ce premier projet, `init`, vous donnera une introduction aux commandes système et réseau de base, à de nombreux services utilisés sur le serveur et à quelques idées de script que les administrateurs système peuvent utiliser au quotidien.


</br>
</br>
</br>

# Chapitre III.

## Instructions de base

Vous ne devez utiliser que les commandes du terminal pour effectuer tous les exercices de ce sujet.

Il y a trois types de questions dans ce projet. Vous pouvez déterminer le type de réponse attendue à l'aide d'un code couleur :

:blue_heart : Bleu - équipe

:green_heart : Vert - sortie de la commande

:coeur: En rouge - la déduction écrite dans vos mots

    - Créez un dossier pour chaque partie de ce thème à la racine de votre référentiel. Ces dossiers doivent être nommés `network`, `system` et `scripts`. Enregistrez vos réponses dans un fichier nommé d'après le numéro à deux chiffres de la question. Par exemple : La réponse à la question `01` de la partie `network` doit se trouver dans le fichier `network/01`.

    - Soumettez vos scripts en tant qu'exécutables.

> La partie 1 - `Network` (Réseau) doit être effectuée sur les ordinateurs de l'école `Mac`. Les parties 2 et 3, `System` et `Scripting` doivent être exécutées dans la machine virtuelle `Debian` (pensez `live CD debian`).

</br>
</br>
</br>

# Chapitre IV.

## Partie obligatoire

</br>

### V.1 Soyons amis

Suivez `Slash16` sur [Facebook](https://www.facebook.com/slash16), [Twitter](https://twitter.com/slashseize) et [Linkedin](https://www.linkedin.com /entreprise/5277426).

</br>

### Réseau V.2

1. :blue_heart : Obtenir une liste des interfaces réseau de la machine sans afficher aucun détail pour ces interfaces. Juste une liste de noms

2. :blue_heart : Définir et afficher les caractéristiques de l'interface "Ethernet" :
a) Déterminer l'adresse de diffusion
b) Déterminer toutes les adresses IP qui font partie du même réseau

3. :blue_heart : Trouver l'adresse MAC de la carte Wi-Fi

4. :blue_heart : définir la passerelle par défaut dans la table de routage

5. :blue_heart : Déterminez l'adresse IP DNS qui répond à l'URL suivante : "slash16.org"

6. :blue_heart : Récupère le chemin d'accès complet au fichier qui contient l'adresse IP du serveur DNS que vous utilisez

7. :blue_heart : Interroger un serveur DNS externe sur le nom de domaine "slash16.org" (par exemple, google est "8.8.8.8")

8. :blue_heart : Trouvez le fournisseur "slash16.org"

9. :green_heart : Trouvez l'adresse IP externe "42.fr"

10. :blue_heart : Identifiez les périphériques réseau entre votre ordinateur et le domaine "slash16.org"

11. :blue_heart : Utilisez la sortie de la commande précédente pour trouver le nom et l'adresse IP de l'appareil qui communique entre vous (LAN) et le monde extérieur

12. :blue_heart : Trouvez l'adresse IP qui vous a été attribuée par le serveur DHCP

13. :green_heart: Grâce à la question précédente et inverse "DNS" trouvez votre hostname

14. :heart: Quel fichier contient les entrées "DNS" locales ?

15. :heart : Redirigez "intra.42.fr" vers "46.19.122.85"

</br>

### Système V.3

1. :heart: Dans quel fichier pouvez-vous trouver la version installée de votre "Debian" ?

2. :blue_heart: Quelle commande pouvez-vous utiliser pour renommer votre système ?

3. :heart: Quel fichier doit être modifié pour le rendre permanent ?

4. :blue_heart: Quelle commande affiche le temps écoulé depuis le dernier démarrage de votre système ?

5. :blue_heart : Nommez la commande qui détermine l'état du service "SSH"

6. :blue_heart
