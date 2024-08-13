<html lang="pl">
<head>
    <meta charset="utf-8">
    <title>Kompletny Layout Strony z Mapą</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        table {
            width: 65%;
            border: 1px solid black;
            margin: 0 auto;
            border-collapse: collapse;
        }
        td {
            border: 1px solid black;
            padding: 10px;
        }
        iframe {
            border: 0;
            width: 100%;
            height: 420px;
        }
        img {
            max-width: 100%;
            height: auto;
        }
        .logo-container {
            text-align: center;
        }
        .logo {
            margin-left: 20%;
        }
    </style>
</head>
<body>
    <table>
        <tr>
            <td colspan="3" class="logo-container">
                <img src="Logotyp ZSE Gdańsk.jpg" alt="Logotyp ZSE Gdańsk" class="logo">
            </td>
        </tr>
        <tr>
            <td width="18%" align="center">
                <b>Lewe menu</b>
                <ul>
                    <li><a href="https://zse.edu.gdansk.pl/" target="obszar_glowny">Strona ZSE</a></li>
                    <li><a href="https://www.kuratorium.gda.pl/" target="obszar_glowny">Kuratorium</a></li>
                    <li><a href="https://pl.wikipedia.org/wiki/Plik:ZSE_Gdańsk.jpg" target="obszar_glowny">Wikipedia</a></li>
                    <li><a href="https://www.wikipedia.org" target="obszar_glowny">Wikipedia</a></li>
                </ul>
            </td>
            <td align="center">
                <iframe name="obszar_glowny" src="about:blank"></iframe>
            </td>
            <td width="18%" align="center">
                <b>Prawe menu</b>
                <img src="mapa1.gif" alt="Mapa interaktywna" usemap="#mapa_kowalski">
                <map name="mapa_kowalski">
                    <area shape="poly" coords="5,5,95,5,50,95" href="plik1.zip" alt="Opcja 1">
                    <area shape="rect" coords="0,100,100,150" href="https://kejpy.github.io/tabela/" target="obszar_glowny" alt="Opcja 2">
                    <area shape="circle" coords="50,200,25" href="https://kejpy.github.io/formularz/" target="obszar_glowny" alt="Opcja 3">
                    <area shape="poly" coords="5,230,95,230,50,290" href="mailto:kacper.wawrzyniakpekar@gmail.com" alt="Opcja 4">
                    <area shape="rect" coords="0,300,100,350" href="https://kacperwawrzyniak-pekar.github.io/index/" target="obszar_glowny" alt="Opcja 5">
                </map>
            </td>
        </tr> 
        <tr>
            <td colspan="3" align="center">
                <p>
<div class="image-rotator"><div class="rotator-slide" id="rotator-slide-1"><a href="https://www.darmowylicznik.pl/" title="Przejdź na stronę licznika" target="_blank"><img src="https://www.darmowylicznik.pl/licznik.php?id=147594" alt="Darmowy licznik odwiedzin" style="border:0px;" /></a></div></div>
    </p>
            </td>
        </tr>
    </table>
</body>
</html>
