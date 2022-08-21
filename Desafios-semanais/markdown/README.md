## Visão geral

Quase todos os aplicativos Markdown suportam a sintaxe básica descrita no documento original de design do Markdown. Existem pequenas variações e discrepâncias entre os processadores Markdown - essas são anotadas em linha sempre que possível.

## Títulos

Para criar um título, adicione sinais numéricos ( #) na frente de uma palavra ou frase. O número de sinais numéricos que você usa deve corresponder ao nível do título. Por exemplo, para criar um nível de título três `( <h3>)`, use três sinais numéricos (por exemplo, ### My Header).  

| Markdown            | HTML                      | Saída renderizada         |
| ------------------- | ------------------------- | ------------------------- |
| `# Título nível 1`  | `<h1>Título nível 1</h1>` | <h1>Título nível 1</h1>   |
| `# Título nível 2`  | `<h2>Título nível 1</h2>` | <h2>Título nível 1</h2>   |
| `# Título nível 3`  | `<h3>Título nível 1</h3>` | <h3>Título nível 1</h3>   |
| `# Título nível 4`  | `<h4>Título nível 1</h4>` | <h4>Título nível 1</h4>   |
| `# Título nível 5`  | `<h5>Título nível 1</h5>` | <h5>Título nível 1</h5>   |
| `# Título nível 6`  | `<h6>Título nível 1</h6>` | <h6>Título nível 1</h6>   |

### Práticas recomendadas de título

Os aplicativos de remarcação não concordam em como lidar com um espaço ausente entre os sinais numéricos ( #) e o nome do título. Para compatibilidade, sempre coloque um espaço entre os sinais numéricos e o nome do título.

## Parágrafos

Para criar parágrafos, use uma linha em branco para separar uma ou mais linhas de texto.  

### Práticas recomendadas do parágrafo  

## Quebras de linha  

Para criar uma quebra de linha ou uma nova linha ( <br>), termine uma linha com dois ou mais espaços e digite return.  

## Ênfase  

Você pode adicionar ênfase colocando o texto em negrito ou itálico.  

| Markdown - negrito                  | Saída renderizada                  |
| ----------------------------------- | ---------------------------------- |
| `Exemplo de texto em **negrito**.`  | Exemplo de texto em **negrito**.   |
| `Exemplo **de** texto em negrito.`  | Exemplo **de** texto em negrito.   |

| Markdown - itálico                   | Saída renderizada                   |
| ------------------------------------ | ----------------------------------- |
| `Exemplo de texto em *negrito*.`     | Exemplo de texto em *itálico*.      |
| `Exemplo *de* texto em negrito.`     | Exemplo *de* texto em itálico.      |

| Markdown - negrito + itálico        | Saída renderizada                  |
| ----------------------------------- | ---------------------------------- |
| `Exemplo de texto em ***negrito***.`| Exemplo de texto em ***itálico***. |
| `Exemplo ***de*** texto em negrito.`| Exemplo ***de*** texto em itálico. |

### Citações em bloco  

Para criar uma citação em bloco, adicione um `>` na frente de um parágrafo.

```
> Exemplo de texto com citação em bloco
```

A saída renderizada fica assim:  

> Exemplo de texto com citação em bloco

### Citações de bloco aninhadas  

Blocos podem ser aninhados. Adicione um `>>` na frente do parágrafo que você deseja aninhar.  

```
> Exemplo de texto com citação em bloco
>
>> Exemplo de texto com citação de bloco aninhada
```

A saída renderizada fica assim:  

> Exemplo de texto com citação em bloco
>
>> Exemplo de texto com citação de bloco aninhada

### Citações em bloco com outros elementos  

Blocos podem conter outros elementos formatados de Markdown. Nem todos os elementos podem ser usados, você precisará experimentar para ver quais funcionam.  

```
> ### Exemplo de título em bloco
>
> - Exemplo de texto com citação em lista não ordenada.
> - Exemplo de texto com citação em lista não ordenada.
> 
> Exemplo de texto em **negrito** e *itálico* em citação de bloco.
```

A saída renderizada fica assim:  

> ### Exemplo de título em bloco
>
> - Exemplo de texto com citação em lista não ordenada.
> - Exemplo de texto com citação em lista não ordenada.
> 
> Exemplo de texto em **negrito** e *itálico* em citação de bloco.


Fonte:  
https://www.markdownguide.org/getting-started/  
https://www.markdownguide.org/basic-syntax/  
https://www.markdownguide.org/extended-syntax/  
https://gist.github.com/rxaviers/7360908  


