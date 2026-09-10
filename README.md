# Atividade POO - Velho Steve (Java)

Repositório com a atividade da aula de POO (Classes e Objetos) do Geração Caldeira.

A ideia do exercício foi pegar o código antigo do Velho Steve (que era procedural) e refatorar usando Orientação a Objetos pra criar, usar e reparar as picaretas.

## O que foi feito no código:

* **Classe Picareta:** molde da picareta com os atributos privados (`material`, `durabilidade`, `forca`).
* **Construtor:** pra criar a picareta com os valores já definidos.
* **Getters:** pra conseguir ler as informações de fora da classe.
* **Métodos:** 
  * `minerar()`: diminui a durabilidade conforme a quantidade de blocos minerados.
  * `reparar()`: recupera a durabilidade da picareta.
  * `toString()`: pra formatar a exibição da picareta no terminal.
* **Classe Main (`OldStevePOO`):** cria as instâncias das picaretas com o `new` e testa as ações de minerar e reparar.
