<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8 />
  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Donut Lovers</title>
</head>

<body>
<header>
  <h1>🍩 Donut Lovers</h1>
  <nav>
    <a href="#" role="button" onclick="showPage('home')">Home</a>
  </nav>
</header>

<main>
  <section id="home">
    <h2>Home</h2>
    <h3>Welcome to Donut Lovers! 🍩</h3>
    <p><strong>Your sweet journey starts here!</strong></p>

<p>
Donuts actually have a fascinating history — the ring shape we all know today was popularized in the mid‑1800s by a sailor named Hanson Gregory, who claimed he cut a hole in the middle so the dough would cook evenly. Since then,donuts have become a global treat, with countless variations from the American glazed classic to Japan’s matcha‑flavored creations. In fact, donuts are so beloved that the United States celebrates National Donut Day every June, a tradition that started in 1938 to honor volunteers who served donuts to soldiers during World War I
Explore different kinds of donuts from around the world.
</p>
  </section>
</main>

<script>
function showPage(pageId) {
  document.querySelectorAll('main section').forEach(sec => sec.style.display = "none");
  document.getElementById(pageId).style.display = "block";
}
</script>

</body>
</html>

