# Merry-Christmas-
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<title>Merry Christmas 🎄</title>

<style>
body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    background: linear-gradient(#c62828, #2e7d32);
    color: white;
    text-align: center;
    overflow-x: hidden;
}

/* Salju lembut */
.snow {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    pointer-events: none;
    background-image: radial-gradient(white 2px, transparent 2px);
    background-size: 35px 35px;
    animation: snow 8s linear infinite;
    opacity: 0.6;
}
@keyframes snow {
    from { background-position: 0 0; }
    to { background-position: 0 600px; }
}

/* Judul utama */
.header {
    padding: 40px 20px 10px;
}

.header h1 {
    font-size: 42px;
    margin: 0;
    color: #ffeb3b;
    letter-spacing: 1px;
}

.header h2 {
    font-size: 22px;
    margin-top: 10px;
    font-weight: normal;
}

/* Kartu isi */
.card {
    margin: 25px auto;
    padding: 30px;
    max-width: 520px;
    background: rgba(255,255,255,0.15);
    border-radius: 18px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.3);
}

.icons {
    font-size: 42px;
    margin-bottom: 15px;
}

p {
    font-size: 16px;
    line-height: 1.6;
}
</style>
</head>

<body>

<!-- Musik Natal lembut -->
<audio autoplay loop>
    <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-3.mp3" type="audio/mpeg">
</audio>

<div class="snow"></div>

<!-- Judul Paling Atas -->
<div class="header">
    <h1>Merry Christmas 🎄</h1>
    <h2>From Melissa & Jason</h2>
</div>

<div class="card">
    <div class="icons">🎄☃️🎁✨</div>

    <p>
        Semoga Natal ini membawa kedamaian,<br>
        kebahagiaan, dan harapan baru.
    </p>

    <p>
        Kiranya kehangatan Natal menyertai<br>
        setiap langkah dan harimu.
    </p>

    <div class="icons">✨🎁☃️🎄</div>
</div>

</body>
</html>
