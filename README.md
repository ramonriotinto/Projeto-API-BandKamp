<h1> API BAND KAMP</h1>

## **1. Projeto**

A API permite criar e gerenciar álbuns musicais, bem como adicionar e gerenciar as músicas associadas a cada álbum. Através da API, é possível criar um novo álbum com informações como título e ano de lançamento. Além disso, é possível adicionar músicas a um álbum existente, informando detalhes como título, duração. A API também permite buscar, criar e listar álbuns e músicas, bem como criar, listar, atualizar, deletar e fazer login com usuário.

## <strong>ER Diagram: </strong>

[DIAGRAMA_BAND_KAMP.pdf](https://github.com/AmandaIsMe-alt/Biblioteka/files/11413212/DIAGRAMA_BAND_KAMP.pdf)

Principais tecnologias utilizadas:

-   Python
-   Django

**Base URL: http://127.0.0.1:8000/**

**Documentação da API:**

http://127.0.0.1:8000/api/docs/redoc/

http://127.0.0.1:8000/api/docs/swagger-ui/

## **Dev**

> -   [Igor Ramon](https://www.linkedin.com/in/igor-ramon-rio-tinto/)

## **2. Inicializando projeto:**

### Digite os comandos no terminal em sequência:

```json
  Criar Ambiente Venv : python -m venv venv

  Ativar Ambiente Venv no Windows : source venv/Scripts/activate

  Ativar Ambiente Venv no Linux : source venv/bin/activate

  Instalar Pacotes : pip install -r requirements.txt

  Criar arquivo chamado .env, copiando e colando o arquivo .env.example, depois renomeando para .env e preencher informações sensíveis do arquivo.

  Gerar Migrações : python manage.py migrate

  Iniciar Servidor : python manage.py runserver
```
