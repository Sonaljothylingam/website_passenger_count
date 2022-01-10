# website_passenger_count
creating a website that counts the number of passengers in a train station
the html code:
<html>
    <head>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <h1>People Entered:</h1>
        <h2 id="count-el">0</h2>
        <button id="increment-btn" onclick="increment()">INCREMENT</button>
        <script src="index.js"></script>
    </body>
</html>
the css code:
body{
    background-image: url(ststionpic.jpg);
    background-size: cover;
    font-weight: bold;
    text-align: center;
    font-family: 'Times New Roman', Times, serif;
}
h1{
    color: beige;
    margin-top: 10px;
    margin-bottom: 10px;
}
h2{
    color: beige;
    font-size: 50px;
    margin-top: 0;
    margin-bottom: 20px;
}
button{
    border:none;
    padding-top: 10px;
    padding-bottom: 10px;
    color: red;
    font-weight: bold;
    width: 200px;
    margin-bottom: 5px;
    border-radius: 5px;
}
#increment-btn{
    background:wheat;
}
#save-btn{
    background:green;
}
