<!DOCTYPE html>
<html>
<head>

    <title>FundMyProject</title>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
    
    <link rel="stylesheet" type="text/css" href="payment-page.css">
    
    <link href="http://fonts.googleapis.com/css?family=Poppins:100,300,400,300italic" rel="stylesheet" type="text/css">
        <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/css/all.min.css" />
    <link rel="stylesheet" type="text/css" href="http://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.css" />
    <style type="text/css">
        
html{
    height: 100%
}
body{
    height: 100%;
    margin: 0;
    padding:0;
    font-family: 'Arial';
    background: #ddd;
}
.page{
    display: flex;
}
.card{
    
    background:#fff;
    margin-top: 6rem;
    padding:3rem 3rem;
    margin-bottom: 4rem;

    

}
#body{

}
.space{
    flex: 0.3;
}
.main{
    display: flex;
    list-style: none;
    padding-left: 0px;
    padding-right: 0px;
}
.spaces{
    flex:1;
    
}

label{
    color:black;
    font-size: 90%;
}
input[type=name]{
    width: 350px;
    height: 30px;
    border: 2px solid grey;
}
.spacer{
    margin-bottom: 10px;
}
.exp{
    width: 100px;
    height: 30px;
    border: 2px solid grey;

}
input[type=submit]{
    width: 360px;
    height: 30px;
    color:white;
    background: #ff0033;
    border:red;
    margin-top: 20px;
    transition: 0.2s;
}
input[type=submit]:hover{
    background: red;

    color: black;
}
.text{
    padding-top: 10rem;
    padding-left: 7rem;

}

.text li{
    padding-bottom: 10px;
    list-style: none;
}
h3{
    padding-bottom: 10px;

}
ins{
    font-weight: bold;
    color: black;
    text-decoration: none;
}
img{
    height:25px;
}

#body.backdrop {
    position: fixed;
    width: 100%;
    height: 100%;
    top:0;
    left:0;
    background: rgba(0,0,0,0.3);
    z-index:500;
}

.toolbar {
    top: 0;
    left: 0;
    width: 100%;
    position: relative;
    background: #FFFFFF;
    height: 118px;
    
    z-index: 800;
}

.toolbar_navigation{
    display: flex;
    align-items: center;
    height: 100%;
    padding: 0 1rem;
    margin-right: 1rem;
}
.toolbar_navigation-items{
    display: flex;
    align-items: center;
    padding-right: 20px;
}
.toolbar_logo {
    margin-left: 2rem;
    color: black;
    font-weight: bold;
    font-size: 150%;
}
.red{
    color: red;
}
.toolbar_logo img:hover{
    transform: scale(1.1);
    transition: all 2s;
}

.toolbar_navigation-items.current {
    text-decoration-line: underline;
    text-decoration-style: 2px solid #71CE47;
    text-decoration-color: #71CE47;
}
.spacer{
    flex: 1;
}
.toolbar_navigation-items a {
    color:black;
    text-decoration: none;
    font-size: 1.0rem;
}
.toolbar_navigation-items ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    padding-right: 10px
}
.toolbar_navigation-items li {
    padding: 0 2rem;
}

.activenav {
    position: relative;
}


.toolbar_navigation-items a:hover,
.toolbar_navigation-items a:active{
    color: #ff0033;}

.signup_button{
    background:#ff0033;
    border-radius: 4px;
    padding: 10px 30px 10px 30px;
}
.signup_button a{
    color: white ;
}
.signup_button a:hover{
    color: white ;
}
.signup_button:hover {
    transform: scale(1.1);
    transition: all 2s;
}
.invest{
    border:2px solid #ff0033;
    color: #ff0033;
    margin-right: 10px;
    padding: 8px 30px;
}
.invest a{
    color: #ff0033;
    font-weight: bold;
}
.invest a:hover{
    color: black;
}
.second-navigation{
    background: white;
}

.second_navigation ul{
 list-style: none;
    margin: 0;
    padding-right: 0;
    display: flex;
    padding-right: 10px;
    margin-left: 40rem;
}
.second_navigation li{
    padding:0 2rem;
    color: red;
    font-weight: bold;

}
.second_navigation a{
    color: black;
}

.passive-nav{
    border-bottom: 2px solid #ff0033;
    padding-bottom: 5px;
}
.second-nav{
    background: white;
 box-shadow: 0px 4px 11px rgba(150, 150, 150, 0.25);
 margin-top: 0px;
 padding-top: 0px;
 }
 .spacee{
   flex: 5;
 }


/* MEDIA QUERIES */


@media screen and (min-width: 850px) {
    #hidden {
        display: none;
    }
    .hamburger{
        display: none;
    }
}

