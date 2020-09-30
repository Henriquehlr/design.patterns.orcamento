# design.patterns.orcamento

## Strategy
No projeto foi utilizado primeiramente o padrão "Strategy" no qual foi possível retirar varios if para realizar o calculo dos novos impostos, no qual o novo imposto pode ser
calculado sem alterar o codigo funcionando para qualquer novo imposto criado. (Henriquehlr)

## Padrão Chain of Responsibility
Obtemos varios descontos aplicados em um cenario especifico e se o cenario não bater irá passar para o proximo. (jfsantos011)

## Template Method
Veja que ambas as classes de impostos só implementam as partes "que faltam" do algoritmo! A classe TemplateDeImpostoCondicional possui um método que funciona como um template, ou seja, um molde, para as classes filhas. Daí o nome do padrão de projeto: Template Method.

Veja que o uso do padrão evitou a repetição de código, e ainda facilitou a implementação das diferentes variações do algoritmo. (Henriquehlr e jfsantos011)

## Autores
Henriquehlr -> Henrique Lucas Rodrigues
jfsantos011 -> João Fernando dos Santos.
