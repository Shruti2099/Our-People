<!DOCTYPE HTML>
<html lang="8">
<head>
    
    <meta charset="UTF-8">
    <title>Board Members</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="temo.css">
        <script src="https://kit.fontawesome.com/8926df8ee0.js"></script>
    
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700;900&display=swap');
* 
{
    margin:0;
    padding: 0;
    font-family: 'Roboto';
    box-sizing: border-box;
}
body
{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    background: black;
    min-height: 70vh;
}


section
{
  position: relative;
}
.heading{
    position: relative;
    margin-top: 50px;
    font-size: 30px;
    font-family: 'roboto' sans-serif;
    text-align: center;
    color: white;  
}
.heading p{
    position: relative;
    margin-top: 40px;
    font-size: 20px;
    font-family: 'roboto' sans-serif;
    text-align: center;
    color: white; 
}
.section-separator {
	float: left;
	width: 100%;
	position: relative;
	margin: 20px 0;
}
.section-separator:before{
	content: '';
	position: absolute;
	left: 50%;
	top: 0;
	height: 3px;
	width: 50px;
	border-radius: 3px;
	z-index: 2;
	background-color: #fff;
	margin-left: -25px;
}
.lols-2{
     display: flex;
    justify-content: center;
    align-items: center;
}


.container{
    position: relative;
    z-index: 2;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    margin: 40px 0;
}
.container .card{
    position: relative;
    width: 200px;
    height: 350px;
    background: rgba(255,255,255,0.05);
    margin: 20px;
    box-shadow: 0 15px 35px rgba(0,0,0,0.2);
    border-radius: 15px;
    display: flex;
    justify-content: center;
    align-items: center;
    backdrop-filter: blur(10px);  
}
.container .card .content
{
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    opacity: 0.5;
    transition: 0.5s;
}
.container .card:hover .content
{
    opacity: 1;
    transform: translateY(-30px);
}

.container .card .content .imgbx
{
    position: relative;
    width: 150px;
    height: 150px;
    border-radius: 50%;
    overflow: hidden;
    border: 10px solid rgba(0,0,0,0.25);
}
.container .card .content .imgbx img
{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
}
.container .card .content .contentBx h3
{
    color: #fff;
    text-transform: uppercase;
    letter-spacing: 2px;
    font-weight: 500;
    font-size: 18px;
    text-align: center;
    margin: 20px 0 10px;
    line-height: 1.1em;
}
.container .card .content .contentBx h3 span
{
    font-size: 12px;
    font-weight: 300;
    text-transform: initial;
}
.container .card .sci
{
    position: absolute;
    bottom: 50px;
    display: flex;
}

.container .card .sci li
{
    list-style: none;
    margin: 0 10px;
    transform: translateY(40px);
    transition: 0.5s;
    opacity: 0;
    transition-delay: clac(0.1s*var(--i));
}
.container .card:hover .sci li
{
    transform: translateY(0px);
    opacity: 1;
}
.container .card .sci li a 
{
    color: #fff;
    font-size: 24px;
}


      
    </style>

        


    </head>



    <body>  
        

        <section>
            
            <div class="heading">
            <h1>Our People</h1>
            <span class="section-separator"></span>
                <p>“A tech-savvy Board sets a right tone for shaping the culture of innovation.”</p>  
                
           <br>
            
            <div class="heading-right">
                <a class="active" href="bo.html" style="color: white; font-size: 18px; padding: 10px;">Board Of Directors</a>
                <a href="index.html" target="_self" style="color: white; font-size: 18px;">Our People</a>
             </div>
            </div>
            <br>

            <!------------------------------------------------------------------------------------------------------------------------->
            
            <!------------------------------------------------------------------------------------------------------------------------->
            
            <br>
            <div class="container">
                <div class="card" style="width: 20rem;" style="height: 30rem;">
                    <div class="content">
                        <div class="imgbx"><img src="21.jpg"></div>
                        <div class="contentBx">
                            <h3>Chakri<br><span>Chairman</span></h3>
                        </div> 
                    </div>
               <ul class="sci">
                    <li style="--i:1">
                    <a href="#"><i class="fa fa-twitter" aria-hidden="true"></i></a>
                    </li>
                    <li style="--i:2">
                    <a href="#"><i class="fa fa-linkedin" aria-hidden="true"></i></a>
                    </li>     
                </ul>               
                </div>
                <div class="card" style="width: 20rem;" style="height: 30rem;">
                    <div class="content">
                        <div class="imgbx"><img src="21.jpg"></div>
                        <div class="contentBx">
                            <h3>Pranathi<br><span>Partner</span></h3>
                        </div> 
                    </div>
               <ul class="sci">
                   <li style="--i:1">
                    <a href="#"><i class="fa fa-twitter" aria-hidden="true"></i></a>
                    </li>
                    <li style="--i:2">
                    <a href="#"><i class="fa fa-linkedin" aria-hidden="true"></i></a>
                    </li>     
                </ul>               
                </div>
                <div class="card" style="width: 20rem;" style="height: 20rem;">
                    <div class="content">
                        <div class="imgbx"><img src="21.jpg"></div>
                        <div class="contentBx">
                            <h3>Sampath Sahukara<br><span>CEO</span></h3>
                        </div> 
                    </div>
               <ul class="sci">
                   <li style="--i:1">
                    <a href="#"><i class="fa fa-twitter" aria-hidden="true"></i></a>
                    </li>
                    <li style="--i:2">
                    <a href="#"><i class="fa fa-linkedin" aria-hidden="true"></i></a>
                    </li>     
                </ul>               
                </div>
                <div class="card" style="width: 20rem;" style="height: 30rem;">
                    <div class="content">
                        <div class="imgbx"><img src="21.jpg"></div>
                        <div class="contentBx">
                            <h3>Jathin<br><span>Manager</span></h3>
                        </div> 
                    </div>
               <ul class="sci">
                    <li style="--i:1">
                    <a href="#"><i class="fa fa-twitter" aria-hidden="true"></i></a>
                    </li>
                    <li style="--i:2">
                    <a href="#"><i class="fa fa-linkedin" aria-hidden="true"></i></a>
                    </li>     
                </ul>        
                </div>
            </div>
        </section>
        <div style="padding-left:16px">
  <h2>Responsive Topnav Example</h2>
  <p>Resize the browser window to see how it works.</p>
</div>

<script>
function myFunction() {
  var x = document.getElementById("myTopnav");
  if (x.className === "topnav") {
    x.className += " responsive";
  } else {
    x.className = "topnav";
  }
}
</script>

    </body>

    
</html>