@media screen and (max-width: 850px) {
    #side {
        height: 100%;
        background: white;
        box-shadow: 0px 4px 11px rgba(150, 150, 150, 0.25);
        position: fixed;
        top:0;
        right:0;
        width: 70%;
        max-width: 300px;
        z-index: 200;
        transform: translateX(100%);
        transition: transform 0.8s ease-out;
    } 
    #side.sideactive {
        transform: translateX(0)
    }

    #side ul {
        list-style: none;
        display: flex;
        height: 100%;
        flex-direction: column;
        justify-content: center;  
        align-items: center;
        font-size: 1.0rem;
        font-weight: 400;
        padding-top: 100px;
    } 
    
    #side li{
        margin: 0.8rem 0;
        
    }
    
    #side a{
        color: black;
        text-decoration: none;
    }

    #side .signup_button a{
        color: white;
        text-decoration: none;
    }

    #side a:hover,
    #side a:active {
        color:   #ff0033;
    }

    #side .signup_button a:hover,
    #side .signup_button a:active {
        color:   white
    }

    .toolbar_navigation-items {
        display: none;
    }

    .hamburger{
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        height: 20px;
        width: 24px;
        background: transparent;
        border: none;
        cursor: pointer;
        padding:0;
        box-sizing: border-box;
        z-index:400;
    }
    .hamburger{
        outline: none;
    }
    .invest {
        margin-bottom: 10px;
        
        
    }
    .invest li{
        color: #ff0033;
    }
    .invest a:hover{
        color: black;
    }
    .ham_line{
        width: 24px;
        height: 4px;
        background: black;
    }
    .second-nav{
        display: none;
    }
    
}


/* HAMBURGER ANIMATION */

#hamturn div:nth-child(1) {
    -webkit-animation: outT 0.8s backwards;
    animation: outT 0.8s backwards;
    -webkit-animation-direction: reverse;
    animation-direction: reverse;
}

#hamturn div:nth-child(2) {
    margin: 5px 0;
    -webkit-animation: outM 0.8s backwards;
    animation: outM 0.8s backwards;
    -webkit-animation-direction: reverse;
    animation-direction: reverse;
}

#hamturn div:nth-child(3) {
    -webkit-animation: outBtm 0.8s backwards;
    animation: outBtm 0.8s backwards;
    -webkit-animation-direction: reverse;
    animation-direction: reverse;
}

#hamturn.hamactive div:nth-child(1) {
    -webkit-animation: inT 0.8s forwards;
    animation: inT 0.8s forwards;
}

#hamturn.hamactive div:nth-child(2) {
    -webkit-animation: inM 0.8s forwards;
    animation: inM 0.8s forwards;
}

#hamturn.hamactive div:nth-child(3) {
    -webkit-animation: inBtm 0.8s forwards;
    animation: inBtm 0.8s forwards;
}

@-webkit-keyframes inM {
    50% {
        -webkit-transform: rotate(0deg);
    }
    100% {
        -webkit-transform: rotate(45deg);
    }
}

@keyframes inM {
    50% {
        transform: rotate(0deg);
    }
    100% {
        transform: rotate(45deg);
    }
}

@-webkit-keyframes outM {
    50% {
        -webkit-transform: rotate(0deg);
    }
    100% {
        -webkit-transform: rotate(45deg);
    }
}

@keyframes outM {
    50% {
        transform: rotate(0deg);
    }
    100% {
        transform: rotate(45deg);
    }
}

@-webkit-keyframes inT {
    0% {
        -webkit-transform: translateY(0px) rotate(0deg);
    }
    50% {
        -webkit-transform: translateY(9px) rotate(0deg);
    }
    100% {
        -webkit-transform: translateY(9px) rotate(135deg);
    }
}

@keyframes inT {
    0% {
        transform: translateY(0px) rotate(0deg);
    }
    50% {
        transform: translateY(9px) rotate(0deg);
    }
    100% {
        transform: translateY(9px) rotate(135deg);
    }
}

@-webkit-keyframes outT {
    0% {
        -webkit-transform: translateY(0px) rotate(0deg);
    }
    50% {
        -webkit-transform: translateY(9px) rotate(0deg);
    }
    100% {
        -webkit-transform: translateY(9px) rotate(135deg);
    }
}

@keyframes outT {
    0% {
        transform: translateY(0px) rotate(0deg);
    }
    50% {
        transform: translateY(9px) rotate(0deg);
    }
    100% {
        transform: translateY(9px) rotate(135deg);
    }
}

