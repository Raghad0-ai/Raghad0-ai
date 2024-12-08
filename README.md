
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تحريك صورة</title>
    <style>
        .background {
            background-image: url('https://drive.google.com/uc?id=1g9TPPZ1xC1u0WFRswGxS0vAYMc9DKs-H');
            background-size: cover;
            width: 400px; /* عرض العنصر */
            height: 400px; /* ارتفاع العنصر */
            animation: move 2s infinite alternate;
        }

        @keyframes move {
            from {
                transform: translateX(0);
            }
            to {
                transform: translateX(100px);
            }
        }
    </style>
</head>
<body>
    <div class="background"></div>
</body>
</html>
