# demo-landingpage
Landing page for the fitness
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
	 <meta name="description" content="Fitness App that grants access to multiple gyms around town">
  <meta name="keywords" content="fitness, group fitness, fitness app, social media fitness, get fit">
  <meta name="author" content="Abi and Lexi">
    <title>Gym Trotter</title>
    
    <link rel="stylesheet" href="../../../landing/landing/css/thimble.min.css">
    <link rel="stylesheet" href="../../../landing/landing/css/styles.css">
	
	<link href="https://fonts.googleapis.com/css?family=Josefin+Sans" rel="stylesheet">
	
	<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">
</head>


<header>
	
	
		
	<div class="container-fluid navhead">
	<div class="row">
	<div class="cell two logo-image"> 
	
      <img src="../../../landing/landing/img/fitness_logo.png" alt="logo"/> </div>	
		
	<div class="cell seven">
		
	<ul class="navbar">
			<a href="#"><li> About </li></a>
			<a href="#"><li> Why Us? </li></a>
			<a href="#"><li> Tesimonials </li></a>
			<a href="#"><li> Pricing </li></a>
				
		</ul>
		
		</div>
	
		<div class="cell one">
			<a href="#" id="login"> Log In </a>
			
		</div>
	<div class="cell two">	
	<a href="#" id="submit_btnh" class="button">Join Gym Trotter</a>
		</div>
	
	</div>
	</div>
	
	
</header>
	
	
<body>

	<div class="container-fluid">
	<div class="row">

	
<!--starting slideshow HTML-->
	<div class="slideshow-container">
  <div class="mySlides fade">
	  <img src="../../../landing/landing/img/fitness_highknees.jpg" alt="friends" style="width: 100%"/>
<div class="textss"><a class="ss" href="#">Refer friends and recieve FREE classes!</a></div>
  </div>


  <div class="mySlides fade">
	  <img src="../../../landing/landing/img/fitness_squats.jpg" alt="promo" style= "width: 100%"/>
    <div class="textss"><a class="ss" href="#">New members get their first 3 classes FREE!</a></div>
  </div>

  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>
		</div>
	</div>
		
	
<!--ending slideshow HTML-->
	
<!--starting slideshow JS script -->
	
	<script> 
		
		var slideIndex = 0;
showSlides();

function showSlides() {
    var i;
    var slides = document.getElementsByClassName("mySlides");
    for (i = 0; i < slides.length; i++) {
        slides[i].style.display = "none"; 
    }
    slideIndex++;
    if (slideIndex > slides.length) {slideIndex = 1} 
    slides[slideIndex-1].style.display = "block"; 
    setTimeout(showSlides, 3000); // Change image every 2 seconds
}
		</script>
	
<!--ending slideshow JS script-->
 

<div class="container-fluid" id="snowflake">
	<div class="row">
		<div class="cell four" id="b1"><a href="#"><p class="box-paragraph">Search trending classes</p></a></div>
		<div class="cell four" id="b2"><a href="#"><p class="box-paragraph">Explore our gyms </p></a></div> 
		<div class="cell four" id="b3"><a href="#"><p class="box-paragraph">Learn about membership</p></a></div> 
	
	</div>
	</div>

<div class="container-fluid about"> 
	<div class="row">
	<div class="cell four left1"> 
	<h3 > What is Gym Trotter? </h3> <br> <hr/>
		
<p> Everyone gets bored with their fitness routines at some point. Gym Trotter makes your fitness experience exciting again. It acts as a passport to gain access to multiple group fitness classes around town. With it you can go to different fitness classes all month long. You can be more engaged and motivated with your workouts. We’re here to help you be your best self.</p>
 </div>
	
	<div class="cell" id="climber"> 
	</div>
		
	</div>

</div>
 
<div class="container-fluid why">
  <div class="row"> 
		
	<div class="cell seven" id="bell"> 
	   </div>	
		
	<div class="cell five right">
	<h3> Why choose Gym Trotter? </h3> <br> <hr/>
	<p>Gym Trotter is the best way to work out. It makes it easier to achieve your goals by efficiently unlocking the classes with the best fitness instructors at the most desirable gyms around town. You will also gain a supportive workout community that will help keep you motivated. <br> <br> <br> 
		


Take your workout to the next level.</p>
		
	<a href="#" id="submit_btn1" class="button">Start Your Free Trial!</a>
		
		
</div>
	
</div>
	
</div>

<div class="container-fluid locations">
	<div class="row"> 
		<div class="cell four left2">
			<h3 class="gym">Gym Locator</h3><br> <hr/> 
			<p> Being a part of the Gym Trotter family gives you access to donzens of the most desirable gyms around town.</p>
		
			
		</div>
		
<div class="cell eight map">

		<a href="#" id="submit_btn" class="button">Show Full Map</a></div>
</div>
</div>
	
	<h3 class="testimonial"> What members have to say:</h3> <br> <hr/>
	

