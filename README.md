<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>💖 Nehir & Fero 💖</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background: linear-gradient(to right, #ffcccc, #ffe6e6);
            margin: 0;
            padding: 0;
        }
        .container {
            background: white;
            margin: 10px auto;
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
            margin-top: 10px;
            width: 90%;
        }
    </style>
    <script>
        // Sayfa yüklenmeden şifre sor
        window.onload = function() {
            var sifre = prompt("💖 Bu sayfa özel, şifreyi giriniz:");
            if (sifre !== "nehir") {
                alert("❌ Yanlış şifre!");
                document.body.innerHTML = "<h2 style='color:red;text-align:center;'>Erişim reddedildi ❌</h2>";
            }
        }
    </script>
</head>
<body>
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

        <audio autoplay loop controls>
            <source src="fall-in-love-264570.mp3" type="audio/mpeg">
            Tarayıcınız müzik çalmayı desteklemiyor.
        </audio>
    </div>
</body>
</html>
