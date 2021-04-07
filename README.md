# project-1
<html>

	<head>
		<title>Background Images — Practice</title>
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta charset="utf-8">
        <link href="css/reset.css" rel="stylesheet">
        <link href="lightbox/css/lightbox.min.css" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css?family=Metal+Mania" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css?family=Open+Sans:300" rel="stylesheet">
        <script src="https://use.fontawesome.com/0ca06f29a6.js"></script>
		<link href="css/style.css" rel="stylesheet">
	</head>

    <body>

        <header>
            <div id="topbar">
                <div class="container">
                    <nav>
                        <ul class="menu">
                            <li><a href="#">Домой</a></li>
                            <li><a href="#tour">Тур</a></li>
                            <li><a href="#gallery">Галерея</a></li>
                            <li><a href="#subscribe">Подписка</a></li>
                        </ul>
                    </nav>
                </div>
            </div>
            <div class="container">
                <h1>Super Duper Metal Band</h1>
                <a href="https://www.kassir.ru/" class="button">Покупка билетов</a>
                  <a href="https://stepin222.wixsite.com/mysite" class="button">Сайт строителей</a>  
            </div>
        </header>

        <div id="tour">
            <div class="container">
                <h2>Тур</h2>
                <div class="tour-card madrid">
                    <h3 class="tour-town">Мадрид, Испания</h3>
                    <p class="tour-place"><i class="fa fa-map-marker" aria-hidden="true"></i> Wizink Center</p>
                    <p class="tour-date">Октябрь 7, 2021</p>
                    <a href="#" class="button">Купить билеты</a>
                </div>
                <div class="tour-card turin">
                    <h3 class="tour-town">Турин, Италия</h3>
                    <p class="tour-place"><i class="fa fa-map-marker" aria-hidden="true"></i> Pala Alpitour</p>
                    <p class="tour-date">Октябрь 14, 2021</p>
                    <a href="#" class="button">Купить билеты</a>
                </div>
                <div class="tour-card hamburg">
                    <h3 class="tour-town">Гамбург, Германия</h3>
                    <p class="tour-place"><i class="fa fa-map-marker" aria-hidden="true"></i> Barclaycard Arena</p>
                    <p class="tour-date">Ноябрь 6, 2021</p>
                    <a href="#" class="button">Купить билеты</a>
                </div>
                <div class="tour-card krakow">
                    <h3 class="tour-town">Краков, Польша</h3>
                    <p class="tour-place"><i class="fa fa-map-marker" aria-hidden="true"></i> Tauron Arena</p>
                    <p class="tour-date">Ноябрь 12, 2021</p>
                    <a href="#" class="button">Купить билеты</a>
                </div>
            </div>
        </div>

        <div id="gallery">
            <div class="container">
                <h2>Галерея</h2>
                <figure class="photo">
                    <a href="img/gallery/originals/gallery-01.jpg" data-lightbox="roadtrip"><img src="img/gallery/gallery-01-min.jpg" alt="" /></a>
                </figure>

                <figure class="photo">
                    <a href="img/gallery/originals/gallery-02.jpg" data-lightbox="roadtrip"><img src="img/gallery/gallery-02-min.jpg" alt="" /></a>
                </figure>

                <figure class="photo">
                    <a href="img/gallery/originals/gallery-03.jpg" data-lightbox="roadtrip"><img src="img/gallery/gallery-03-min.jpg" alt="" /></a>
                </figure>

                <figure class="photo">
                    <a href="img/gallery/originals/gallery-04.jpg" data-lightbox="roadtrip"><img src="img/gallery/gallery-04-min.jpg" alt="" /></a>
                </figure>

                <figure class="photo">
                    <a href="img/gallery/originals/gallery-05.jpg" data-lightbox="roadtrip"><img src="img/gallery/gallery-05-min.jpg" alt="" /></a>
                </figure>

                <figure class="photo">
                    <a href="img/gallery/originals/gallery-06.jpg" data-lightbox="roadtrip"><img src="img/gallery/gallery-06-min.jpg" alt="" /></a>
                </figure>
            </div>
        </div>

        <div id="subscribe">
            <div class="container">
                <div class="pitch">
                    <h2>Подписывайся</h2>
                    <p>Подпишитесь, чтобы получать последние новости о группе прямо на свой почтовый ящик.<p>
                </div>
                <form action="" method="post" class="subscribe-form">
                    <input type="email" name="email" placeholder="Email">
                    <button type="submit">Подписывайся</button>
                </form>
            </div>
        </div>

        <footer>
            <div class="container">
                <div class="social">
                    <a href="#"><i class="fa fa-facebook-official"></i></a>
                    <a href="#"><i class="fa fa-twitter"></i></a>
                    <a href="#"><i class="fa fa-youtube"></i></a>
                    <a href="#"><i class="fa fa-apple"></i></a>
                    <a href="#"><i class="fa fa-spotify"></i></a>
                    <a href="#"><i class="fa fa-soundcloud"></i></a>
                </div>
                <p class="copyright">© Все права защищены</p>
            </div>
        </footer>

        <script src="lightbox/js/lightbox-plus-jquery.min.js"></script>
    </body>
</html>
