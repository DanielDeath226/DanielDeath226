<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sarah Nainggolan </title>
    <link rel="stylesheet" href="./style.css">
</head>
<body>
    <audio autoplay>
        <source src="Ed Sheeran - Perfect (320).mp3" type="audio/mp3"/>
    </audio>
    <div class="container">
        <div class="envelope-wrapper">
            <div class="envelope">
                <div class="letter">
                    <div class="text">
                        <strong>Dear Person.</strong>
                        <p>
                            Sa Tau Ini Mungkin Terlalu Cepat Tapi Sa Malas Menunggu Lama-lama Jadi Sebenarnya Sa Suka Sama Mu
                            Dari Saat Ketemu Sampai Saat Ini.
                        </p>
                        <p>
                            Jadi Mungkin Lewat Ini Sa Mau Ungkap Kan Perasaan Sama Mu. Kalau Mungkin Ko Biasa Saja Sama Sa Gapapa  Sihh.
                            Mungkin Itu Saja Sih Sa Juga Gabisa Maksa
                            Sa Mau Bilang Secara Langsung Tapi Kemarin Ko Ke Arso.
                            Soryy Keliatan Biasa Saja Website Nya Dan Mungkin Ini Terlalu Cepat
                        </p>
                    </div>
                </div>
            </div>
            <div class="heart"></div>
        </div>
    </div>
    <script>
        const envelope = document.querySelector('.envelope-wrapper');
        envelope.addEventListener('click', () => {
            envelope.classList.toggle('flap');
        });
    </script>
</body>
</html>
