<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Форма заявки</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f5f5f5;
        }
        .form-box {
            width: 300px;
            margin: 50px auto;
            padding: 20px;
            background: #ffffff;
            border-radius: 6px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        input, button {
            width: 100%;
            padding: 8px;
            margin-top: 10px;
        }
        button {
            cursor: pointer;
        }
    </style>
</head>
    <!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-0XQ4JBL17F"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-0XQ4JBL17F');
</script>
<body>
<script type="text/javascript">
    (function (d,s,u,e,p) {
      p=d.getElementsByTagName(s)[0],e=d.createElement(s),e.async=1,e.src=u,p.parentNode.insertBefore(e, p);
    })(document, 'script', 'https://script.ringostat.com/v4/e2/e2656b682894fe4968ebb937b28f1c80557ed878.js');
    var pw = function() {if (typeof(ringostatAnalytics) === "undefined") {setTimeout(pw,100);} else {ringostatAnalytics.sendHit('pageview');}};
    pw();
</script>
<div class="form-box">
    <form action="#" method="post">
        <label>
            Имя:
            <input type="text" class="ringostatname" name="name" required>
        </label>

        <label>
            Номер телефона:
            <input type="tel" name="phone" class="ringostatphone" placeholder="+380..." required>
        </label>

        <button type="submit" class="ringostat">Отправить</button>
    </form>
</div>

</body>
</html>
