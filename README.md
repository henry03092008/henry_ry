
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>pesan buat pacarr kuu yangg cantikk</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #fce4ec;
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            text-align: center;
            padding: 30px;
            background-color: #ffffff;
            border-radius: 15px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }
        h1 {
            color: #f06292;
        }
        p {
            font-size: 20px;
            margin: 20px 0;
            font-style: italic;
        }
        .gombal {
            font-size: 22px;
            font-weight: bold;
            color: #d81b60;
        }
        button {
            padding: 12px 25px;
            background-color: #f06292;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 18px;
            transition: background-color 0.3s ease;
        }
        button:hover {
            background-color: #d81b60;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>DI BACAA YAA CANTIKKK</h1>
        <p>akuuu harapp kitaaa bisaaa samaa-samaa teruss yaa</p>

        <div class="gombal">
            <p id="gombalMessage">"Kamu itu seperti bintang di langit, selalu ada meskipun kadang tak terlihat, tapi aku tahu, kamu selalu menyinari hidupku. Karena kamu adalah alasan aku bisa tertawa setiap hari."</p>
        </div>

        <button onclick="changeMessage()">Ganti Pesan Gombal</button>
    </div>

    <script>
        const messages = [
            '"Setiap detik bersamamu adalah detik yang paling berharga. Aku ingin hidup selamanya dalam pelukanmu, karena kamu adalah alasan aku merasa lengkap."',
            '"Kamu adalah rumah tempat hatiku kembali. Tidak ada tempat lain yang lebih nyaman selain berada di sampingmu, kini dan selamanya."',
            '"Aku tidak butuh bintang di langit, karena kamu sudah cukup menjadi cahayaku yang terang di malam hari."',
            '"Ketika aku mencintaimu, aku tahu bahwa tidak ada yang lebih indah dari itu. Kamu adalah anugerah terindah yang pernah aku terima."',
            '"Setiap kali aku merasa ragu, kamu datang seperti angin yang menenangkan. Kamu adalah jawaban dari segala kebingunganku."',
            '"Aku ingin selalu berada di sisimu, menjalani hari-hari penuh cinta bersama, hingga waktu berhenti berputar."'
        ];

        function changeMessage() {
            const randomIndex = Math.floor(Math.random() * messages.length);
            document.getElementById("gombalMessage").textContent = messages[randomIndex];
        }
    </script>

</body>
</html>
