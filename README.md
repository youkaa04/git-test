<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="QRcode.css">
    <style>
        .item{
    border: 1px solid grey;
    background-color: grey;
    width: 500px;
    height: 700px;
}
.container{
    border: 1px solid white;
    background-color: white;
    border-radius: 10px;
    width: 209px;
    height: 400px;
    display: block;
    margin-left: auto;
    margin-right: auto;
    margin: 140px;
}
img{
    width: 199px;
    height: 200px;
    border-radius: 15px;
    padding: 5px;
}
.bold{
    text-align: center;
    font-weight: bold;
    font-size: larger;
    color: black;
}
p{
    font-size: small;
    color: rgb(171, 171, 171);
    text-align: center;
}
@media screen and (max-width:480px) {
    .item{
        width: 100%;
    }
    .container{
        display: block;
        margin-left: auto;
        margin-right: auto;
        width: 80%;
        height: 70%;
        padding: 5px;
    }
    img{
        width: 90%;
        height: 60%;
        display: block;
        margin-left: auto;
        margin-right: auto;
    }
    .bold{
        font-size: x-large;
        text-align: center;
    }
    p{
        font-size: large;
        text-align: center;
        padding:0px 18px;
    }
    
}
    </style>
    <title>QR code</title>
</head>
<body>
    <div class="item">
        <div class="container">
            <img src="image-qr-code.png">
            <p class="bold">Improve your front-end skills by building projects</p>
            <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
        </div>
    </div>
</body>
</html>
"# qr-code-component-main" 
