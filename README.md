# Desafio Machine Learning 

  

Este repositório contém um dataset com 7121 formulas de medicamentos manipulados.  

  

O objetivo do teste é prever o valor da coluna "correto" com menor erro possível a partir das outras informações do dataset. 

  

dos 7121 pontos de dados, podem usar no máximo os primeiros 5121 dados do dataset para prever os últimos 2000 

  

está livre o uso de qualquer ferramenta de aprendizado de máquina, só precisam disponibilizar o código de forma que consigamos reproduzir o que foi feito, pode ser em um repositório ou notebook no colab research. 

  

# Colunas: 

  

## descricao  

  

descrição da formula, seguindo o padrão: 

  

    qtd unidade_volume | insumos separados por ';' 

     

    a unidade de volume vai ser sempre CAP no dataset 

  

    os insumos vão ter o padrão: 

  

        nome do insumo qtdunidade;  

        ex: zinco quelado 20mg; 

  

## criado 

  

data de criação da formula 

  

## qtdInsumos 

quantidade de insumos da formula 

  

## calculado 

preço pré-calculado da formula

  

## correto 

preço correto da formula, o objetivo é prever ele
