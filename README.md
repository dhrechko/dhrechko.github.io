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
<body>

<div class="form-box">
    <form action="#" method="post">
        <label>
            Имя:
            <input type="text" class="ringostatphone" name="name" required>
        </label>

        <label>
            Номер телефона:
            <input type="tel" name="phone" class="ringostatname" placeholder="+380..." required>
        </label>

        <button type="submit" class="ringostat">Отправить</button>
    </form>
</div>

</body>
</html>
