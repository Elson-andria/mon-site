<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Entreprise de Elson</title>

    <style>

        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
        }

        body{
            font-family: Arial, Helvetica, sans-serif;
            background:#f4f4f4;
            color:#333;
        }

        /* MENU */

        header{
            background:#111;
            padding:20px;
        }

        nav{
            display:flex;
            justify-content:space-between;
            align-items:center;
        }

        .logo{
            color:white;
            font-size:28px;
            font-weight:bold;
        }

        nav ul{
            display:flex;
            list-style:none;
        }

        nav ul li{
            margin-left:20px;
        }

        nav ul li a{
            color:white;
            text-decoration:none;
            transition:0.3s;
        }

        nav ul li a:hover{
            color:#00bfff;
        }

        /* HERO */

        .hero{
            height:90vh;
            background:linear-gradient(rgba(0,0,0,0.6),
            rgba(0,0,0,0.6)),
            url('https://scontent.ftnr2-2.fna.fbcdn.net/v/t39.30808-6/326344565_711652287267605_6310448203865757549_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=6ee11a&_nc_ohc=Y0gQKHgGWoUQ7kNvwHImjLH&_nc_oc=AdplAw52hAribTCS83vfMbOMgZl37gOeH29ogaQpEyFNoO12AisOtsuaL39m9FjGgls&_nc_zt=23&_nc_ht=scontent.ftnr2-2.fna&_nc_gid=67fIhbUXDpo-r52rNFFC7Q&_nc_ss=7b2a8&oh=00_Af7OxTqNTTwx9kiwq2Ulg4SlwtlYYyPR84orO5dy79S0-A&oe=6A09E673') center/cover;

            display:flex;
            justify-content:center;
            align-items:center;
            text-align:center;
            color:white;
            padding:20px;
        }

        .hero-content h1{
            font-size:60px;
            margin-bottom:20px;
        }

        .hero-content p{
            font-size:20px;
            margin-bottom:30px;
        }

        .btn{
            padding:15px 30px;
            background:#00bfff;
            color:white;
            text-decoration:none;
            border-radius:5px;
            transition:0.3s;
        }

        .btn:hover{
            background:#009acd;
        }

        /* SERVICES */

        .services{
            padding:80px 20px;
            text-align:center;
        }

        .services h2{
            margin-bottom:40px;
            font-size:40px;
        }

        .cards{
            display:flex;
            justify-content:center;
            flex-wrap:wrap;
            gap:20px;
        }

        .card{
            background:white;
            padding:30px;
            width:300px;
            border-radius:10px;
            box-shadow:0 5px 15px rgba(0,0,0,0.1);
            transition:0.3s;
        }

        .card:hover{
            transform:translateY(-10px);
        }

        .card h3{
            margin-bottom:15px;
        }

        /* FOOTER */

        footer{
            background:#111;
            color:white;
            text-align:center;
            padding:20px;
        }

        /* RESPONSIVE */

        @media(max-width:768px){

            .hero-content h1{
                font-size:40px;
            }

            nav{
                flex-direction:column;
            }

            nav ul{
                margin-top:15px;
            }

        }

    </style>

</head>

<body>

    <!-- MENU -->

    <header>

        <nav>

            <div class="logo">Elson</div>

            <ul>
                <li><a href="#accueil">Accueil</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>

        </nav>

    </header>

    <!-- HERO -->

    <section class="hero" id="accueil">

        <div class="hero-content">

            <h1>Mon premier site professionnel</h1>

            <p>
                Nous développons des sites modernes,
                rapides et responsives.
            </p>

            <a href="#" class="btn">
                Commencer
            </a>

        </div>

    </section>

    <!-- SERVICES -->

    <section class="services" id="services">

        <h2>Nos Services</h2>

        <div class="cards">

            <div class="card">
                <h3>Développement Web</h3>
                <p>
                    Création de sites vitrines et applications web modernes.
                </p>
            </div>

            <div class="card">
                <h3>Responsive Design</h3>
                <p>
                    Compatible mobile, tablette et ordinateur.
                </p>
            </div>

            <div class="card">
                <h3>SEO</h3>
                <p>
                    Optimisation pour apparaître sur Google.
                </p>
            </div>

        </div>

    </section>

    <!-- FOOTER --><section id="portfolio" class="services">

    <h2>Mon Portfolio</h2>

    <div class="cards">

        <div class="card">
            <h3>Projet 1</h3>
            <p>Mon premier site web professionnel.</p>
        </div>

        <div class="card">
            <h3>Projet 2</h3>
            <p>Design moderne et responsive.</p>
        </div>

    </div>

</section>

<!-- CONTACT -->

<section id="contact" class="services">

    <h2>Contact</h2>

    <p>Email : andriaharivelonirina@gmail.com</p>

    <br>

    <input type="text" placeholder="Votre nom">

    <br><br>

    <input type="email" placeholder="Votre email">

    <br><br>

    <textarea placeholder="Votre message"></textarea>

</section>

    <footer>

        <p>
            © 2026 DEVPRO - Tous droits réservés
        </p>

    </footer>

</body>

</html>
