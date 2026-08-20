<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>QR Redirect</title>
</head>

<body>
    <h2 id="status">Memproses...</h2>

    <script>
        const tujuan = {
            "001": "https://www.youtube.com/"
        };

        const params = new URLSearchParams(window.location.search);
        const id = params.get("id");

        if (tujuan[id]) {
            window.location.replace(tujuan[id]);
        } else {
            document.getElementById("status").innerText =
                "QR tidak ditemukan";
        }
    </script>
</body>
</html>
