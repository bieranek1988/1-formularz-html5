<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>

<body>

    <form action="https://formspree.io/kamil.bieranowski.1988@wp.pl" method="post">
        <label for="firstname">Imię:</label><br>
        <input type="text" name="name" id="firstname"><br>
        <label for="surname">Nazwisko:</label><br>
        <input type="text" name="surname" id="surname"><br>
        <label for="e-mail">e-mail:</label><br>
        <input type="text" name="e-mail" id="e-mail"><br>
        <label for="phone-number">Telefon:</label><br>
        <input type="text" name="phone-number" id="phone-number"><br>




        <label for="city">Wybór miasta:</label><br>
        <select name="city" id="city">
            <option value="city">Kraków:</option>
            <option value="city">Warszawa:</option>
            <option value="city">Gdańsk:</option>
        </select><br>

        <label for="gender">Płeć:</label><br>
        <label for="gender">Kobieta:</label>
        <input type="radio" name="gender" value="female" id="gender">
        <label for="gender">Mężczyzna:</label>
        <input type="radio" name="gender" value="male"><br>

        <input type="checkbox" name="consent" value="consent">
        <label for="message">Wyrażam zgodę na przetwarzanie danych osobowych.</label>

        <label for="message">Wiadomość:</label><br>
        <textarea name="<message>" id="message" cols="60" rows="10"></textarea><br>
        <input type="submit" value="Wyslij">






    </form>

</body>

</html>
