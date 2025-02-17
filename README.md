
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animasi Teks</title>
    <style>
        .marquee {
            font-size: 24px;
            font-weight: bold;
            white-space: nowrap;
            overflow: hidden;
            display: inline-block;
            animation: marquee 5s linear infinite;
        }

        @keyframes marquee {
            from {
                transform: translateX(100%);
            }
            to {
                transform: translateX(-100%);
            }
        }
    </style>
</head>
<body>
    <div class="marquee">Halo! selamat datang di web marsha, enjoy 🚀</div>
</body>
</html>
