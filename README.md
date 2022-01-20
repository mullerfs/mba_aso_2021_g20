# Arquitetura de Soluções - G20
Trabalho de entrega da Fase

# Passo a Passo
## 1. Crie o Projeto
Certifique-se de criar o projeto com o nome do grupo
``` 
oc new-project fiap-aso-g20
```

## 2. Faça o Deploy

```
oc create -f full.yaml
```

## 3. Inicie o banco de dados
```
oc exec `oc get pods -l deployment=blog-django-py|cut -d' ' -f1|tail -n1` -- /bin/sh -c ./setup
```
## 4. Acesse Web
# Saiba mais!

Repositório do Source Code: https://github.com/mullerfs/blog-django-py

Repositório das Configurações: https://github.com/mullerfs/mba_aso_2021_g20

Baixe a imagem: ``docker pull quay.io/mullerfs/blog-django-py``