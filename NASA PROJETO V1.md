# Nome do Grupo: 



## Nome do Aplicativo: 



## Titulo do Projeto: 

Ciencia cidada para identificaçao de queimadas



## Resumo de Alto Nivel:

O projeto destina a identificacao de queimadas por meio de analise  de dados geoespaciais junto a dados do... que fornecem o meio para ciencia cidada onde as pessoas poderao incluir atividades relacionadas a incendio, e com base nas notificaoes alertar a populacao e os setores responsaveis para combate de queimadas



## Refencias Bibliográficas:



## Tags:

#fire, #application, #cienciacidada, #meansuring





# Desenvolvimento



## Aplicativo

- A aplicativo é responsavel por gerenciar usuarios e notifica-los

- Ele  enviara as informacoes ao backend, onde o backend ira tratar os dados, e caso haja evidencias de que as queimadas acontecam, ira ser disparado notificacoes aos usuarios



## Backend

A API do backend é reponsável pelo:

- gerenciamento de usuários e notificacoes
- realizar o tratamento dos dados enviados pelos usuarios e junto aos dados da predicao encontrar um valor para notificar outros usuarios
- codificada em python usando framework fastapi e/ou flask
- o backend será responsavel por gerar e armazenar o indice de confiabilidade do:
  - usuario
  - queimada
- será codificado em flutter
- possuira uma base de dados mongodb



## Predicao

- codificada em python usando a ferramenta kaggle
- usando duas bases de dados iniciais:
  - base 1
  - base 2

- responsavel pelo tratamento dos dados e da geracao do modelo a ser usado para predicao do backend

