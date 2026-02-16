<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ma presentation</title>
    <!-- font family -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
    <!--style css-->
    <style>
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            text-decoration: none;
            font-family: "Poppins", sans-serif;
        }
        body{
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0;
            color: white;
            background: #9400D3;
            background: linear-gradient(to right,#9400D3,#4B0082);
            height: 100vh;
        }
        .right{
            display: flex;
            align-items: center;
            width: 75vw;
            max-width: 650px;
            padding: 50px 30px 50px 20px;
            background: black;
            border-radius: 24px;
        }
        .right img{
            max-width: 280px;
            width: 35vw;
            height: 300px;
            object-fit: cover;
            margin-left: -60px;
            margin-right: 30px;
            border-radius: inherit;
            box-shadow: 0 60px 40px rgb(0 0 0 / 8%);
        }
        .right h2{
            font-size: 26px;
            font-weight: 400;
            margin-top: 0;
            margin-right: 30px;
            margin-bottom: 10px;
        }
        .right h3{
            font-size: 16px;
            font-weight: 400;
            opacity: 0.75;
        }
        .right p{
            font-size: 14px;
            font-weight: 400;
            margin-bottom: 30px;
        }
        .right button {
            border: 1px solid white;
            background: transparent;
            color: white;
            padding: 16px 26px;
            font-size: 16px;
            border-radius: 40px;
            font-family: inherit;
        }
        @media (width <= 600px ){
            .right{
                margin: 0 40px;
                padding-left: 50px;
                padding-right: 50px;
                padding-bottom: 60px;
                width: 100%;
                text-align: center;
                flex-direction: column;
            }
            .right h2{
                margin-right: 0;
                font-size: 26px;
            }
            .right img{
                margin: -100px 0 30px 0;
                width: 100%;
                max-width: 1000px;
                height: 250px;
            }
            .right p{
                max-width: 360px;
            }
        }
        @media (width <= 440px ){
            .right img{
                height: 45vw;
                width: 45vw;
                border-radius: 50%;
                margin: -140px 0 30px 0;
            }
        }
    </style>
</head>
<body>
    <!--ma description-->
    
    <div class="right">
        <img src="image,video/WhatsApp Image 2026-02-14 at 14.00.55.jpeg" alt="Photo">
        <div>
            <h2>ATHILEY Rudolph K. Geraud</h2>
            <h3>Etudiant en licence 1 IA/BD.</h3>
            <p>J'ai 18 ans , je viens de l'etablissement revelateur des talents et c'est mon premier projet sur github , ce base c'est un taf donner par monsieur de html mais j'ai decider partager ce petit moment de code avec vous.</p>
            <button>En savoir plus ? <span class="icon">➡️</span></button>
        </div>
    </div>
</body>
</html>
