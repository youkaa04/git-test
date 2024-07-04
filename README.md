<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="Card.css">
    <title>Preview Card</title>
    <style>
        .item{
    border: 1px solid rgb(215, 215, 215);
    background-color: rgb(215, 215, 215);
    width: 100%;
    height: 100%;
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
</head>
<body>
    <div class="container">
        <div class="item">
            <img src="assets/images/Capture.PNG" class="first">
            <h4>Learning</h4>
            <p class="light">Published 21 Dec 2023</p>
            <h1>HTML & CSS foundations</h1>
            <p class="strong">These languages are the backbone of every website, defining structure, content, and presentation.</p>
            <div class="img">
                <img src="assets/images/image-avatar.webp" class="second">
                <strong>Greg Hooper</strong>
            </div>
        </div>
    </div>
</body>
</html>
