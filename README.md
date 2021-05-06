# Curso introdução a programação web direto ao ponto  
Introdução a progração web direto ao ponto com python e flask.  

## Roteiro
[Link do Roteiro](./course/README.md)

# Flask
Primeiro Site flask

## Virtual env
Criar virtual env
> % python3 -m venv foldername  
% source foldername/bin/activate  
% cd foldername  

## Rotas
mapeamento de rotas
parametros
> pip3 install flask gunicorn
```python
from flask import Flask
app= Flask(__name__)

@app.route('/')
def index():
  return "<h1>Welcome to CodingX</h1>"
```
## html
bootstrap
reuse

## Static
css
js
img

# Repositório git
Primeiro repositório git
Utilizando git

## Deploy
On heroku
> pip3 freeze > requirements.txt  
> web: gunicorn wsgi:app  

1. Criar um modelo simples de site
2. Adicionar funcionalidades
3. Criar contas
4. Adicionar funcionalidades


By Sham
