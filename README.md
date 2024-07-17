<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>نموذج بسيط</title>
</head>
<body>
    <form action="submit_form.php" method="post">
        <label for="gender">الجنس:</label>
        <select id="gender" name="gender">
            <option value="male">ذكر</option>
            <option value="female">أنثى</option>
        </select>
        <br><br>
        <label for="inputField">الخانة الثانية:</label>
        <input type="text" id="inputField" name="inputField">
        <br><br>
        <input type="submit" value="إرسال">
    </form>
</body>
</html>
