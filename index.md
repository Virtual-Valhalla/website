---
layout: default
---

<h1>Crear un nuevo Post</h1>
<form action="/submit-post" method="POST">
    <label for="title">Título:</label><br>
    <input type="text" id="title" name="title" required><br><br>

    <label for="date">Fecha:</label><br>
    <input type="date" id="date" name="date" required><br><br>

    <label for="author">Autor:</label><br>
    <input type="text" id="author" name="author" required><br><br>

    <label for="categories">Categorías:</label><br>
    <input type="text" id="categories" name="categories" required><br><br>

    <label for="tags">Etiquetas:</label><br>
    <input type="text" id="tags" name="tags"><br><br>

    <label for="excerpt">Extracto:</label><br>
    <textarea id="excerpt" name="excerpt" required></textarea><br><br>

    <label for="content">Contenido:</label><br>
    <textarea id="content" name="content" required></textarea><br><br>

    <button type="submit">Crear Post</button>
</form>
