<!DOCTYPE html>
<html>
<head>

    <title>FundMyProject</title>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
    
    
    
    <link href="http://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&display=swap" rel="stylesheet" type="text/css">
        <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/css/all.min.css" />
    <link rel="stylesheet" type="text/css" href="http://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.css" />
    <style type="text/css">
        
html{
    height: 100%
}
body{
  width: 100%;
height: 100vh;
    margin: 0;
    padding:0;
    font-family: DM Sans;
    background: #F0F0F0;
    align-items: center;
}
.page{
    display: flex;
   
    margin-left: 10rem;
    padding-right: 2rem;

}
.card{
    margin-top: 7rem;

    
    background: #FFFFFF;
box-shadow: 0px 2.76726px 2.21381px rgba(153, 153, 153, 0.0196802), 0px 6.6501px 5.32008px rgba(153, 153, 153, 0.0282725), 0px 12.5216px 10.0172px rgba(153, 153, 153, 0.035), 0px 22.3363px 17.869px rgba(153, 153, 153, 0.0417275), 0px 41.7776px 33.4221px rgba(153, 153, 153, 0.0503198), 0px 100px 80px rgba(153, 153, 153, 0.07);
border-radius: 11px;
width: 574px;
height: 542px;
display: flex;
flex-direction: column;
padding: 64px 40px;



    

}

.space{
    flex: 0.8;
}
.JANE{
    font-size: 16px;
line-height: 21px;
display: inline-flex;
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
   font-family: DM Sans;
font-style: normal;
font-weight: normal;
font-size: 16px;
line-height: 21px;
width: 131px;
height: 21px;
color: #04172A;

}

input[type=name]{
   width: 492px;
height: 48px;
    border: 2px solid #989898;
box-sizing: border-box;
border-radius: 5px;
padding-left: 0.5rem;
margin-bottom: 2rem;

}


