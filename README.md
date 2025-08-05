<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>💖 Nehir & Fero 💖</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #ffcccc, #ffe6e6);
            margin: 0;
            padding: 0;
        }
        /* Giriş ekranı */
        #girisEkrani {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            text-align: center;
            background: rgba(255, 255, 255, 0.8);
        }
        #girisEkrani h2 {
            color: #ff4d79;
            font-size: 1.5em;
            margin-bottom: 20px;
        }
        #sifreInput {
            padding: 10px;
            border: 2px solid #ff4d79;
            border-radius: 10px;
            font-size: 1em;
            outline: none;
            text-align: center;
        }
        #girisButon {
            margin-top: 15px;
            padding: 10px 20px;
            background: #ff4d79;
            color: white;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            font-size: 1em;
        }
        #girisButon:hover {
            background: #ff1a57;
        }
        /* Ana içerik */
        #icerik {
            display: none;
            text-align: center;
            padding: 10px;
        }
        .container {
            background: white;
            margin: 0 auto;
            padding: 15px;
            max-width: 350px;
            border-radius: 15px;
            box-shadow: 0 0 15px rgba(0,0,0,0.1);
        }
        h1 {
            color: #ff4d79;
            font-size: 1.4em;
        }
        p {
            font-style: italic;
            color: #555;
            font-size: 0.9em;
        }
        img {
            width: 100%;
            max-width: 220px;
            border-radius: 10px;
            margin: 10px 0;
        }
        .date {
            font-weight: bold;
            font-size: 1em;
        }
        audio {
            display: none; /* Gizli müzik */
        }
    </style>
    <script>
        function girisYap() {
            var sifre = document.getElementById("sifreInput").value.trim();
            if (sifre === "1.83") {
                document.getElementById("girisEkrani").style.display = "none";
                document.getElementById("icerik").style.display = "block";
                document.getElementById("bg-music").play();
            } else {
                alert("❌ Yanlış cevap!");
            }
        }
    </script>
</head>
<body>
    <!-- Giriş ekranı -->
    <div id="girisEkrani">
        <h2>💖 Hoş geldin, bu sayfa özel 💖<br>🔑 Soru: FERO'NUN BOYU nedir?</h2>
        <input type="text" id="sifreInput" placeholder="Boyu buraya yaz">
        <button id="girisButon" onclick="girisYap()">Giriş</button>
    </div>

    <!-- Ana içerik -->
    <div id="icerik">
        <audio id="bg-music" autoplay loop>
            <source src="fall-in-love-264570.mp3" type="audio/mpeg">
        </audio>

        <div class="container">
            <h1>💖✨ Nehir & Fero ✨💖</h1>
            <p>Sevgili olduk: <span class="date">16.07.2025</span></p>

            <img src="IMG_20250805_080010.jpg" alt="Bebek">
            <p>Hayatımın en saf, en masum gülüşü… Bir gün elimizi hiç bırakmayacak ellerin küçüklüğünde koca bir dünya saklı.</p>

            <img src="IMG_20250805_075902.jpg" alt="Göz">
            <p>Bir bakışın var ki… konuşmadan anlıyor, dokunmadan hissettiriyor. Sanki tüm hikâyem gözlerinde yazılı.</p>

            <img src="IMG_20250805_080208.jpg" alt="Ayna">
            <p>Sen kadraja bile sığmayan güzelliğinle, karanlık odaları bile aydınlatan bir ışıksın.</p>

            <img src="d04293a2-78ce-4086-a3ce-793bec60bc89.jpg" alt="Motosiklet">
            <p>Yol uzun, gece serin… Ama sen yanımdayken ne üşürüm ne de yorulurum. İki teker, bir aşk hikâyesi ve sonsuza kadar sürecek bir yolculuk.</p>
        </div>
    </div>
</body>
</html>
