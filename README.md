<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pokédex</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="hero">
    <div class="hero-inner">

    
      <div class="top-image">
        <img src="logo..png" alt="Imagen de encabezado">
      </div>

      <p>Explora y descubre tus Pokémon favoritos</p>

      <div class="search-wrap">
        <input id="search" type="search" placeholder="Buscar por nombre o número...">
      </div>
    </div>
  </header>

  <main>
    <nav id="filters" class="filters">
      <button class="active" data-type="all">Todos</button>
      <button data-type="normal">Normal</button>
      <button data-type="fire">Fire</button>
      <button data-type="water">Water</button>
      <button data-type="grass">Grass</button>
      <button data-type="electric">Electric</button>
      <button data-type="ice">Ice</button>
      <button data-type="fighting">Fighting</button>
      <button data-type="poison">Poison</button>
      <button data-type="ground">Ground</button>
      <button data-type="flying">Flying</button>
      <button data-type="psychic">Psychic</button>
      <button data-type="bug">Bug</button>
      <button data-type="rock">Rock</button>
      <button data-type="ghost">Ghost</button>
      <button data-type="dark">Dark</button>
      <button data-type="dragon">Dragon</button>
      <button data-type="steel">Steel</button>
      <button data-type="fairy">Fairy</button>
    </nav>

    <div class="status" id="status">Cargando Pokémon...</div>
    <section id="grid" class="grid"></section>
  </main>

  <button id="topBtn" class="top-btn">↑</button>
  <script src="script.js"></script>
</body>
</html>
