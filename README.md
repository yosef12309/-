# -<!DOCTYPE html>
<html lang="he">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>YH Jewelry</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            direction: rtl;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        section {
            padding: 50px;
            text-align: center;
        }

        h1, h2, h3 {
            color: #333;
        }

        .product-gallery {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 30px;
        }

        .product-item {
            width: 250px;
            text-align: center;
        }

        .product-item img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }

        footer ul {
            list-style-type: none;
            padding: 0;
        }

        footer ul li {
            display: inline;
            margin: 0 15px;
        }
    </style>
</head>
<body>
    <header>
        <h1>YH Jewelry</h1>
        <nav>
            <ul>
                <li><a href="#home">דף הבית</a></li>
                <li><a href="#catalog">קטלוג</a></li>
                <li><a href="#about">אודות</a></li>
                <li><a href="#contact">צור קשר</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>ברוכים הבאים ל-YH Jewelry</h2>
        <p>תכשיטים בעיצוב ייחודי ומרשים</p>
    </section>

    <section id="catalog">
        <h3>הקטלוג שלנו</h3>
        <p>בחרו את התכשיטים המועדפים עליכם:</p>
        <div class="product-gallery">
            <div class="product-item">
                <img src="https://via.placeholder.com/250x250?text=Ring" alt="טבעת">
                <p>טבעת יהלום</p>
            </div>
            <div class="product-item">
                <img src="https://via.placeholder.com/250x250?text=Necklace" alt="שרשרת">
                <p>שרשרת זהב</p>
            </div>
            <div class="product-item">
                <img src="https://via.placeholder.com/250x250?text=Bracelet" alt="צמיד">
                <p>צמיד אלגנטי</p>
            </div>
            <div class="product-item">
                <img src="https://via.placeholder.com/250x250?text=Earrings" alt="עגילים">
                <p>עגילים ייחודיים</p>
            </div>
            <div class="product-item">
                <img src="https://via.placeholder.com/250x250?text=Diamond+Jewelry" alt="תכשיטים משובצים יהלומים">
                <p>תכשיטים משובצים יהלומים</p>
            </div>
            <div class="product-item">
                <img src="https://via.placeholder.com/250x250?text=Non-Diamond+Jewelry" alt="תכשיטים לא משובצים">
                <p>תכשיטים לא משובצים</p>
            </div>
        </div>
    </section>

    <section id="about">
        <h3>אודות</h3>
        <p>YH Jewelry מתמחה בעיצוב תכשיטים איכותיים ומרשימים, תוך שימוש בחומרים הטובים ביותר ובטכנולוגיות מתקדמות.</p>
    </section>

    <section id="contact">
        <h3>צור קשר</h3>
        <p>לפרטים נוספים, אל תהססו לפנות אלינו!</p>
        <ul>
            <li>טלפון: 054-9027246</li>
            <li>אימייל: yosafhen@gmail.com</li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2025 YH Jewelry | כל הזכויות שמורות</p>
        <ul>
            <li><a href="#">מדיניות פרטיות</a></li>
            <li><a href="#">תנאי שימוש</a></li>
        </ul>
    </footer>
</body>
</html>