<div class="container-fluid testimonials">
	<div class="row"> 
		
	<div class="cell four test1"><p> I regret not using Gym Trotter sooner. I resisted for 2 years because of the fear of trying something new. It’s great feeding off the energy of others. The results are life changing.</p> <br>
	<p>-Laura, West Seattle</p> 
	<p>Age 36 </p>
		</div>
	

	<div class="cell four test1"><p> I joined Gym Trotter recently and started exercising regularly which makes me happy. Thanks for helping me find great places to workout. </p> <br>
	<p>-Peter, Green Lake</p> <br>
	<p>Age 45 </p>
		</div>

	<div class="cell four test1"><p> First real workout in years and I loved it! Personal coaching feature was amazing and helped me with modify my workout when I was floundering!</p><br>
	<p>-Sara, Capitol Hill</p> <br>
	<p>Age 20 </p>
		</div>
</div>
</div>
	<!-- abi code starts here -->
	
	<h3 class="classprice"> Select the best plan that suits you</h3> <br> <hr/>
	<div class="container-fluid" id="classprice">
	<div class="row">
		<div class="cell three" id="box1"><p class="price-paragraph">5 Classes <br> $60/Month <br> One Visit Any Studio <br> <a href="#" class="price-button"> Select</a> </p>
		</div>
		<div class="cell three" id="box2"><p class="price-paragraph">10 Classes <br> $100/Month <br> Two visit Any studio <br> <a href="#" class="price-button"> Select</a> </p>
			
		</div> 
		<div class="cell three" id="box3"><p class="price-paragraph">20 Classes <br>$180/Month <br> Four Visit Any Studio <br> <a href="#" class="price-button"> Select</a> </p>
			
		</div> 
		<div class="cell three" id="box4"><p class="price-paragraph">Unlimited <br>$250/Month <br> Five Visit Any Studio <br> <a href="#" class="price-button"> Select</a> </p>
			
		</div> 
	
	</div>
	</div>
	
	<!--pricing end -->
	
	<!--Signup section-->

	<div class="container-fluid signupsection">
<div class="row">
<div class="cell twelve signupsection">	
	<h3> Want to know about the best workouts?</h3>
	<h4> Please sign up and we will send you a city guide of our best studios near you.</h4>
	<hr>
	<form action="/action_page.php" style="border:1px solid #ccc">
  <div class="container">
    <label><b>Email</b></label>
    <input type="text" placeholder="Enter Email" name="email" required>

    <label><b>Password</b></label>
    <input type="password" placeholder="Enter Password" name="psw" required>

    <label><b>Repeat Password</b></label>
    <input type="password" placeholder="Repeat Password" name="psw-repeat" required>
    <!--<input type="checkbox" checked="checked"> Remember me -->
    <p>By creating an account you agree to our <a href="#">Terms & Privacy</a>.</p>

    <div class="clearfix">
      <!--<button type="button" class="cancelbtn">Cancel</button>-->
      <button type="submit" class="signupbtn">Sign Up</button>
    </div>
  </div>
</form>

	</div>
	</div>	
	
	</div>
	
<!--Footer section-->	
<footer class="container-fluid">
<div class="row pricing">
<div class="cell three"> <h1> GymTrotter</h1> <h4><a href="http://google.com"> About us </a> </h4> <h4><a href="http://google.com"> Pricing </a> </h4></div>	
<div class="cell three"> <h1> Support</h1> <h4><a href="http://google.com"> Contact </a> <br> <a href="http://google.com">Helpcenter </a> </h4></div>	
<div class="cell three"> <h1> Partners</h1><h4><a href="http://google.com"> Studios </a><br> <a href="http://google.com">Gym Locator</a></h4></div>
<div class="cell three"> <h1> Community</h1><h4><a href="http://google.com"> Blogs </a></h4></div>	
<div class="row">
<div class="cell three">
<span class="footer fitness"> <p>Enjoy fitness on the go </p></span>
<p>
	<!--<a class="footer__downloads--ios" target="_blank" rel="noopener noreferrer" href="https://itunes.apple.com/us/app/GymTrotter/id912947244?mt=8&amp;uo=4"><span>Download GymTrotter for iPhone</span></a> -->
	<a href="http://www.google.com" target="_blank">
	<img src="../../../landing/landing/img/App store.png" alt=""/>
	</a>
	</p>	
<p>
	
	<!--<a class="footer__downloads--android" target="_blank" rel="noopener noreferrer" href="https://play.google.com/store/apps/details?id=com.gymtrotter.gymtrotter"><span>Download GymTrotter for Android</span></a>-->
	</p>
	<a href="http://www.google.com" target="_blank">
	<img src="../../../landing/landing/img/google-play-badge.png" alt=""/>
	</a>
	</div>
<div class="cell nine">	
<ul>
	<li> <i class="fa fa-facebook" aria-hidden="true"></i> </li>
	<li> <i class="fa fa-twitter" aria-hidden="true"></i> </li>
	<li> <i class="fa fa-pinterest" aria-hidden="true"></i> </li>
	<li>  <i class="fa fa-instagram" aria-hidden="true"></i></li>
	
</ul>
	
	</div>	
</div>		
</div>	
</footer> <!--end container-->	
<!-- end abi code --> 

	
</body>
</html>

