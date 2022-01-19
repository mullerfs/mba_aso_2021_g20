# Arquitetura de Soluções - G20
Trabalho de entrega da Fase

# 1. Antes de começar
Certifique-se de criar o projeto com o nome do grupo
``` 
oc new-project fiap-aso-g20
```

# 2. Criação da Aplicação

```
oc new-app python:3.8~https://github.com/mullerfs/blog-django-py
```

# 3. Subindo Banco de dados


# 4. Aplicando Deployment com Enviroment variables

```
 oc apply -f deployments.apps.yaml
```
# 5. Aplicando Rotas

```
 oc apply -f routes.yaml
```