@-webkit-keyframes inBtm {
    0% {
        -webkit-transform: translateY(0px) rotate(0deg);
    }
    50% {
        -webkit-transform: translateY(-9px) rotate(0deg);
    }
    100% {
        -webkit-transform: translateY(-9px) rotate(135deg);
    }
}

@keyframes inBtm {
    0% {
        transform: translateY(0px) rotate(0deg);
    }
    50% {
        transform: translateY(-9px) rotate(0deg);
    }
    100% {
        transform: translateY(-9px) rotate(135deg);
    }
}

@-webkit-keyframes outBtm {
    0% {
        -webkit-transform: translateY(0px) rotate(0deg);
    }
    50% {
        -webkit-transform: translateY(-9px) rotate(0deg);
    }
    100% {
        -webkit-transform: translateY(-9px) rotate(135deg);
    }
}

@keyframes outBtm {
    0% {
        transform: translateY(0px) rotate(0deg);
    }
    50% {
        transform: translateY(-9px) rotate(0deg);
    }
    100% {
        transform: translateY(-9px) rotate(135deg);
    }
}


*,
    *::before,
    *::after{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    footer{
        background-color:#000033;
        font-size: 0.75em;
        font-family: sans-serif;
    }

    a{
        text-decoration: none;
    }

    ul{
        list-style: none
    }

    h1{
        margin: .7em 0;
        font-size: 1.8rem;
    }

    .footer-top{
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        margin: 0 10em;
        font-size: 1rem;
        line-height: 2em;
        color:#fff;
    }

    .footer-top li a{
        color: #fff;
    }

    .footer-top-color{
        color: #Fff;
    }

    .footer-icons > a > img{
    margin-right: 1em;
    }

    hr{
        border: 2px solid rgba(4, 23, 42, 0.05);
        margin: 1em 12em;
    }

    .footer-bottom{
        display: flex;
        flex-flow: row;
        margin: 1.5em 10em;
        color: #fff;
        font-size: .9rem;
        margin-bottom: 2em;
    }

    .footer-bottom > .footer-bottom-right{
        margin-left: 2em;
        margin-bottom: 1.5em;
        color: white;
    }
.footer-bottom > .footer-bottom-right:hover{
    color:red;
}
    .footer-bottom > .footer-bottom-left{
    margin-right: auto;
    }


    @media (max-width: 760px) {
        .footer-top{
            flex-direction: column;
            align-items: center;
            text-align: center;
            font-size: .6rem;
            margin: auto 0;
        } 
        input[type=name],
        input[type=submit]{
    width: 300px;}

        h1{
            font-size: .8rem;
            margin-bottom: .1em;
        }

        hr{
            margin: 2em 0;
        }

        .footer-bottom, .footer-bottom-left, .footer-bottom-right{
            margin: 0 .5em;
            font-size: .6rem;}
      
.page{
    display: flex;
    flex-direction: column;
}
.text{
    height: 80px;
    padding-top: 10px;
}
h3{
font-size: 100%;    
}
.spaces{
    flex:0.9;
}
.card{
    padding-left: 2rem;
}

    }

    @media (max-width: 1024px) {
        .footer-top{
            font-size: .8rem;
        }
    h1{
        font-size: 1rem;
    }

    hr{
        margin: 2em 0;
    }


    .footer-bottom,  .footer-bottom-left, .footer-bottom-right{
        margin: 0 2.3em;
        font-size: .6rem;
    }

    } 

    </style>
</head>
<body id="body">
    <header class="toolbar">
        <nav class="toolbar_navigation">
            <div></div>
            <div class="toolbar_logo">FundMy<ins class="red">Laptop</ins></div>
            <div class="spacer"></div>
            <div class="toolbar_navigation-items">
                <ul>
                    <li class="activenav"><a href="index.html">Home</a></li>
                    <li><a href="About.html">About us</a></li>
                    <li><a href="Faq.html">Faq</a></li>
                    <li><a href="Facilities.html">Contact us</a></li>
                    
                </ul>
                <div class="invest">
                    <a href="">Invest</a>
                </div>
                <div class="signup_button">
                    <a href="">Get a Loan</a>
                </div>
            </div>
            <button class="hamburger" id="hamturn" onclick="toggle(); backdrop(); hamturn()">
                <div class="ham_line"></div>
                <div class="ham_line"></div>
                <div class="ham_line"></div>
            </button>


        </nav>

        <div class="second-nav">
             <nav class="second_navigation">
            <div class="spacee"></div>
            
                <ul>
                    <li ><a href="#">Main Page</a></li>
                    <li><a href="payment-page.html" class="passive-nav">Payment Details</a></li>
                    <li><a href="#">Confirmation</a></li>
                    
                    
                </ul>
        </nav>
    </div>
    </header>
    <div id="hidden">
        <nav id="side">
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="About.html">About Us</a></li>
                <li><a href="Contact.html">Faq</a></li>
                <li><a href="Facilities.html">Contact Us</a></li>
                
                <div class="invest">
                    <a href="">Invest</a></div>
                    <div class="signup_button">
                    <a href="">Get a Loan</a>
                </div>
            </ul>
        </nav>
    </div>

    <div class="page">
        <div class="text">
        <ul><h3>Payment for:</h3>
            <li>
                <img src="https://res.cloudinary.com/devmajor/image/upload/v1592555207/ellipse_197_k991n6.png"><ins>Jane Doe</ins><br>laptop purchase
            </li>
            <li>as a<ins> Loan</ins></li>
            <li>for <ins>6 months</ins></li>
            <li>at <ins>5% interest rate</ins></li>
        </ul>
    </div>
    <div class="space"></div>
    <div class="card">
        <form>
            <div class="spacer"><label>Cardholder Name:<br> <input type="name" name="name" placeholder="Cardholder Name" required="required"><br></div>
            <div class="spacer"><label>Cardholder Number<br><input type="name" name="number" placeholder="Cardholder Number" required="required"><br></div>
                
        
            <ul class="main">
            <li><label>Expiry Date <br><input type="text" name="date" placeholder="MM/YY" class="exp" required="required"></li><br> <div class="spaces"></div>          <li><label>CVV<br><input type="text" name="number" placeholder="CVV" class="exp" required="required"><br></label></li>
                
            </ul>
            <input type="Submit" name="submit" value="Pay">

        </div>
        
        </form>
    </div>

    </div>
</div>
    <footer>
        <!-- top section----- -->
        <div class="footer-top">
            <div class="footer-top-1">
            <ul>
                <li><h1>FundMy<span class="footer-top-color">Laptop</span></h1></li>
                <li><p>Our Address</p></li>
                <li><p>Plot 1415 Adetokunbo Ademola Street PMb 12724, Victoria island.Lagos Nigeria</p></li>
                <div class="footer-icons">
                    <a href="#"> <img src= "https://res.cloudinary.com/dytnzt4jf/image/upload/v1592431707/Facebook_epztwm.png" alt="facebook icon"></a>
                   <a href="#"> <img src="https://res.cloudinary.com/dytnzt4jf/image/upload/v1592430002/Instagram_rts1mp.png" alt="instagram icon"></a>
                   <a href="#"> <img src= "https://res.cloudinary.com/dytnzt4jf/image/upload/v1592431827/twitter_y2z4io.png" alt="twitter icon"></a>
                </div>

            </ul>
        </div>

        
        <div class="footer-top-2">
            <ul>
                <li><h1>Our Contact</h1></li>
                <li><a href="#">hello.fundmylaptop@Official.com</a></li>
                <li><a href="#">+234 81 555-0120</a></li>
                <li><a href="#">+234 81 555-0129</a></li>
                <li><a href="#">+234 81 555-0121</a></li>
            </ul>
        </div>

        <div class="footer-top-3">
            <ul>
                <li><h1>Invest</h1></li>
                <li><a href="#">Invest your money</a></li>
                <li><a href="#">Invest fee & return rate</a></li>
                <li><a href="#">How to invest</a></li>
            </ul>
        </div>

       
    </div>
            
    <hr>

        <!-- bottom section----- -->
        <div class="footer-bottom">
        <p class="footer-bottom-left">2020 © Copyright All rights reserved</p>
           <a href="#" class="footer-bottom-right">FAQ</a>
           <a href="#" class="footer-bottom-right">Privacy Policy</a>
            <a href="#" class="footer-bottom-right">Terms & Conditions</a>
        </ul>
    </div>
   </footer>
            </body>
</html>
    

</body>
<script type="text/javascript">
    function toggle() {
    var active = document.getElementById('side')
    active.classList.toggle('sideactive')
}

function backdrop() {
    var backdrop = document.getElementById('body')
    backdrop.classList.toggle('backdrop')
}

function hamturn() {
    var hamturn = document.getElementById('hamturn')
    hamturn.classList.toggle('hamactive')
}
</script>
</html>
