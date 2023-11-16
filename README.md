# Dojo – Grupo 5

## Temas

- Django
- Inicialização ao docker
- Deploy Render

## Django

### Comandos 

1. Criar projeto
```django-admin startproject nome_do_projeto```
2. Criar aplicação
```python manage.py startapp nome_da_app```
3. Criar migrações
``` python mananage.py makemigrations ```
4. Executar Migrações
```python manage.py migrate```
5. Executar Servidor de Desenvolvimento
```python manage.py runserver```

## Docker
Docker é um conjunto de produtos de plataforma como serviço que usam virtualização de nível de sistema operacional para entregar software em pacotes chamados contêineres. Os contêineres são isolados uns dos outros e agrupam seus próprios softwares, bibliotecas e arquivos de configuração.

- Imagem: Uma imagem Docker é um pacote executável que inclui tudo o que é necessário para executar um aplicativo, incluindo o código, um ambiente de execução, bibliotecas, dependências e configurações. Base para criação do container.

- Docker-compose: Ferramenta adicional do docker que permite definir e gerenciar aplicativos Docker compostos por vários containers.

### Pré- requisito
- Ter o docker e o docker-compose instalado


### Comandos usados
1. Criar imagem pelo docker compose
   ```docker-compose up --build```

### Comandos adicionais
1. Criar imagem
   ``` docker build -t nome_da_sua_imagem:tag ```
2. Ver as imagens ```docker image ls```
3. Ver os containers ```docker ps```

    ...

# Deploy Render
[Render](https://render.com/) é uma plataforma conhecida por oferecer serviços de hospedagem para aplicativos da web, proporcionando uma experiência de deploy simplificada.
