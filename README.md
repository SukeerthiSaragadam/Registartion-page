# Registartion-page
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Registration Form</title>
        <link rel="stylesheet" href="lo.css">
    </head>
    <body>
        <div class="container">
            <form class="registration-form" action="#" method="POST">
                <h2>Register</h2>
                <div class="form-group">
                    <label for="username">Username</label>
                    <input type="text" id="username" name="username" required>
                </div>
                <div class="form-group">
                    <label for="email">Email</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="password">Password</label>
                    <input type="password" id="password" name="password" required>
                </div>
                <button type="submit">Submit</button>
            </form>
        </div>
    </body>
</html>

#lo.css
body {
display: flex;
justify-content: center;
align-items: center;
height: 100vh;
/*background-image: url(login.jpg);*/
background-size: cover;
}
.container
{
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    max-width: 400px;
    padding:20px;
    background-color: #ffffff;
    box-shadow:0 0 10px rgba(0, 0, 0,0.1);
    border-radius: 10px;
}
.registration-form{
    width:100%;
}
.registration-form h2{
    margin-bottom: 20px;
    text-align: center;
    color:#333;
}
.form-group {
    margin-bottom:15px;
}
.form-group label{
    display:block;
    margin-bottom:5px;
    color:#555;
}
.form-group input{
    width:100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 10px;
}
button{
    width:100%;
    padding:10px;
    background-color: #007bff;
    border:none;
    border-radius:5px;
    color:white;
    font-size:18px;
    cursor:pointer;
    transition: background-color 0.3s;
}
button:hover{
    back-ground-color:#0056b3;
}
@media(max-width:600px){
    .container{
        padding:10px;
    }
    .registrtion-form h2{
        font-size:24px;
    }
    .form-group input{
        font-size:14px;
    }
    button{
        font-size:16px;
    }
    
}
