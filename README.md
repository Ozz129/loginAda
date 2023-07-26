# loginAda

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .container {
            border: 10px solid #44C3E5;
            padding-top: 20px;
            padding-bottom: 20px;
            padding-left: 20px;
            padding-right: 20px;
        }

        .container-dos{
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        #btnLogin {
            background-color: #44C3E5;
            color: white;
            border: solid;
            padding-top: 5px;
            padding-bottom: 5px;
            font-size: 30%;
        }

        h3 {
            color: #44C3E5;
            text-align: center;
            font: 1em sans-serif;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="container-dos">
            <h3>Login into your account</h3>
            <input type="text" placeholder="Username">
            <input type="text" placeholder="Password">
            <input type="button" value="Login" id="btnLogin">
        </div>
    </div>
</body>
</html>
