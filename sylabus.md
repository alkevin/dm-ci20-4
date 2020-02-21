# DM Continuous Integration (20.4)
​
## Sylabus
​
Fork le projet [GitHub - vmonjaret/dm-ci20-4](https://github.com/vmonjaret/dm-ci20-4)
​
Vous avez commencé un projet sous Symfony que vous aimeriez rendre Open-Source sur Github.
​
Votre objectif est donc de rendre le projet le plus accessible et de guider au mieux les développeurs qui souhaiterai contribuer à votre projet.
​
## Tâches
​
### Collaboration
​
Aider les contributeurs de votre projet.
​
- [ ] Template de Pull Request
- [ ] Templates d'issues (Feature, Bug, etc...)
- [ ] Readme.md
- [ ] Contributing.md
- [ ] Makefile
- [ ] Flow GIT
​
### Qualité de code
​
Automatiser le lancement des outils de Code Quality (n'hésitez pas à en rajouter).
​
- [ ] [Hadolint](https://github.com/hadolint/hadolint)
- [ ] [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer) (en mode dry-run avec le Ruleset de Symfony)
- [ ] [Security checker](https://github.com/sensiolabs/security-checker)
​
### Automatisation des tests
​
Automatiser le lancement des différents tests
​
- [ ] Tests unitaires
- [ ] Tests intégrations (à lancer également de manière planifié)
- [ ] Tests fonctionnels
​
### Automatiser docker images
​
Automatiser la création des images docker et l'envoie sur le registry de GitHub pour la **PRODUCTION**.
​
- [ ] Image PHP (`docker build --target=php -t <image_name> .`)
- [ ] Image Nginx (`docker build --target=nginx -t <image_name> .`)