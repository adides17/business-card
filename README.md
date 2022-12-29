# business-card
/*html code*/
<html>
    <head>
        <link rel="stylesheet" href="businessstyles.css">
    </head>
    <body>
        <div class="card italic">
        <img class="selfclick" src="My image.jpg" alt="Aditya posing for a nice click with diwali decoration in background">
        <div class="info">
        <h1 class="italic">Aditya Deshmukh</h1>
        <p>Frontend Developer</p>
        <h2 class="italic">Pune, Maharashtra</h2>
        </div>
        </div>
    </body>
</html>



/*css code*/

.selfclick {
    width: 150px;
}
.card {
    padding: 20px;
    display: flex;
    justify-content: center;
    width: 400px;
    margin-left: auto;
    margin-right: auto;
    text-align: center;
    border-bottom: 8px solid #64b5f6;
    background: #5e548e;
    color: #fdca40;
}
.info {
    display: inline;
    margin: 20px;
}
.italic {
    font-style: italic;
}
.dotblue {
    border: 1px dotted blue;
}
