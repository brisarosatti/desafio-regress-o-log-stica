# Desafio Regressão Logística

## Elaborado por Marcus Oliveira da Silva

Segundo desafio do Bootcamp de Data Science and Machine Learnin da Tera. 

Neste desafio, vamos resolver um caso de preço de imóveis. Este desafio foi construído em parceria entre Tera e o QuintoAndar, onde o objetivo é simular um projeto de Machine Learning com características semelhantes ao que acontece no dia-a-dia da empresa.

Imagine-se na seguinte situação: A área de marketing da QuintoAndar quer montar uma calculadora de preço como esta [aqui](https://mkt.quintoandar.com.br/quanto-cobrar-de-aluguel/), e neste projeto, analistas e corretores de negócios também querem entender as principais variáveis e características chave que influenciam o valor de venda do imóvel (por exemplo, quantificar o impacto do aumento da área do imóvel no preço, ou quantificar o impacto de ter uma piscina, ou não, no preço). Você é o cientista de dados que vai agir para resolver este caso.

## Base de dados
[Base de dados](https://drive.google.com/file/d/1THulRo680Wqf5MPjMvfNQ1ouhCeMvQaX/view?usp=sharing])

[Dicionário de dados](https://drive.google.com/file/d/1B3AJBLhDSyNghSVrVnCIr0WudSwQqxBl/view?usp=sharing])

## Roteiro para o desafio:

 ### **1) Análise exploratória**

Você pode tentar o seguinte:

- Verificar a distribuição da variável de interesse (valor de venda)

- Contar o número de valores faltantes

- Verificar a matriz de correlação entre as features contínuas

- Scatterplots são úteis para visualizar duas variáveis contínuas

- Plotar a distribuição do valor de venda (histogramas ou boxplots) para as diferentes variáveis - categóricas

- Ao final, escreva um pouco sobre o que você conseguiu entender, extrapolar e interpretar a partir da análise exploratória

### **2) Pré-Preprocessamento, limpeza dos dados, construção de features**

Você pode tentar o seguinte:

- Dropar colunas(features) com muitos valores faltantes

- Buscar algum erro de preenchimento no dataset

- Tente criar features (Exemplo: dividir o número de quartos pela área, elevar a área ao quadrado)

- Não remova linhas com valores faltantes, já que isso pode modificar a distribuição do dataset de validação

**Objetivo 1: interpretabilidade usando uma regressão linear**

**Objetivo 2: poder preditivo, regressão via random forest**

A ideia dessa segunda parte é treinar um modelo mais robusto visando o poder preditivo e a obtenção de um modelo para uso em produção (uso real em uma aplicação web)
