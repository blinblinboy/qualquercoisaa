# qualquercoisaa
<!DOCTYPE html>
    <html lang="pt-BR">
    <head>
        <meta charset="UTF-8">
        <title>Galeria de Arte do Pablo Picasso</title>
        <link rel="stylesheet" type="text/css" href="galeria.css">
    </head>
    <body>
        <header class="primary-header">
        <h1 class="main-heading">Galeria de Arte do Pablo Picasso</h1>
        <nav>
            <ul class="main-nav">
            <li><a href="#guernica">Guernica</a></li>
            <li><a href="#les-demoiselles-d-avignon">Les Demoiselles d'Avignon</a></li>
            <li><a href="#a-mulher-que-chora">A Mulher que Chora</a></li>
            </ul>
        </nav>
        <figure class="town-preview">
            <a href="https://pt.wikipedia.org/wiki/Pablo_Picasso"><img src="Aulas_de_HTML-CSS-main/pasta/fotos/pablopicasso.png" alt="Ilustração de Pablo Picasso"></a>
            <figcaption>Ilustração de Pablo Picasso</figcaption>
        </figure>
        </header>
        <main class="gallery">
        <section class="store-section" id="guernica">
            <h2 class="category-heading">Guernica</h2>
            <ul class="store-list">
            <li class="store-name"><a href="https://pt.wikipedia.org/wiki/Guernica_(quadro)">Pintura Guernica</a></li>
            </ul>
        </section>
        <section class="store-section" id="les-demoiselles-d-avignon">
            <figure class="building">
            <a href="https://pt.wikipedia.org/wiki/Guernica_(quadro)"><img src="Aulas_de_HTML-CSS-main/pasta/fotos/guernica.png" alt="Ilustração da pintura Guernica"></a>
            <figcaption>Ilustração da pintura Guernica</figcaption>
            </figure>
            <div class="store-details">
            <h2 class="category-heading">Les Demoiselles d'Avignon</h2>
            <ul class="store-list">
                <li class="store-name"><a href="https://pt.wikipedia.org/wiki/Les_demoiselles_d%27Avignon">Pintura Les Demoiselles d'Avignon</a></li>
            </ul>
            </div>
        </section>
        <section class="store-section" id="a-mulher-que-chora">
            <figure class="building">
            <a href="https://pt.wikipedia.org/wiki/Les_demoiselles_d%27Avignon"><img src="Aulas_de_HTML-CSS-main/pasta/fotos/lesdemoiseles.png" alt="Ilustração da pintura les-demoiselles-d-avignon"></a>
            <figcaption>Ilustração da pintura les-demoiselles-d-avignon</figcaption>
            </figure>
            <div class="store-details"> 
                <h2 class="category-heading">A Mulher que Chora</h2>
                <ul class="store-list">
                  <li class="store-name"><a href="https://pt.wikipedia.org/wiki/A_mulher_que_chora">Pintura A Mulher que Chora</a></li> <img src="Aulas_de_HTML-CSS-main/pasta/fotos/amulherquechora.png    ">
                </ul>
              </div>
            </section>
        </body>
      </html>
      
      body{
    background-color: antiquewhite;
}

.gallery {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    height: 100vh;
  }

  .store-link {
    color: rgb(0, 0, 0);
}
