# Juandavidzapata.github.oi

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="index.css">
    <title>Cifrador Juanda</title>
</head>
<body>
    <main>
>      <h1>Cifrador Juanda</h1>
    <form id="cifrador" autocomplete="off">
       <input id="input original" spellcheck="false" placeholder="Ingrese el texto " type="text" name="text">
    </form>
<div id="resultado"></div>
<div class="rango">
    <input id="rango" type="range" value="10" min="1" max="20" oninput="this.nextElementSibling.value = this.value">
    <output>10</output>
</div>
    </main>
</body>
</html>
