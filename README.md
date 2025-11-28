# Técnicas de NLP (Processamento de Linguagem Natural) Aplicadas em Projeto de Ciência de Dados e Sistema de Recomendação de Conteúdo

## Aluno
- Nome: Kaike Mendes Costa — RA: 2225202786
| Turma: 41 - SA | Curso: Ciência da Computação | Período: Noturno | Ano: 2025

## Problema
Com o ininterrupto crescimento do catálogo de serviços de streamings ao redor do mundo, é de suma importância que sejamos capazes de, além de acompanhar nossas séries e filmes favoritos, também ter o conhecimento para buscarmos conteúdos semelhantes que despertem nossa atenção quando estamos em um momento de lazer. Este projeto de ciência de dados visa a criação de um sistema básico de recomendação de conteúdo baseado em um dataset contendo informações sobre filmes e séries da Netflix através de técnicas de inteligência artificial.

## Abordagem de IA
A principal **técnica** de inteligência artificial utilizada na criação deste projeto é o **TF-IDF (Term Frequency-Inverse Document Frequency)**, uma abordagem bastante conhecida no campo do Processamento de Linguagem Natural (NLP) por conta da sua capacidade de vetorizar, ou transformar, textos em matrizes numéricas. Em relação à **métrica**, foi utilizada a **cosine_similarity**, que é responsável por medir o quão semelhantes dois vetores (ou matrizes) conseguem ser. Estas duas ferramentas são adequadas para o desenvolvimento deste projeto pois são relativamente fáceis de se manipular e funcionam perfeitamente juntas.

## Dados
Os dados utilizados na criação deste projeto pertencem a um [dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows) disponibilizado no site Kaggle pelo usuário [Shivam Bansal](https://www.kaggle.com/shivamb).

## Como reproduzir

Aqui está um guia de como executar este projeto:

### 1. **Acessar o Google Colab**

Para realizar esta etapa, é necessário que o usuário possua apenas uma conta no Google para conseguir acessar o projeto e clicar no link a seguir para abrir o Google Colaboratory:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1yLyi87AuCKZyIierof9zM3uD0Q-pErAV)

Assim que o usuário tiver criado ou logado em sua conta Google e acessado o link, o Google Colab deverá aparecer assim:

<img width="1365" height="584" alt="image" src="https://github.com/user-attachments/assets/b8f04048-7aa9-47a2-b127-e957e58fd527" />

### 2. **Executar as células**

Em seguida, é necessário executar as células do projeto. Para isto, o usuário, caso queira visualizar a execução de cada uma separadamente, precisa selecionar a célula e apertar as teclas Ctrl + Enter no teclado, ou, também, clicar no botão ao lado desta célula.

<img width="270" height="176" alt="image" src="https://github.com/user-attachments/assets/aee42b28-e2c2-45bf-a150-55178e52f2bb" />

Se preferir executar tudo de uma vez, o usuário pode clicar na opção "Executar tudo" que está localizada na barra superior.

<img width="381" height="39" alt="image" src="https://github.com/user-attachments/assets/990ce30b-8fc5-4646-9d20-858ef17cb987" />

### 3. **IA**

Após executar todas as células, chegaremos na 4ª sessão do nosso projeto que é a **Criação do Sistema de Recomendação de Conteúdo**. Nesta fase do projeto, aparecerá uma caixa de texto para o usuário onde ele pode digitar o título que ele deseja basear as recomendações. Em seguida, aparecerá outro campo para o usuário digitar, que é o do número de recomendações que ele deseja receber. Após digitar nestes dois campos, a função do projeto rodará e irá recomendar séries ou filmes semelhantes àquele digitado.

<img width="895" height="80" alt="image" src="https://github.com/user-attachments/assets/9a3c0ff1-72a9-438a-b500-84b57e09fd5d" />

## Resultados do Projeto

Primeiramente, temos a Avaliação de Distribuição de Similaridades:

<img width="551" height="451" alt="grafico_distribuicao_similaridades" src="https://github.com/user-attachments/assets/15fb665d-c197-4a9f-b4f6-dc8d19c4291d" />

E, em seguida, o Heatmap de Similaridades:

<img width="570" height="507" alt="grafico_heatmap_similaridades" src="https://github.com/user-attachments/assets/3f29d621-92e1-4de2-8e80-7cb927d96c6c" />

