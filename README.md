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
    })(document, 'script', 'https://script.ringostat.com/v4/e2/e2656b682894fe4968ebb937b28f1c80557ed878.js');
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
            <div class="aroma-header__top">
                <div class="aroma-header__top-left-links">
                 <a href="tel:+380675095964">
                     <svg width="14" height="21" viewBox="0 0 14 21" fill="none" xmlns="http://www.w3.org/2000/svg">
                         <rect x="1" y="1.54993" width="12" height="18" stroke="#212121" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"></rect>
                         <path d="M7 16.2166H7.01111" stroke="#212121" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
                     </svg>
                     +38 067 509 59 64
                 </a>
                </div>
            </div>    
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