.exp{
    width: 100px;
    height: 30px;
    border: 2px solid #989898;
box-sizing: border-box;
border-radius: 5px;
width: 140px;
height: 48px;
margin-bottom: 2rem;
padding-left: 0.5rem;

}
input[type=submit]{
    background: linear-gradient(270deg, #FB3F5C 0%, #FC657D 80.86%);
box-shadow: 0px 2.76726px 2.21381px rgba(251, 63, 92, 0.0196802), 0px 6.6501px 5.32008px rgba(251, 63, 92, 0.0282725), 0px 12.5216px 10.0172px rgba(251, 63, 92, 0.035), 0px 22.3363px 17.869px rgba(251, 63, 92, 0.0417275), 0px 41.7776px 33.4221px rgba(251, 63, 92, 0.0503198), 0px 100px 80px rgba(251, 63, 92, 0.07);
border-radius: 5px;
    margin-top: 20px;
    transition: 0.2s;
    width: 492px;
height: 48px;
font-family: DM Sans;
font-style: normal;
font-weight: bold;
color: #fff;
width: 492px;
height: 48px;
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
   font-family: DM Sans;
font-style: normal;
font-weight: bold;
font-size: 32px;
line-height: 42px;
/* identical to box height */


color: rgba(0, 0, 0, 0.59);

}
h3{
    font-family: DM Sans;
font-style: normal;
font-weight: bold;
font-size: 32px;
line-height: 42px;
width: 197px;
height: 42px;
}
ins{
    font-weight: bold;
    color: black;
    text-decoration: none;
    font-size: 32px;
line-height: 42px;
}
img{
    width: 64px;
height: 64px;
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


.second_navigation ul{
 list-style: none;
    margin: 0;
    padding-right: 0;
    display: flex;
    padding-right: 10px;
    margin-left: 40rem;
    padding-bottom: 0px;
}
.second_navigation li{
    padding:0 2rem;
    color: red;
    font-weight: bold;
    text-decoration: none;
    font-family: DM Sans;
    font-style: normal;
font-weight: 500;
font-size: 16px;
line-height: 22px;

}
.second_navigation a{
width: 77px;
height: 23px;

font-family: DM Sans;
font-style: normal;
font-weight: 500;
font-size: 16px;
line-height: 22px;
text-decoration: none;
/* identical to box height, or 140% */


color: #04172A;

}

.passive-nav{
    border-bottom: 2px solid #fB3F5C;
    padding-bottom: 5px;
    width: 156px;
height: 3px;


}
.second-nav{
    background: white;
 box-shadow: 0px 4px 11px rgba(150, 150, 150, 0.25);
 margin-top: 0px;
 padding-top: 10px;
 top: 0;
    left: 0;
    width: 100%;
    position: relative;
    background: #FFFFFF;
    height: 32px;
    
    z-index: 800;
}
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


@media screen and (max-width: 850px){


.page{
    display: flex;
    flex-direction: column;
    margin-left: 0px;
    align-self:center; 
    margin-top: 0px;    
}
.card{
    display: flex;
flex-direction: column;
padding: 50px 15px;
width: 354px;
border-radius: 18px;
height: 484px;
margin-bottom: 4rem;
align-self: center;

margin-top: 10px;
}
.text{
    padding-top: 2rem;
    align-items: center;
    padding-left: 3rem;
    

}

ins{
    font-weight: bold;
    color:#fB3F5C;}
body{
    width: 100%;
    align-items: center;
    margin-left: 0px;


}
#body{
    height: 100%;
    align-items: center;
}

.JANE{
color:black;
}
.second-nav{
    display: none;
height: 0px;}
.spaces{
    flex:0.93;
}
input[type=name],
input[type=submit]
{
    width: 314.72px;
height: 48px;
}
.exp{
    width: 89.55px;
height: 48px;
}

.main-body{
    display: flex;
    flex-direction: column;
}
}

@media screen and (max-width: 850px) {
    #side {
        height: 30%;
        background: white;
        box-shadow: 0px 4px 11px rgba(150, 150, 150, 0.25);
        position: fixed;
        top:0;
        right:0;
        width: 100%;
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
        padding-top: 10px;
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
        color:  #fB3F5C;
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
        flex-direction: column-reverse;
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
        margin-top: 10px;
        margin-left: 10px;

    }
   
    
    .ham_line{
        width: 24px;
        height: 4px;
        background: black;

    }
    .ham_lines{
        width: 20px;
        height: 4px;
        background: black;
    }
    .ham_liness{
        width: 16px;
        height: 4px;
        background: black;
    }
    .second-nav{
        display: none;
    }
    
}
@media screen and (max-width: 1200px){
    .page{
    align-items: center;
    display: flex;
    }
    .second_navigation ul{
 list-style: none;
    margin: 0;
    padding-right: 0;
    display: flex;
    padding-right: 10px;
    margin-left: 20rem;
    padding-bottom: 0px
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
        background-color:#2A3A64;
        font-size: 0.75em;
        font-family: sans-serif;
    }

    
    </style>
</head>
<body id="body">
    <header class="toolbar">
       
            <button class="hamburger" id="hamturn" onclick="toggle(); backdrop(); hamturn()">
                <div class="ham_line"></div>
                <div class="ham_lines"></div>
                <div class="ham_liness"></div>
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
                    <li ><a href="#">Main Page</a></li>
                    <li><a href="payment-page.html" class="passive-nav">Payment Details</a></li>
                    <li><a href="#">Confirmation</a></li>
                    
                    
                </ul>
        </nav>
    </div>
    <div class="main-body">

    <div class="page">
        <div class="text">
        <ul><h3>Payment for:</h3>
            <li>
                <img src="https://res.cloudinary.com/devmajor/image/upload/v1592555207/ellipse_197_k991n6.png"><ins class="JANE">Jane Doe</ins><br>laptop purchase
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
            <input type="Submit" name="submit" value="Pay #60,000:00">

        </div>
        
        </form>
    </div>

    </div>
</div>
    
</div>
        
       

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
