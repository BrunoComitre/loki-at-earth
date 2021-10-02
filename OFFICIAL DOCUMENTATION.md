# Nome do Grupo: Loki at Earth

## Nome do Aplicativo: Anhanga 

Anhanga é descrito como "gênio da floresta protetor da fauna e da flora na mitologia tupi", que "[...] não devora nem mata. Vinga os animais vitimados pela insaciabilidade dos caçadores".

Há descrições de que assume a forma de um veado branco com olhos de fogo e é o protetor da caça nas florestas, protegendo os animais contra os caçadores, sobretudo fêmeas com filhotes. Quando a caça conseguia fugir, os indígenas diziam que Anhangá a havia protegido e ajudado a escapar.~~~~

## Titulo do Projeto: 

Ciencia cidada para identificaçao de queimadas

## Resumo de Alto Nivel:

Os sistemas de monitoramento orbital de queimadas e incêndios são baseados no uso de imagens de baixa resolução espacial. Sendo assim, as queimadas cuja extensão é muito inferior à resolução espacial do sensor podem não ser identificadas. É  caso, por exemplo, de queimadas que acontecem no perímetro urbanos dos municípios e que são muito frequentes no período de estiagem.
Este projeto tem como objetivo, desenvolver um sistema que permita que qualquer cidadão possa fazer o registro de uma queimada (citizens as sensors), fornecendo uma foto com geotag (localização da foto).
Os dados de coordenadas espaciais da queimada são enviados para as instituições responsáveis pelo combate e autuação. Além disso, esses dados de ciência cidadã são úteis para validação (verificação de erros de omissão e de comissão) de produtos de monitoramentos de queimadas (área queimada e focos).
Outra funcionalidade do sistema é enviar alertas de queimadas e incêndios que estão ocorrendo nas proximidades (até 2 km) de uma determinada localização, como residência de interessados em receber o alerta, aeroportos, áreas protegidas (unidades de conservação e terras indígenas) linhas de tranmissão de energia e outros.
O sistema deve consumir os seguintes dados:
- Produto MYD09Q1 (Reflectância de superfície, composição de 8 dias, com resolução de 250 m)para visualização da superfície terrestre, considerando o melhor pixel dos últimos 8 dias
- Produto MYD09GQ (Reflectância de superfície, diário, com resolução de 250 m) para visualização da superfície terrestre diária (com possibilidade de cobertura de nuvens e ausência de imagens)
- Produto MYD14A1.006 (Anomalias térmicas e fogo diário, com resolução de 1 km) para visualização da localização de queimadas
- Produto MYD04_L2 (Aerossol, 5 minutos, com resolução de 10 km) para visualização de plumas de fumaça
- Focos de queimadas ocorridas nas últimas 2 horas (todos os satélites) disponibilizados pelo Projeto Queimadas do INPE para visualizar as coordenadas de queimadas e incêndios detectados por outros satélites além do MODIS/Aqua
- OpenStreetMap (OSM), que é um projeto de mapeamento colaborativo para facilitar a buscar de uma determinada localização

Na Mitologia Nórdica, Loki é o deus do fogo. O nome do grupo é um trocadilho para a expressão "Look at" com o nome de Loki, remetendo à frase "Olhe para a Terra".

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
