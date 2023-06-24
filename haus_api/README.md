# HAUS - EVERTON VASZELEWSKI BACKEND - BANCO DE DADOS
# MVP SPRINT 1 - Pós-Graduação em Engenharia de Software

Backend do projeto HAUS: Um Sistema web de gerenciamento e catalogar coleções de objetos de Música


---
## Como executar 

Requisitos:
- Realizar a instalação das libs python listadas no `requirements.txt`.
- É recomendado o uso de ambientes virtuais do tipo [virtualenv](https://virtualenv.pypa.io/en/latest/installation.html).


1 - Após clonar o repositório, é necessário ir ao diretório raiz, pelo terminal, para poder executar os comandos descritos abaixo:

cd evertonMvp\haus_api

2 - Instalar Virtualenv
```
$ pip install VirtualEnv
```

3 - Criar Virtualenv
```
$ Virtualenv venv
```

4 - Ativar venv
```
$ venv\scripts\activate
```

5 - Instalar libs python
```
(venv)$ pip install -r requirements.txt
```

6 - Instalar Greenlet
```
(venv)$ pip install greenlet
```

7 - Executar API:

```
(venv)$ flask run --host 0.0.0.0 --port 5000
```

Em caso de modificações no código enquanto a API estiver rodando, utilizar o parâmetro reload, que reiniciará o servidor
automaticamente após uma mudança no código fonte. 

```
(env)$ flask run --host 0.0.0.0 --port 5000 --reload
```

Após seguir todos os passos, abrir o link abaixo no bavegador para verificar o status da API em execução
- [http://localhost:5000/#/](http://localhost:5000/#/)

Link para Documentação:
- [http://127.0.0.1:5000/openapi/] (http://127.0.0.1:5000/openapi/)
