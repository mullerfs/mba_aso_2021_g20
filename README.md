# Arquitetura de Soluções - G20
Trabalho de entrega da Fase

# 1. Antes de começar
Certifique-se de criar o projeto com o nome do grupo
``` 
oc new-project fiap-aso-g20
```

# 2. Criação da Aplicação via Template

```
oc new-app app-g20.json -p SOURCE_REPOSITORY_URL=https://github.com/mullerfs/blog-django-py
```
