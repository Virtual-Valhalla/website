<h1>Crear un nuevo Post</h1>
<p>Aviso: Por favor, sube las imágenes manualmente al repositorio y proporciona las URLs en los campos correspondientes.</p>
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

    <label for="image1-url">URL de la Imagen 1:</label><br>
    <input type="text" id="image1-url" name="image1-url" placeholder="https://example.com/imagen1.jpg"><br><br>

    <label for="image2-url">URL de la Imagen 2:</label><br>
    <input type="text" id="image2-url" name="image2-url" placeholder="https://example.com/imagen2.jpg"><br><br>

    <button type="submit">Crear Post</button>
</form>
