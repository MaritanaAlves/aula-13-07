---
marp: true
theme: default
paginate: skip

style: |
  section {
    color: 
    font-family: "Montserrat", sans-serif;
    background-color: #fff;
  }
---

## Vanessa

![w:300 bg left](./images/vanessa.png)

Aluna da Turma SouDevMulheres

---

## Maritana Alves

![w:300 bg left](./images/mari.png)

Monitora na Digital College
Estagiária na Softlog
Linkedin: MaritanaAlves
GitHub: MaritanaAlves

---

# Objetivos

---

# Introdução ao HTML

## HTML (hypertext Markup Language)

É a linguagem de marcação padrão para criação de páginas web. Ele é essencial para estruturar e organizar o conteúdo das páginas que visitamos diariamente na internet.

<div align="center">

![w:600 center](./images/o-que-e-HTML.png)

</div>

<!--O HTML desempenha um papel fundamental no desenvolvimento web, permitindo que criemos, links, títulos, parágrafos, imagens e vários outros elementos que compõem as páginas web. Ele trabalha em conjunto com o CSS para definir a aparência desses elementos e com o JavaScript para adicionar interatividade e funcionalidades às páginas. -->

<!--Mostrar um site funcionando, acessar: https://digitalcollege.com.br/-->

---

# Estrutura básica do HTML

```C
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="utf-8">
    <title>Primeiro Projeto</title>
  </head>
  <body>
    <p>Olá Mundo!</p>
  </body>
</html>
```

<!--
- <!DOCTYPE HTML> Essa declaração informa ao navegador que o documento está escrito em HTM5, a versão mais recente e amplamente usada do HTML.
Na versão anterior do HTML, a declaração do Doctype era mais extensa e difícil de decorar, havendo a necessidade de referenciar para o navegador o arquivo DTD com as definições daquela especificação.
- <html lang="pt=br"> É a tag principal, que comporta todos os outros elementos filhos, é nessa tag que declaramos o idioma principal do documento, através do atributo lang
- <head> providencia informações gerais (metadados) sobre o documento, incluindo seu título e links para scripts e folhas de estilos. UTF-8, o padrão de codificação mais utilizado. <title> Título mostrado na aba da página.
- <body> É onde fica todo o conteúdo visível da página . Aqui é onde incluímos cabeçalhos, parágrafos, imagens, links e todos os outros elementos que queremos que os visitantes vejam na página.
-->

---

# Tags < HTML >

![w:8000 center](./images/mdn_anatomia_de_um_elemento_html.png)

<!--
A anatomia de um elemento HTML é formada pela tag de abertura, tag de fechamento, o atributo e valor do atributo, e o conteúdo que será exibido.
-->

---

#
