# API REST em Python
> Este projeto é uma REST API que atende aos chamados HTTP, retorna um JSON com a Competição criada, a criar ou a ser encerrada.


De um a dois parágrafos sobre o que é seu projeto e o que ele faz

Esta RestAPI quer tornar o COR (Comitê Olímpico Radar), um evento benéfico para todos, captando as competições e resultados dos atletlas de forma rápida e eficiente. O benefício de utilizar a API, é que você não precisará ficar esperando a competição se encerrar
para ficar sabendo dos resultados, você poderá saber o resultado parcial também, para acompanhar um atleta, ou saber como anda uma competição.


## Instalação do Ambiente Virtual

OS X & Linux & Windows:

```sh
python -m venv radar
```

## Instalação das Dependências

OS X & Linux & Windows:

```sh
pip install -r requirements.txt
```

## Ativação do Ambiente Virtual

OS X & Linux & Windows PowerShell:

```sh
.\radar\Scripts\activate.sp1
```

Windows cmd:

```sh
.\radar\Scripts\activate.bat
```


## Exemplo de utilização da API

Comando HTTP para buscar todas as competições:

```sh
GET '../api/competicao';
```
Comando HTTP para buscar {x} competição:

```sh
GET '../api/competicao/{x}';
```


## Ambiente para Teste de methods

Para se testar a api e os methods (GET,POST,PUT,DELETE), foi criado uma documentação swagger.json, para que seja possível testes e validação de API, que pode ser acessado em:

```sh
'../api/doc';
```

Lá se encontra essa seguinte interface:

![interface](https://user-images.githubusercontent.com/50371525/139464835-5a44a803-ab00-4c28-9e9d-11f13e46b45d.jpg)

Assim pode-se testar a API da seguinte forma:

![POST_1](https://user-images.githubusercontent.com/50371525/139465546-e8501dc5-9e35-4bad-924d-8348ffc863eb.jpg)

Dê um click na ação desejada (GET,POST,PUT,DELETE), logo após clique no botão: "Try it out" e deverá abrir o método desejado com os VALORES EDITÁVEIS:

![POST_2](https://user-images.githubusercontent.com/50371525/139466245-0c9db316-ffb1-4c93-81a0-9a6ca78b3a0d.jpg)

Após fazer suas alterações, note que, o payload é requirido, ou seja, todos os atributos são obrigatórios(PS: CAMPO Enc é para saber se a competição está em andamento ou foi encerrada, 0 para em andamento, 1 para encerrada). E é só clicar em EXECUTE:

![POST_3](https://user-images.githubusercontent.com/50371525/139468415-14419510-136c-4fdb-9185-002ff0e73d35.jpg)


## Contato

Lucas de Souza Duarte – lucasduarte.2009@hotmail.com

GitHub - (https://github.com/duartegit)
