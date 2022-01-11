

# Exercício
### Desenvolva o Diagrama Entidade-Relacionamento para as seguintes situações:

> Continuação da aula 5

2. Um diretor dirige no máximo um departamento. Um
departamento tem no máximo um diretor

![image](https://user-images.githubusercontent.com/93041258/149007524-efa8da88-57d8-430e-87b7-4b2d021308b4.png)

3. Um autor escreve vários livros. Um livro pode ser
escrito por vários autores.

![image](https://user-images.githubusercontent.com/93041258/149009057-dd83d747-7edc-4f4e-966d-6983b8f97988.png)

4. Uma equipe é composta por vários jogadores. Um
jogador joga apenas em uma equipe.

![image](https://user-images.githubusercontent.com/93041258/149009419-c02bfad0-396c-44c1-afc8-1934f39d13ac.png)


5. Um cliente realiza várias encomendas. Uma
encomenda diz respeito apenas a um cliente.

![image](https://user-images.githubusercontent.com/93041258/149010248-075a8822-d3c3-49e9-a260-5a731aece76f.png)


## Normalização

### Aplicar as Formas Normais cabíveis, nas questões abaixo. Você deve transformar os esquemas abaixo em conjuntos de esquemas que estejam na 2NF, 3NF e, justificar sua normalização de acordo com suas dependências funcionais.

1. Empregado (Número Empregado, Nome do Empregado, Número do Departamento, Nome do Departamento, Número do Gerente, Nome do Gerente, Número do Projeto, Nome do Projeto, Data de Início do Projeto, Número de horas trabalhadas no projeto, valor-hora do Projeto).
2. OrdemCompra (codOrdem, dtEmissão, codFornecedor, nomeFornecedor, endereçoFornecedor, codMaterial (n vezes), descriçãoMaterial (n vezes), qtComprada (n vezes), valorUnitário (n vezes), valorTotalItem (n vezes), valorTotalOrdem).
3. Tabela de Notas Fiscais (NumNF, Série, Data emissão, CodCliente, NomeCliente, EndereçoCliente, CGC cliente, Código Mercadoria, Descrição Mercadoria, Quantidade vendida, Preço de venda, Total da venda da Mercadoria e Total Geral da Nota).Cada nota pode ter mais de uma mercadoria. 
