# github.io
boites à citations
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Site de citations</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <div class="container">
      <div class="input-section">
        <h2>Ajouter une citation</h2>
        <textarea id="citation-input" placeholder="Entrez votre citation ici"></textarea>
        <button id="add-button">Ajouter</button>
      </div>
      <div class="citations-section">
        <div class="box" id="patriotiques">
          <h2>Citations patriotiques</h2>
        </div>
        <div class="box" id="communistes">
          <h2>Citations communistes</h2>
        </div>
        <div class="box" id="divers">
          <h2>Citations diverses</h2>
        </div>
      </div>
      <div class="search-section">
        <h2>Recherche de citations</h2>
        <input type="text" id="search-input" placeholder="Entrez un mot-clé ou une catégorie">
      </div>
    </div>
    <script src="script.js"></script>
  </body>
</html>
