# Alikhan
this is my first card project in css
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>card 2</title>
    <style>
          *{
            padding: 0%;
            margin: 0%;
            box-sizing: border-box;
        }
        .container{
            width: 100vw;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: rgb(34,193,195);
background: linear-gradient(0deg, rgba(34,193,195,1) 0%, rgba(70,253,45,0.7287289915966386) 100%);

           
        }
        .card{
            width: 400px;
            height: 600px;
            display: flex;
            align-items: center;
            background-color:white;
            border-radius: 20px;
            flex-direction: column;
            gap: 25px;
            box-shadow: 0 14px 28px rgba(0,0,0,0.25), 0 10px 10px rgba(0,0,0,0.22);
        }
        .card img{
            width: 100%;
            height: 30%;
            border-top-left-radius: 20px;
            border-top-right-radius: 20px;
        }
        .text{
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            gap: 15px;
            width: 75%;
            text-align: center;
        }
        .amountbox{
            width: 80%;
            height: 10%;
            background-color:rgb(244, 244, 106);
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding-right: 20px;
            padding-left: 20px;
        }
        .leftbox{
            height: 100%;
            display: flex;
            gap: 15px;
            align-items: center;
        }
        #Paymentb{
            width: 80%;
            height: 9%;
            background-color: rgb(88, 173, 88);
            border-radius: 10px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);
        }
    .cancel a {
        text-decoration: none;
        color: rgb(80, 73, 73);
        font-weight: bold;
        font-size: large;
    }
   .leftbox img{
    width: 40px;
    height: 40px;
   }
    </style>
</head>
<body>
        <div class="container">
            <div class="card">
                <img src="card2.jpeg" alt="">
                <div class="text">
                    <h2>Order summary </h2>
                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Maxime repellat totam iste, odit ea voluptas? Non unde dolorum placeat veniam?</p>
                </div>
                <div class="amountbox">
                    <div class="leftbox">
                        <div class="img">
                            <img src="sp.png" alt="">
                        </div>
                        <div>
                            <p>Amount</p>
                            <p>$99.9/year</p>
                        </div>

                    </div>
                    <div class="rightbox">
                        <a href="">Change</a>

                    </div>
                </div>
                <button id="Paymentb">
                    Proceed to Payment
                </button>
                <div class="cancel">
                    <a href="#cancelorder">Cancel Order</a>
                </div>
    

            </div>
          
        </div>
</body>
</html>
