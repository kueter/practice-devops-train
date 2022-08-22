# practice-devops-train

Mettrez en place une chaine ci/cd pour automatiser les processes de deploiement d'une equipe de developpeurs Front tout en respectant les bonne pratiques.
Features: 
- activation des webhooks
- les pipelines doivent s'executer pendant Pull Request
- scan constant du repo et des branches qui le composent
- l'administrateur doit recevoir une notification par mail pour toute issues du build du step
- tags de vos images en dev ou en prod doivent etre enregistrer sur 2 repos differents: docker_username/myapp_dev:tagVersion && docker_username/myapp_prod:tagVersion

Environment : Jenkins, Github, docker  

