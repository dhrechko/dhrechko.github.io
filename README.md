<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Пример сайта</title>
    <link rel="stylesheet" href="style.css"> <!-- подключение CSS -->
    <script type="text/javascript">
    (function (d,s,u,e,p) {
      p=d.getElementsByTagName(s)[0],e=d.createElement(s),e.async=1,e.src=u,p.parentNode.insertBefore(e, p);
    })(document, 'script', 'https://script.ringostat.com/v4/44/4471f95785dc0992a846a479166cc697b3066d15.js');
    var pw = function() {if (typeof(ringostatAnalytics) === "undefined") {setTimeout(pw,100);} else {ringostatAnalytics.sendHit('pageview');}};
    pw();
</script>
</head>
<body>
    <header>
        <h1>Добро пожаловать на мой сайт</h1>
        <nav>
            <ul>
                <li><a href="#about">О проекте</a></li>
                <li><a href="#contact">Контакты</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>О проекте</h2>
            <p>Это базовая разметка HTML для демонстрации структуры сайта.</p>
        </section>

        <section id="contact">
            <h2>Контакты</h2>
            <p>Email: example@mail.com</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Мой сайт</p>
    </footer>

    <script src="script.js"></script> <!-- подключение JS -->
</body>
</html>
