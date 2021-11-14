# [URL Shortener Microservice](https://www.freecodecamp.org/learn/back-end-development-and-apis/back-end-development-and-apis-projects/url-shortener-microservice)
Développement back-end et API
Projets de développement back-end et d'API
Microservice de raccourcissement d'URLPassé
Créez une application JavaScript à pile complète qui est fonctionnellement similaire à celle-ci : https://url-shortener-microservice.freecodecamp.rocks/ . Travailler sur ce projet vous obligera à écrire votre code en utilisant l'une des méthodes suivantes :

Clonez ce dépôt GitHub et terminez votre projet localement.
Utilisez notre projet de démarrage Replit pour terminer votre projet.
Utilisez un constructeur de site de votre choix pour terminer le projet. Assurez-vous d'intégrer tous les fichiers de notre référentiel GitHub.
Lorsque vous avez terminé, assurez-vous qu'une démo fonctionnelle de votre projet est hébergée dans un endroit public. Ensuite, soumettez-lui l'URL dans le Solution Linkchamp. En option, soumettez également un lien vers le code source de vos projets sur le GitHub Linkterrain.

ASTUCE : N'oubliez pas d'utiliser un middleware d'analyse de corps pour gérer les requêtes POST. Vous pouvez également utiliser la fonction dns.lookup(host, cb)du dnsmodule principal pour vérifier une URL soumise.

Lien de solution
ex : https://project-name.camperbot.repl.co/
Lien GitHub
ex : https://github.com/camperbot/hello

/**
*
* Votre sortie de test ira ici
*
*
*/
Vous devez fournir votre propre projet, pas l'exemple d'URL.

Vous pouvez POSTER une URL vers /api/shorturlet obtenir une réponse JSON avec les propriétés original_urlet short_url. Voici un exemple :{ original_url : 'https://freeCodeCamp.org', short_url : 1}

Lorsque vous visitez /api/shorturl/<short_url>, vous serez redirigé vers l'URL d'origine.

Si vous transmettez une URL non valide qui ne respecte pas le http://www.example.comformat valide , la réponse JSON contiendra{ error: 'invalid url' }

