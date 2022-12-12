# Fundamentos da programação
Aulas iniciais de programação na Rocketseat.

## O que é programação?
```markdown

Programação nada mais é do que ensinar o computador
```
---
## Ensinar o computador

- Algoritmos

  Sequência de passos, conjunto de regras

- Lógica de programação

  Maneira de pensar

- Sintaxe

  Maneira correta de escrever


## Front-end e Back-end

```markdown

## É uma comunicação

Imagina uma farmácia onde você vai pedir um remédio para o atendimento

---
## Cliente x Servidor

- Cliente

  Navegador (browser)

- Servidor

  Computador em algum lugar do mundo que tem os códigos

- Troca de dados

  Cliente faz o pedido e Servidor escuta e responde ao pedido.

- Cliente é o front-end, servidor é o back-end

---
## Tecnologias Front-end

- HTML

  Linguagem de marcação de texto para estrutura os textos, criar links, imagens, etc...

- CSS

  Linguagem de estilo para deixar o HTML bonito

- JavaScript

  Linguagem de programação que funciona no Navegador

---
## Tecnologias Back-end

- NodeJS

  Rodar o JavaScript no computador

- SQL

  Banco de dados para proteger os dados do seu programa
```

## HTML

```markdown
## O que é HTML?

- Estruturar textos, criar links, imagens, vídeo, etc ...

- Hypertext Markup Language

  Linguagem de marcação de texto

---

## Hypertext

- Hiper texto

- Texto que contém links

---

## Markup

- Marcação do texto

- Elemento HTML ou tag

  Existem inúmeras tags e cada uma deles irá servir para um determinado propósito. Ex.: imagem, texto grande, link, parágrafo, etc...

---

## Sintaxe de uma tag

sinal de menor, nome da tag, sinal de maior, conteúdo, sinal de menor, barra, nome da tag, sinal de maior

```html
  <p>conteúdo</p>
```

---

## Atributos

- Adicionam informações e configurações à uma tag

- Sintaxe

  nome do atributo, sinal de igual, aspas duplas (abre), valor, aspas duplas (fecha)

```html
  <a href="#">link</a>
```

---

## Comentários

- Ignorar linhas de código

- Adicionar informação

- Somente acessível por quem coda

```html
  <!-- Aqui vem um comentário -->
  <!--
  Várias linhas de código 
  poderão ser ignoradas 
  ao utilizar comentário
  -->
```

## O que é CSS?
```
- Apresentação visual para o cliente

- Estilos para o HTML

- Cascading Style Sheets

Folha de Estilo em Cascata

---
```
## Declaration
```
- Declaração

  Pedaço de código que irá ditar as propriedades e valores a serem 
aplicadas a um elemento HTML

- Sintaxe

  Seletor, chave (abre), propriedade, dois pontos, valor, ponto vírgula, 
chave (fecha)

```css
  body {
    background: red;
  }
```

---

## Comentários

- Ignorar parte do código

- Adicionar informações que serão visíveis somente pra quem coda

```css
/* Essa linha será ignorada */

/*
Poderemos ignorar várias 
linhas de código
dessa forma
*/
```

---

## Cascading

- Cascata

  Quando há 2 (ou mais) declarações a última será mais relevante

```css
  body {
    background: red;
  }

  body {
    background: blue;
  }
```

---

## Specificity

Especificidade: Cada seletor tem um peso e a soma dos pesos, será levada 
em conta para que determinada declaração seja mais específica


```css
  #id {
    /* peso 100 */
  }

  .class {
    /* peso 10 */
  }

  element {
    /* peso 1 */
  }
```

> A cascata perde prioridade e é priorizada a especificidade da declaração

---

## Box Model

- Tudo são caixas

  Todos os elementos HTML serão considerados uma caixa, assim como uma 
caixa de papelão

- Caixas possuem determinadas propriedades, veja

  Conteúdo, Largura, Altura, Borda, Preenchimento (espaço interno), 
Espaçamento (espaço externo)

---

