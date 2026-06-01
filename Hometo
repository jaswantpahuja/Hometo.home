from flask import Flask
app = Flask(__name__)
@app.route("/")
def home():
    return """

<html>

<head>

<title>Hometo</title>

<style>

body{
    background:orange;
    color:black;
    text-align:center;
    font-family:arial;
    padding-top:40px;
}

button{
    width:260px;
    height:60px;
    margin:10px;
    font-size:20px;
    border-radius:15px;
}

.box{
    margin-top:20px;
    border:2px solid white;
    padding:20px;
    width:80%;
    margin-left:auto;
    margin-right:auto;
    border-radius:20px;
}

a{
    text-decoration:none;
}

</style>

</head>

<body>

<h1>Hometo</h1>

<p>Ghar baithe khao khana </p>

<!-- ROTI -->

<div class="box">

<h2>  Roti Service</h2>

<p>
Sham ko aao rotii kha ke jao.
</p>

<p> 
2 rupees per day<br>
5 rupees per week<br>
21 rupees per month
</p>

<p>
Delivery Time: 3 minutes
</p>

<a
href="https://wa.me/919999336298?text=New%20Order:%20Roti%20service">

<button>Order Now</button>

</a>

</div>

<!-- Raita -->

<div class="box">

<h2> Raita</h2>

<p>
Raita with bondi with special spices
</p>

<p>
price: 2 rupees
</p>

<P>
Delivery Time: 4 minutes
</p>

<a
href="https://wa.me/919999336298?text=New%20Order:%20Raita">

<button>Order Now</button>

</a>

</div>

<!-- Charger -->

<div class="box">

<h2>Charger</h2>

<p>
Phone karo charge its charger
</p>

<p>
Price:1 rupees
</p>

<p>
Delivery Time:1 minute
</p>

<a
href="https://wa.me/919999336298?text=New%20Order:%20Charger">

<button>Order Now</button>

</a>

</div>

<!-- Snacks -->

<div class="box">

<h2>Snacks</h2>s

<p>
jo khana hai vo mangayo.
</p>

<p>
Price: Depends on food
</p>

<p>
Delivery Time: Depends on you
</p>

<a
href="https://wa.me/919999336298?text=New%20Order:%20Snacks">

<button>Order Now</button>

</a>

</div>

</body>

</html>

"""
import os

app.run(
    host="0.0.0.0",
    port=int(os.environ.get("PORT",
5000))
)