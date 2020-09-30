# Design patterns Utilizados
## Strategy
No projeto foi utilizado primeiramente o padrão "Strategy" no qual foi possível retirar vários if para realizar o cálculo dos novos impostos, o novo imposto pode ser calculado sem alterar o código funcionando para qualquer novo imposto criado. <br> (Henriquehlr)

## Padrão Chain of Responsibility
Obtemos varios descontos aplicados em um cenario especifico e se o cenario não bater irá passar para o proximo. <br> (jfsantos011)

## Template Method
Veja que ambas as classes de impostos só implementam as partes "que faltam" do algoritmo! A classe TemplateDeImpostoCondicional possui um método que funciona como um template, ou seja, um molde, para as classes filhas. Daí o nome do padrão de projeto: Template Method.
Veja que o uso do padrão evitou a repetição de código, e ainda facilitou a implementação das diferentes variações do algoritmo. <br> (Henriquehlr e jfsantos011)

## Autores
Henriquehlr -> Henrique Lucas Rodrigues <br>
jfsantos011 -> João Fernando dos Santos.
