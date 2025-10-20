index.html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Paloma Buarque</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1><a href="index.html">Paloma Buarque</a></h1>
    <nav>
      <a href="index.html" class="active">Início</a>
      <a href="textos.html">Textos</a>
    </nav>
  </header>

  <main>
    <section class="intro">
      <h2>Escritora, pesquisadora e ilustradora</h2>
      <p>Crio histórias e ilustrações que exploram o real, o íntimo e o invisível.</p>
    </section>
  </main>

  <footer>
    <p>© 2025 Paloma Buarque</p>
  </footer>
</body>
</html>

textos.html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Textos | Paloma Buarque</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1><a href="index.html">Paloma Buarque</a></h1>
    <nav>
      <a href="index.html">Início</a>
      <a href="textos.html" class="active">Textos</a>
    </nav>
  </header>

  <main>
    <section class="lista-textos">
      <h2>Textos</h2>

      <article>
        <h3><a href="texto1.html">A casa e o espelho</a></h3>
        <p>Um ensaio breve sobre a solidão e os espaços que habitamos — internos e externos.</p>
      </article>

      <article>
        <h3><a href="texto2.html">Lugares que cabem no bolso</a></h3>
        <p>Reflexão sobre memória, fotografia e o desejo de conter o tempo.</p>
      </article>

    </section>
  </main>

  <footer>
    <p>© 2025 Paloma Buarque</p>
  </footer>
</body>
</html>

texto1.html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>A casa e o espelho | Paloma Buarque</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1><a href="index.html">Paloma Buarque</a></h1>
    <nav>
      <a href="index.html">Início</a>
      <a href="textos.html">Textos</a>
    </nav>
  </header>

  <main>
    <article class="texto">
      <h2>A casa e o espelho</h2>
      <p>Coloque aqui o texto completo. Você pode escrever livremente, com parágrafos e espaçamento.</p>
      <p>Exemplo de segundo parágrafo.</p>
    </article>
  </main>

  <footer>
    <p>© 2025 Paloma Buarque</p>
  </footer>
</body>
</html>

style.css
body {
  font-family: "Helvetica Neue", Arial, sans-serif;
  color: #222;
  background: #fff;
  margin: 0;
  padding: 0;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 2rem 4rem;
}

header a {
  text-decoration: none;
  color: #000;
}

nav a {
  margin-left: 2rem;
  font-weight: 500;
}

nav a.active {
  text-decoration: underline;
}

main {
  padding: 2rem 4rem;
  max-width: 800px;
  margin: 0 auto;
}

h1, h2, h3 {
  font-weight: 500;
}

.intro {
  margin-top: 4rem;
}

.lista-textos h2 {
  margin-bottom: 2rem;
}

.lista-textos article {
  margin-bottom: 3rem;
}

.lista-textos h3 a {
  color: #000;
  text-decoration: none;
}

.lista-textos h3 a:hover {
  text-decoration: underline;
}

.texto {
  margin-top: 4rem;
  line-height: 1.6;
}

footer {
  text-align: center;
  padding: 3rem 0;
  font-size: 0.9rem;
  color: #555;
}
