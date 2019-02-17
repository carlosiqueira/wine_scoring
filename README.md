# Wine Scoring
Example of a algorithm that scores wines based on  given chemical characteristics...

## Teste passado para testar algumas habilidades em manipulação de dados e algoritmos.

###### Deixo claro que poderia ser uma analise mais completa e detalhada,  mas como foi um teste e teve de ser conciliado com outros compromissos para ser entregue foi feito o melhor que consegui dentro do tempo de entrega, aceito sugestões para melhorias

### Algumas observações importantes:

- O dataset dado possuia vinhos brancos e vermelhos, ao analisar o mercado, pode se concluir que é extremamente limitado esse nível de separação, cada uva e terroir tem caracteristicas desejadas diferentes
- Foi separado  ao menos o branco do vermelho e segui na analise apenas com os brancos, seria o mesmo raciocínio para o vermelho, depois pretendo clonar o arquivo e deixar tambem o dos vinhos vermelhos aqui

### Respostas desejadas pelo teste

O problema foi tratado como um problema de classificacao, ao fazer analises dentro do dataset deu para perceber que, possívelmente, o método de KNN seria uma boa opção para seguir.
Para ter a certeza de que havia um modelo razoavel em maos fiz uma classificacao aleatoria atravez de um  dummy classifier a fim  de comparar o  resultado final.
O resultado foi bem melhor que o dummy no fim do modelo, apesar, de conforme podemos observar no grafico com as amostras em dispersao, se confirmar que algumas notas sao mais dificeis de nao se misturarem entre si.

###### O arquivo se encontra comentado,  mas por favor, entrem em contato comigo para caso qualqer esclarecimento  seja necesário. Fico devendo uma  v2 com comparativo pelo  menos com um método de regressão e uma melhoria no de classificacao  atraves de  combinacao de metodos.
