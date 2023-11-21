## Création d’un serveur LDAP

- Le conteneur peut être requis par plusieurs services et il est alors nécessaire de l'accéder depuis plusieurs réseaux si on veut que les services puissent communiquer entre eux et certains être isolés.
- Les ports jusqu'à 1024 sont réservés au superutilisateur (root) et ne peuvent être ouverts par un utilisateur normal.

## Creation d'un application WEB

- Traefik agit sur la couche 7 du modèle OSI, la couche application.
Dans certains cas il peut agir sur la couche 4, la couche transport, pour faire du load balancing TCP ou UDP.
- Une ingress est un point d'entrée dans le cluster Kubernetes. C'est un objet qui permet de configurer les règles de routage pour les requêtes entrantes.
Un middleware est un composant qui permet de modifier les requêtes HTTP entrantes ou sortantes (par ex pour de l'authentification).
Un plugin est un composant qui permet d'étendre les fonctionnalités de Traefik (par ex pour ajouter des métriques).
- PathPrefix(`/api`) dans Traefik permet de rediriger les requêtes qui contiennent `/api` vers le service `api`.
- La passerelle HTTP ou HTTPS est le seul service qui doit être exposé à l'extérieur, le seul disposant des certificats HTTPS...