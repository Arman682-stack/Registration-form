# Registration-form
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Form</title>
</head>

<body>
    <h1>REGISTRATION FORM</h1>
    <form action="/submit-form" method="post">
        <div>
            <label for="username">Name:</label>
            <input type="text" id="username" name="username" placeholder="Enter your username">
        </div>
        <div>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email">
        </div>
        <div>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password">
        </div>
        <div>
            <label>Gender:</label>
            <input type="radio" id="male" name="gender" value="male">
            <label for="male">male</label>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">female</label>
        </div>
        <div>
            <label for="department">Department:</label>
            <input type="text" id="department" name="department" placeholder="Enter your department">
        </div>
        <div>
            <input type="checkbox" id="terms" name="terms" value="accepted">
            <label for="terms">Accept Terms and Conditions:</label>
        </div>
        <button type="submit">submit</button>

    </form>

</body>

</html>
