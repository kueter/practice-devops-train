# practice-devops-train

[APPLICATION](https://github.com/kueter/angular-dashboard-ui)

Mettrez en place une chaine ci/cd pour automatiser les processes de deploiement d'une equipe de developpeurs Front tout en respectant les bonne pratiques.
Features: 
- activation des webhooks
- les pipelines doivent s'executer pendant Pull Request
- l'administrateur doit recevoir une notification par mail pour les __failed jobs__  
- tags de vos images en dev ou en prod doivent etre enregistrer sur 2 repos differents: docker_username/myapp_dev:tagVersion && docker_username/myapp_prod:tagVersion
- scan de vulnerabilites de l'image avec trivy : faire echouer le pipeline si __severity is HIGH__

Environment : Jenkins, Github, docker , Kubernetes 



Mettre sur repo github votre  

- Jenkinsfile
- Makefile
- Dockerfile
- un Dossier contenant 2 fichiers yaml : pour le deployment Resource et Les Services pour exposer l'application

