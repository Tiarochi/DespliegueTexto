<!DOCTYPE html>
<html>
<head>
    <title>Formulario PHP</title>
</head>
<body>
    <h2>Introduce tu nombre:</h2>
    <form method="post">
        <input type="text" name="nombre">
        <input type="submit" value="Enviar">
    </form>
    <br>

    <?php
    if ($_SERVER["REQUEST_METHOD"] == "POST") {
        $nombre = $_POST['nombre'];
        echo "<h3>Hola, $nombre</h3>";
    }
    ?>
</body>
</html>