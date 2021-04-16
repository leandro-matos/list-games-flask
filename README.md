# list-games-flask

## Como rodar o projeto?

* Clone esse repositório.
* Crie um virtualenv com Python 3.
* Ative o virtualenv.
* Instale as dependências.
* Rode o jogoteca

```
git clone https://github.com/leandro-matos/list-games-flask.git
cd list-games-flask
virtualenv venv
.\venv\Scripts\activate
pip install -r requirements.txt
python3 jogoteca.py
```

```
docker pull leandromatpereira/list-games-flask:latest
docker run -d -p 5000:5000 leandromatpereira/list-games-flask
```

