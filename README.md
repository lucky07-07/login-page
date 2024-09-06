<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login |Lucky</title>
    <link rel="stylesheet" href="bootstrap.css">
    <link rel="stylesheet" href="bootstrap-icons.css">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <link rel="stylesheet" href="form.css">
</head>

<body class="d-flex justify-content-center align-items-center">
    <div class="main">
        <form action="">
            <h1 class="text-center">Register</h1>
            <div class="usertext">
                <input type="text" placeholder="Name" required>
                <i class='bx bx-user' ></i>
            </div>
            <div class="usertext">
                <input type="text" placeholder="Email" required>
                <i class='bx bxs-envelope'></i>
            </div>
            <div class="usertext">
                <input type="password" placeholder="Password" required>
                <i class='bx bxs-lock-alt' ></i>
            </div>

            <div class="checkbox">
                <label> <input type="checkbox">I agree to the terms & conditons</label>
            </div>

            <button class="button bg-white w-100 border-0" type="submit"> Register</button>
            <div class="register text-center">
                <p>already have an account ?
                    <a href="loginform.html" class="text-white text-decoration-none"> Login</a>
                </p>

            </div>
        </form>
    </div>

</body>

</html>
