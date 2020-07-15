# noteIt
Repositório para desenvolvimento de uma aplicação WEB com fins didáticos usando django + vue

# Estudar:
    -git
    -django
    -python web
    -vue 
    -javascript
    -mongodb
    -css
    -scss

# Criação do virtualenv:
    instalar python 3.7.2
    instalar pip
    pip install virtualenv
    virtualenv . #criando virtualenv
    source Script/activate #ativando virtualenv
    pip install django    

# Estrutura de pastas:
	app->
	   - server
	   - client
	   - manage.py

# Criação do backend (gerar django app na pasta backend):
    django-admin startproject backend #cria configurações de backend 
    python manage.py migrate (rodar dentro de backend) #cria banco de teste
    python manage.py runserver #rodou servidor
    python manage.py createsuperuser  #cria usuario teste

    python manage.py startapp [name] (rodar dentro de backend)

# Criação do frontend (gerar vue na past frontend):
    sudo npm install -g @vue/cli
    vue create frontend (rodar comando na pasta app)
