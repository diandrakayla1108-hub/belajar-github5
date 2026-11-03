# belajar-github5
Project belajar GitHub

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biodata Diri</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="container">
        <div class="card">

            <h1>BIODATA DIRI</h1>
            <p class="subtitle">Profil Pribadi Saya</p>

            <hr>

            <div class="biodata">
                <p><strong>Nama Lengkap:</strong> DIANDRA KAYLA ARAMITA</p>
                <p><strong>Tempat, Tanggal Lahir:</strong> OKUTIMUR,11 DESEMBER 2008</p>
                <p><strong>Jenis Kelamin:</strong> PEREMPUAN</p>
                <p><strong>Alamat:</strong> KURUNGAN NYAWA III</p>
                <p><strong>Agama:</strong> ISLAM</p>
                <p><strong>Hobi:</strong> MEMBACA</p>
                <p><strong>Cita-cita:</strong> SUKSES</p>
            </div>

            <button id="tombol">Klik Saya</button>

            <p id="pesan"></p>

        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>

const tombol = document.getElementById("tombol");
const pesan = document.getElementById("pesan");

tombol.addEventListener("click", function() {
    pesan.innerHTML = "Terima kasih telah mengunjungi biodata saya!";
});

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #74ebd5, #ACB6E5);
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

.container {
    width: 100%;
    padding: 20px;
}

.card {
    background: white;
    max-width: 450px;
    margin: auto;
    padding: 30px;
    border-radius: 20px;
    text-align: center;
    box-shadow: 0 8px 20px rgba(0,0,0,0.2);
}

h1 {
    color: #4b6584;
    margin-bottom: 10px;
}

.subtitle {
    color: #8395a7;
    margin-bottom: 20px;
}

hr {
    border: 1px solid #dfe6e9;
    margin-bottom: 20px;
}

.biodata {
    text-align: left;
    line-height: 2.2;
    color: #2d3436;
}

button {
    background: #0984e3;
    color: white;
    border: none;
    padding: 12px 25px;
    border-radius: 10px;
    margin-top: 20px;
    cursor: pointer;
    font-size: 16px;
}

button:hover {
    background: #0652DD;
}

#pesan {
    margin-top: 15px;
    color: #0984e3;
    font-weight: bold;
}
                
