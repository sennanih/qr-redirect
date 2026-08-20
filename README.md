<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>QR Redirect</title>

    <script>
        const tujuan = {
            "001": "https://www.google.com"
        };

        const params = new URLSearchParams(window.location.search);
        const id = params.get("id");

        if (tujuan[id]) {
            window.location.href = tujuan[id];
        }
    </script>
</head>

<body>
    <h2>QR belum aktif</h2>
    <p>Silakan hubungi admin.</p>
</body>
</html>
