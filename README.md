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

Para se testar a api e os methods (GET,POST,PUT,DELETE), foi criado uma documentação swagger.json, para que seja possível testes e validação de API.
Lá se encontra essa seguinte interface:


```sh
make install
npm test
```


## Contato

Lucas de Souza Duarte – lucasduarte.2009@hotmail.com

GitHub - (https://github.com/duartegit)
