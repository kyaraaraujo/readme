## README

[Por que se dedicar ao README?](#por-que-se-dedicar-ao-readme)

[A inspiração](#a-inspiração)

[O que escrever no README ?](#o-que-escrever-no-readme)

[Ferramentas](#ferramentas)

[Possibilidades](#possibilidades)

- [Títulos](#títulos)
- [Índices](#índices)
- [Links](#links)
- [Tabelas](#tabelas)
- [Inserir imagem](#inserir-imagem)
- [Centralizar conteúdo](#centralizar-conteúdo)
- [Linha separadora](#linha-separadora)
- [Itens](#itens)

[Autora](#autora)

[Referências](#referências)



---



## Por que se dedicar ao README

O README serve como um "cartão de visitas", é importante para que outras pessoas possam entender do que se trata o projeto, essas pessoas podem ser recrutadores e desenvolvedores. Eu acrescento que **o README também é importante para você**, pois após um tempo sem rever o projeto é comum esquecer certas coisas, então tenha o README como um resumo do que se trata o seu projeto para que seu eu do futuro possa relembrar (assim espero :upside_down_face: rsrs).



## A inspiração

A inspiração de usar template para o README veio do [Meet Up da Dev Girls ](https://github.com/devgirlsbr/meetups/blob/main/julho-2021-comunidade/TALK2.md) onde foi apresentado a importância do README e  exemplo de template, a partir dele adaptei o meu. O [repositório do template das desenvolvedoras Clarissa e Eline se encontra aqui](https://github.com/devgirlsbr/templates/tree/main/readme-101).



## O que escrever no README?

Isso é bem flexível, mas seria interessante manter um certo padrão entre seus arquivos README. [Nesse template](https://github.com/devgirlsbr/templates/blob/main/readme-101/README_TEMPLATE.md) apresenta alguns exemplos de seções que podem ser inseridas, a partir delas adaptei ao que necessitava e caso necessário posso adaptar novamente.



## Ferramentas

Pode ser usado uma IDE que possua a visualização da extensão .md (markdown), como IntelliJ, VS Code, ou até leitores/editores específicos como o Typora.



## Possibilidades

No arquivo .md pode ser usado o markdown e até mesmo HTML, pode ser usado links de [badges](https://shields.io/category/license), imagens, tabelas, etc. Há muitas coisas que se pode fazer com markdown, porém aqui [explicarei o que utilizei nesse template](https://github.com/kyaraaraujo/array-js), é possível visualizar o código através de alguma das etapas:

- baixar o arquivo e abrir em algum editor de texto/IDE

- pelo github: clica no arquivo README.md e então no botão `raw` ao lado direito

- à URL do README insere o endereço `raw.githubusercontent.com` antes do usuário, exemplo:

   https://raw.githubusercontent.com/kyaraaraujo/array-js/main/README.md



### Títulos

Assim como no HTML, pode ser usado títulos, enquanto no HTML se usa as tags `<h1>, <h2>, <h3>,...<h6>` no markdown se usa quantidade de `#` para determinar o nível do título (quanto mais `#` menor nível e menor tamanho default da fonte, pode ser usado diferentes níveis para gerar seções e subseções).

Exemplo:

```markdown
#### Título nível 4 
##### Título nível 5 
###### Título nível 6
```



### Índices

Para criar índices no markdown se usa a sintaxe `[título](#seção)` , a seção deve estar escrita exatamente como o título da seção, se houver espaços será necessário colocar - , exemplos:

```markdown
[Índice](#índice)
[Este possui espaços](#este-possui-espaços)
[Pode ter mesmo nome](#pode-ter-mesmo-nome)

## Índice
[...alguma informação ...]

## Este possui espaços
[...alguma informação ...]

## Pode ter mesmo nome
[...alguma informação ...]
```



### Links

Uma sintaxe parecida ao de índices, porém ao invés de `#seção` se informa a URL: 

`[texto](https://www.url.com.br)`

```markdown
[Clique para visualizar o perfil](https://github.com/kyaraaraujo)
```



### Tabelas

Em markdown se uitliza `|` para definir a tabela e `---`  e `:`para alinhar o texto

```markdown
| Coluna 1  |   Coluna 2  | Coluna 3 |
|   ---:    |    :---:    |   ---    |
|à direita  | centralizado| à esquerda (default) |
```

Em HTML, para as tags de tabela precisa indicar abertura `<table>` e fechamento `</table>` 

```html
<table>
    <tr align="center">
        <th>Coluna 1</th>
        <th>Coluna 2</th>
    </tr>
    <tr align="center">
        <td>conteúdo 1</td>
        <td>conteúdo 2</td>
    </tr>
</table>
```

`<tr>` = table row (linha)

`<th>` = table head (título/coluna)

`<td>` = table data (conteúdo da linha)

`align="center"` = centralizar o texto que estiver dentro da linha `<tr>`



### Inserir imagem

Em markdown pode haver título alternativo, pode ser usado caminho do diretório ou URL, pode inserir título opcional (que aparece ao deixar o mouse parado sobre a imagem). 

```markdown
![Texto Alternativo](/caminho/da/img.jpg)
![Texto Alternativo](/caminho/da/img.jpg "Título Opcional")
![](/caminho/da/img.jpg)

```

Em HTML se usa a tag `<img>` e pode ser usado atributos  `height` e `width` para redimensionar a imagem e `alt` para texto alternativo.

```html
<img src="https://github.com/kyaraaraujo.png" height="40" width="40" alt="Foto de Kyara Araújo"/>
```

O texto alternativo serve para caso a imagem não seja carregada corretamente e também para fins de acessibilidade.



### Centralizar conteúdo 

Caso deseje centralizar vários blocos de conteúdo, pode envolver em uma `<div>` (no Typora não visualiza corretamente)

Exemplo:

```markdown
<div align="center">

    <img src="https://github.com/kyaraaraujo.png" height="40" width="40" alt="Kyara Araújo's photo"/>
    
    | Coluna 1 | Coluna 2 | 
	|   :---:  |   :---:  |  
	| conteúdo | conteúdo |
	
	Estamos centralizados
	
</div>
```



### Linha separadora

Serve para criar um linha horizontal para separar visualmente um conteúdo de outro, deve ser usado em uma linha sem conteúdo.

Em markdown `---`

```markdown
conteudo antes da linha.

---

abaixo da linha.
```



Em HTML `<hr>`

```html
conteudo antes da linha.

<hr>

abaixo da linha.
```



### Itens

Usando `-` é possível criar itens e subitens

```markdown
- item principal
	- item interno
		- item mais interno
```



## Autora

|        [Kyara Araújo](https://github.com/kyaraaraujo)        |
| :----------------------------------------------------------: |
| <img src="https://github.com/kyaraaraujo.png" height="80" width="80" alt="Foto de Kyara Araújo"/> |





## Referências

- [Meet Up - Dev Girls - Julho 2021 - template README](https://github.com/devgirlsbr/meetups/blob/main/julho-2021-comunidade/TALK2.md)
- [O que escrever no README](https://github.com/devgirlsbr/templates/blob/main/readme-101/README_TEMPLATE.md)
- [Typora - editor e leitor de markdown](https://typora.io/)
- [Referência markdown da Typora](https://support.typora.io/Markdown-Reference/)
- [Meu primeiro template](https://github.com/kyaraaraujo/array-js)
- [O que é README e porque ele é tão importante? (rocketseat.com.br)](https://blog.rocketseat.com.br/o-que-e-readme-e-porque-e-tao-importante/)
- [Básico HTML - tabela](https://www.w3schools.com/html/html_tables.asp)
- [Badges](https://shields.io/)
- [Sintaxe básica de escrita e formatação no GitHub](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)

---

:arrow_up_small: [Voltar ao início](#readme)

