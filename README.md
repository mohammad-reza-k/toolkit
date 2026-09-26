# Overleaf Toolkit

only change is in the volumes so in base compose so we can access the templates.

lib/docker-compose.base.yml

volume added:
 - "/home/mohrez/projects/overleaf-5.5.2-source:/overleaf"
 - "/home/mohrez/projects/overleaf-template-storage:/var/lib/overleaf-template-storage"
      
