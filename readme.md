# Desafio Flask para criar um web app com IA

## Bootcamp Backend Python e Django 2024.1

## Aluna: Clarice Sofia Henrique Soares

### Criação e Ativação do ambiente (Windows)

1. Crie o ambiente virtual
```bash
python -m venv venv
```
2. Ative o ambiente virtual
```bash
./venv/scripts/activate
```
3. Crie um arquivo chamado **requirements.txt**. Dentro dele coloque o texto abaixo:

```text
flask
python-dotenv
requests
```
4. Salve o arquivo e faça a instalação das dependências

```bash
pip install -r requirements.txt
```
5. Você deve possuir uma conta Azure e criar um arquivo chamado **.env** e inserir as seguintes informações:
```
KEY= sua_chave
ENDPOINT= endpoint
LOCATION= sua_localização
```