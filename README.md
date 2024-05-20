![imagemHome](https://github.com/Giljared/recriando-wikipedia-moderna/assets/64940515/8d9e8fee-0ec6-4cb1-bdd2-77b18aaa463d)


<span align="center">

##  Recriando a Website/moderno Wikimedia com HTML e CSS 👋 
### Link: https://my-wikipedia-gil-silva.netlify.app/

</span>
# Recriando a Website/moderno Wikimedia com HTML e CSS
Introdução

## Neste tutorial, vamos criar uma versão simplificada da página inicial do site da Wikimedia usando HTML e CSS. O objetivo é demonstrar os conceitos básicos de estruturação e estilização de um site, sem focar em funcionalidades complexas.

## Pré-requisitos

## Para acompanhar este tutorial, você precisará de:

## Um editor de texto simples, como o Notepad++ ou o Sublime Text
Um navegador web, como o Chrome, Firefox ou Edge
Conhecimento básico de HTML e CSS
Etapas

## Crie um arquivo HTML
Comece criando um novo arquivo HTML e salvando-o com o nome index.html.

## Estrutura básica do HTML
Adicione o seguinte código HTML ao seu arquivo:

# HTML
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Wikimedia</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Wikimedia</h1>
  </header>

  <main>
    <section class="search-bar">
      <input type="text" placeholder="Pesquisar na Wikipédia">
      <button type="button">Pesquisar</button>
    </section>

    <section class="featured-articles">
      <h2>Artigos em destaque</h2>
      <ul>
        <li><a href="#">Artigo 1</a></li>
        <li><a href="#">Artigo 2</a></li>
        <li><a href="#">Artigo 3</a></li>
      </ul>
    </section>

    <section class="random-article">
      <h2>Artigo aleatório</h2>
      <p><a href="#">Clique aqui para um artigo aleatório</a></p>
    </section>
  </main>

  <footer>
    <p>&copy; Wikimedia Foundation/modern</p>
  </footer>
</body>
</html>
## Use code with caution.
content_copy
Este código define a estrutura básica da página, incluindo o cabeçalho, a seção principal com a barra de pesquisa, artigos em destaque e um artigo aleatório, e o rodapé.

## Estilização com CSS (sugestões básicas)
Crie um novo arquivo CSS chamado style.css e adicione o seguinte código:

# CSS
body {
  font-family: sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #f0f0f0;
  padding: 20px;
  text-align: center;
}

header h1 {
  font-size: 32px;
  margin: 0;
}

main {
  padding: 20px;
}

.search-bar {
  margin-bottom: 20px;
}

.search-bar input {
  width: 80%;
  padding: 10px;
  border: 1px solid #ccc;
}

.search-bar button {
  padding: 10px 20px;
  background-color: #4CAF50;
  color: white;
  border: none;
  cursor: pointer;
}

.featured-articles {
  margin-bottom: 20px;
}

.featured-articles h2 {
  font-size: 24px;
  margin-bottom: 10px;
}

.featured-articles ul {
  list-style: none;
  padding: 0;
}

.featured-articles li {
  margin-bottom: 10px;
}

.featured-articles a {
  text-decoration: none;
  color: #333;
}

.random-article {
  text-align: center;
}

.random-article a {
  font-size: 18px;
  color: #007bff;
}

footer {
  background-color: #f0f0f0;
  padding: 10px;
  text-align: center;
}

footer p {
  margin: 0;
}
## Use code with caution.
content_copy
## Este código CSS define estilos básicos para os elementos da página, como cores, fontes, tamanhos e espaçamentos.

**Abra o arquivo HTML em um
