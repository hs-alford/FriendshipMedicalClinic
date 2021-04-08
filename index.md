<!DOCTYPE HTML>

<html>
	<head>
		<title>Friendship Medical Clinic</title>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no" />
		<link rel="stylesheet" href="assets/css/main.css" />
		<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
		<script src="https://kit.fontawesome.com/42057b5def.js" crossorigin="anonymous"></script>
		<style>
			.heading-1 {
				padding-top: 0px;
				padding-bottom: 0px;
			}
			.heading-1 p{
				font-size: x-large;
			}
			
			/* .grouping {
				display: block;
				overflow: hidden;
				padding-left: 20px;
				padding-right: 20px;
				padding-top: 5px;
				margin-left: 0;
				margin-right: 0;
			}
			
			.feature-list span {
				float: left;
				margin-left: 0;
				padding-left: 0;
			}

			.feature-list section {
				margin-bottom: 1px;
				padding-bottom: 1px;
				padding-top: 50px;
				margin-top: 1px;
				
			} */
			
			#header {
				border-bottom: solid 30px #203e64;
			}

			

			/* .textalert {
				text-align: center;
			} */

			.textalert h3{
				margin-bottom: 3px;
				float: left;
				padding-left: 15em;
				padding-right: 10px;
				text-transform: none;
				font-size:large;
			}

			.textalert p{
				margin-bottom: 3px;
				padding-top: 1em;
				
			}

			/* h2.major {
			position: relative;
			border-top: solid 5px #e7eae8;
			font-size: 1.65em;
			text-align: center;
			margin: 0 0 1.9em 0;
			top: 0.775em;
		}

			

			.major p {
				display: inline-block;
				border-top: solid 2px #e5e5e5;
				color: #777;
				margin: 1.5em 0 0 0;
				padding: 1.5em 0 0 0;
				font-style: normal;
			} */

			.mission p{
				color:#203e64;
				
			}

			.mission h3 {
				color: #203e64;
			}

			.imgcenter {
				display: block;
  				margin-left: auto;
  				margin-right: auto;
  				width: 50%;
			}


			#midline {
  				overflow: hidden;
  				text-align: center;
				padding-bottom: 2%;
			}

			#midline:before,
			#midline:after {
				background-color: rgb(155, 155, 155);
				content: "";
				display: inline-block;
				height: 1px;
				position: relative;
				vertical-align: middle;
				width: 50%;
			}

			#midline:before {
				right: 0.5em;
				margin-left: -50%;
			}

			#midline:after {
				left: 0.5em;
				margin-right: -50%;
			}



			.tile {
				max-width: 100%;
				height: 30em;
				color:#203e64;
				background-color: white;
				position: relative;
			
			}
			.tile h3,
			.tile p {
				position: relative;
				z-index: 2;
				text-align: center;
			}
			.tile .fas {
				font-size: 540px;
				color:#4f88bd;
				position: absolute;
				top: 0;
				right: 0;
				bottom: 0;
				left: 0;
				z-index: 0;
				display: -webkit-box;
				/* Safari */
				display: flex;
				align-items: center;
				justify-content: center;
			}

			#r1 .icon {
				font-size: .8em;
				padding-left: 3em;
				padding-right: 3em;
				text-align: center;
			}
			
			.linktext {
				padding-top: 20px;
				font-size: 1.1em;
				display: block;
				position: relative;
				font-weight: bolder;
				text-align: center;
				color: white;
			}

			.w3-content {
				box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
			}

			.row-2 h3 {
				padding-top: 10px;
				padding-bottom: 5px;
				color:#203e64;
			}

			.row-2 p {
				padding-top:20px;
				color: #203e64;
			}

			.underline {
				border-bottom: solid 5px #b6b6b6;
				margin-left:25em;
				margin-right: 25em;
				opacity: .5;
			}

			.mySlides {display:none}
			.w3-left, .w3-right, .w3-badge {cursor:pointer}
			.w3-badge {height:13px;width:13px;padding:0}

			#r3 .sidebar h4 {
				text-transform: capitalize;
			}

			#r3 h2 {
				text-align: center;
				padding-top: .7em;
			}

			#r3 p {
				padding-top: 1em;
			}

			#r3 h1, h2, h3, h4, p {
				color:#203e64
			}
			/* #r3 img {
				background-color: black;
				height: 100%;
				width: 40%;
				object-fit:contain;
				
			} */

			/* Create an active/current "tab button" class */
			.tab button.active {
			background-color: #4f88bd;
			}

			.sidelinks button {
				display: block;
				width:80%;
				margin-top: 1em;
				margin-bottom: 1em;
			}

			.sidebar {
				margin-top: 14em;
			}

		</style>
	</head>
	<body class="homepage is-preload landing">
		<div id="page-wrapper">

			<!-- Header -->
				<header id="header">
					<div class="logo container">
						<div>
							<h1><span><a href="index.html" id="logo">
								<img src="images/fmclogo.jpg" alt="logo" class="fmclogo" />
							</a></span></h1>
							<!-- <p>Friendship Medical Clinic</p> -->
						</div>
					</div>
					
				</header>
				

				<button onclick="document.getElementById('id01').style.display='block'" class="w3-button w3-teal w3-block w3-round-small">
					<h4 style="font-size: medium;text-transform: capitalize;margin: 0;color:white">
						For Information About <b style="color: black;">COVID-19</b> and Our Policies <b style="color: black;">Please Click Here</b></h4>
				</button>



				  <div id="id01" class="w3-modal">
					<div class="w3-modal-content w3-card-4 w3-animate-opacity">
					  <header class="w3-container w3-teal"> 
						<span onclick="document.getElementById('id01').style.display='none'" 
						class="w3-button w3-display-topright">&times;</span>
						<h2 class="w3-text-white">Modal Header</h2>
					  </header>
					  <div class="w3-container">
						<h3>More intriguing information</h3>
							<p>
								Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas ac quam risus, at tempus
								justo. Sed dictum rutrum massa eu volutpat. Quisque vitae hendrerit sem. Pellentesque lorem felis,
								ultricies a bibendum id, bibendum sit amet nisl. Mauris et lorem quam. Maecenas rutrum imperdiet
								vulputate. Nulla quis nibh ipsum, sed egestas justo. Morbi ut ante mattis orci convallis tempor.
								Etiam a lacus a lacus pharetra porttitor quis accumsan odio. Sed vel euismod nisi. Etiam convallis
								rhoncus dui quis euismod. Maecenas lorem tellus, congue et condimentum ac, ullamcorper non sapien
								vulputate. Nulla quis nibh ipsum, sed egestas justo. Morbi ut ante mattis orci convallis tempor.
								Etiam a lacus a lacus pharetra porttitor quis accumsan odio. Sed vel euismod nisi. Etiam convallis
								rhoncus dui quis euismod. Maecenas lorem tellus, congue et condimentum ac, ullamcorper non sapien.
								Donec sagittis massa et leo semper a scelerisque metus faucibus. Morbi congue mattis mi.
								Phasellus sed nisl vitae risus tristique volutpat. Cras rutrum commodo luctus.
							</p>
							<p>
								Phasellus odio risus, faucibus et viverra vitae, eleifend ac purus. Praesent mattis, enim
								quis hendrerit porttitor, sapien tortor viverra magna, sit amet rhoncus nisl lacus nec arcu.
								Suspendisse laoreet metus ut metus imperdiet interdum aliquam justo tincidunt. Mauris dolor urna,
								fringilla vel malesuada ac, dignissim eu mi. Praesent mollis massa ac nulla pretium pretium.
								Etiam a lacus a lacus pharetra porttitor quis accumsan odio. Sed vel euismod nisi. Etiam convallis
								rhoncus dui quis euismod. Maecenas lorem tellus, congue et condimentum ac, ullamcorper non sapien.
								Donec sagittis massa et leo semper a scelerisque metus faucibus. Morbi congue mattis mi.
								Maecenas tortor mauris, consectetur pellentesque dapibus eget, tincidunt vitae arcu.
								Vestibulum purus augue, tincidunt sit amet iaculis id, porta eu purus.
							</p>
					  </div>
					  <footer class="w3-container w3-teal">
						<p class="w3-text-white">Modal Footer</p>
					  </footer>
					</div>
				  </div>
				</div>
			<!-- Nav -->
				<nav id="nav">
					<ul>
						<li class="current"><a href="index.html">Home</a></li>
						<li>
							<a href="paitentinfo.html">Paitents</a>
						</li>
						<li>
							<a href="about_us.html">Who We Are</a>
							<ul>
								<li><a href="about_us.html">About Us</a></li>
								<li><a href="mission.html">Our Mission</a></li>
								<li><a href="history.html">History</a></li>
								<li><a href="team.html">Meet The Team</a></li>
								<li><a href="the_board.html">Board Members</a></li>
								<li><a href="benefits.html">Why We Benefit Everyone</a></li>
							</ul>
						</li>
						<li>
							<a href="how_to_help.html">Getting Involved</a>
							<ul>
								<li><a href="how_to_help.html">How You Can Help</a></li>
								<li><a href="volunteer.html">Voluenteering</a></li>
								<li><a href="giving.html">Giving</a></li>
							</ul>
						</li>
						<!-- <li><a href="success_stories.html">Success Stories</a></li> -->
						<li><a href="contact.html">Contact Us</a></li>
						<li><a href="donate.html">Donate</a></li>
					</ul>
				</nav>


				<!-- Banner -->

				<section id="banner" style="padding-bottom:10px; margin-bottom:0; height: 40em;;"> <!-- z index was at -1 -->
					<div class="content">
						<div class="bannerleft">
							<h2>Welcome to Friendship Medical Clinic & Pharmacy</h2>
							<p>Serving and Providing Healthcare Services to Horry County, SC Since 1965</p>
							<div style="z-index: 3;">
								<a href="#main" class="button scrolly">Learn More</a>
								
								<a href="#main" class="button scrolly">Donate</a>
							</div>
						</div>
						<div class="bannerright">
							<i class='fas fa-heartbeat' style='font-size:24em;color:#203e64'></i>
						</div>
					</div>
					
				</section>
			<!-- Main -->
			<section id="main" style="background-color: white;"> <!-- zindex was at 0 -->

<!-- ============================================== QUOTE IN BANNER ============================================== -->

					<!-- <div class="container">
						<div class="row-1 w3-card-4 div-wrapper" style="margin-bottom: 7em; margin-top: -10em; z-index: 2;">
							
							<section class="box special" style="padding: 20px 0 0 0; margin: 0; background-color: #414141d0;">
								<div style="padding-bottom: 15px;">
									<h3 style="color:#4f88bd; font-weight:bold; font-style: italic; text-transform: capitalize;
										padding-left: 1em; padding-right: 1em;">
										We believe that by providing direction, education, and support in regards to paitent's health, we help
										improve the paitent's quality of life and enrich the community as a whole.</h3>
									
								</div> 
								
							</section>
						</div>
					</div> -->


<!-- ============================================== CLINIC MISSION ROW ============================================== -->

				<div class="container-fluid">
					<div class="row" style="background-color: white;border-top: solid 45px #203e64;">
						<div class="container">
							<div class="row" style="padding-top: 3em;padding-bottom: 6em;">
								<div class="col-12">
									<div class="content mission tile" style="background-color: white;">
										<section class="box page-content">
											<i class='fas fa-globe' style='color:#4f88bd;opacity: .6;'></i>
											<h3 class="w3-xxlarge" style="color:#203e64;text-align: center;font-weight: bolder;">Our Mission</h3>
												<p class="w3-xlarge" style="font-weight: normal;">
													Friendship Medical Clinic provides free healthcare services and treatment
													for uninsured adults living in Horry County.
												</p>
											
												<h3 class="w3-xxlarge" style="color:#203e64;text-align: center;font-weight: bolder;">Our Goals</h3>
												<p class="w3-xlarge" style="font-weight: normal;">
													Improve health outcomes by providing medical care regardless of the ability to pay for services
													<br><br>
													Promote healthy behaviors
													<br><br>
													Assist with transportation when needed to prevent delays in medical care
												</p>
												
												<!-- <img src="images/stethoscopeicon.png" alt="" style="height: 15em;width: 20%;float: right;"> -->
										</section>
										
									</div>
								</div>
							</div>
						</div>
					</div>
				</div>	

<!-- ============================================== QUICK LINKS ROW ============================================== -->

					<div class="container-fluid">
						<div style="background-color: #203e64;">
							<div class="contianer">
								<div class="row gtr-200" id="r1" style="margin-top:1em;padding-bottom: 6em;">
									<div class="col-12">
		
										<!-- Highlight -->
											<section class="box highlight">
												<ul class="special">
													<li><a href="#" class="icon solid fa-search"><span class="linktext">Paitent Info</span></a></li>
													<li><a href="#" class="icon solid fa-tablet-alt"><span class="linktext">Our Services</span></a></li>
													<li><a href="#" class="icon solid fa-flask"><span class="linktext">Community Work</span></a></li>
													<li><a href="#" class="icon solid fa-cog"><span class="linktext">Contact Us</span></a></li>
												</ul>
												<header>
													<!-- <h2>Quick Links</h2> -->
													<p style="color: white;">If you are looking any of these categories just click the icon</p>
												</header>
												<!-- <p>
													Phasellus quam turpis, feugiat sit amet ornare in, hendrerit in lectus. Praesent semper mod quis eget mi. Etiam eu<br />
													ante risus. Aliquam erat volutpat. Aliquam luctus et mattis lectus amet pulvinar. Nam nec turpis consequat.
												</p> -->
											</section>
											<!-- <div style="border-bottom: solid 5px #b6b6b6;margin-left:15em;margin-right: 15em;opacity: .5;"></div> -->
									</div>
								</div>
							</div>	
						</div>
					</div>	
	
					
<!-- ============================================== HISTORY AND GOALS ROW ============================================== -->
					

				<div class="container-fluid">
					<div class="col-12" style="padding: 5em 7em;">

						<!-- Blog -->
							<section class="box blog" id="r3">
								
								<div>
									<div class="row">
										<div class="col-9 col-12-medium">
											<div class="content">
	
												<!-- Featured Post -->
													<article class="box post">
														<header>
															<h3><a href="#">Here's a really big heading</a></h3>
															<p>With a smaller subtitle that attempts to elaborate</p>
															
														</header>

														<div class="container">

														<div id="history" class="tabcontent">
															<div class="w3-content w3-display-container w3-card-4">
																<img src="images/hands.jpg" style="height: 29em;width: 100%;object-fit: contain;background-color: black">															
															</div>
															<h2>History Of Our Clinic</h2>
															<div class="underline" style="margin-left: 25em;margin-right: 25em;"></div>
															<p>
																Founded in 1965, Friendship Medical Clinic & Pharmacy is the oldest free medical 
																clinic in South Carolina. The roots of 
																Friendship Medical Clinic & Pharmacy extend back to during some of the worst times in the 
																fight for civil rights, but through the foresight of a creative teacher wanting to help students see beyond the 
																color of a person's skin, their project of helping people receive medical care has continued long after their 
																graduation in 1968. Friendship Medical Clinic & Pharmacy turned 50 years old in 2015! 
															</p>
															<a href="" class="button" >Learn More</a>
														</div>
														  
														  <div id="community" class="tabcontent">
															<div class="w3-content w3-display-container w3-card-4">
																<img src="images/CMCMammography.jpg" style="height: 29em;width: 100%;object-fit: contain;background-color: black">															
															</div>
															<h2>Community Outreach</h2>
															<div class="underline"></div>
															<p>
																Conway Medical Center and Conway Medical Center Foundation agreed 16 years ago to 
																partner with Friendship Medical Clinic & Pharmacy in providing health care to low-income 
																residents in Horry County. Without their support the clinic would have great difficulty 
																in securing diagnostic tests and medical procedures as well as maintaining the clinic facility.
																Our many partners make it possible for us to give paitents the care they deserve and do the work 
																we do.
															</p>
															<a href="" class="button" >Learn More</a>
														  </div>
														  
														  <div id="giving" class="tabcontent">
															<div class="w3-content w3-display-container w3-card-4">
																<img  src="images/robynwithpatient-1 copy.jpg" style="height: 29em;width: 100%;object-fit: contain;background-color: black">															
															</div>
															<h2>Giving</h2>
															<div class="underline"></div>
															<p>
																It takes individuals, families, churches, civic groups, businesses, corporations, 
																United Way of Horry County, Grants, Conway Medical Center, Conway Medical Center 
																Foundation and Fundraisers to uphold our mission and maintain such diverse and 
																high-quality medical care services for our patients. Here you can learn more about 
																how you can help or make a donation.
															</p>
															<a href="" class="button" >Learn More</a>
														  </div>
														  <div id="paitent" class="tabcontent">
															<div class="w3-content w3-display-container w3-card-4">
																<img src="images/medicalStudentwithRobyn.jpg" style="height: 29em;width: 100%;object-fit: contain;background-color: black">															
															</div>
															<h2>Paitent Information</h2>
															<p>
																Friendship Medical Clinic & Pharmacy exists to provide a primary medical 
																care home for those who are uninsured and financially unable to get routine 
																medical care. If you are intrested to see if you meet the requirements, get
																applicaiton information, or lean about our services click here.
															</p>
															<a href="" class="button">Learn More</a>
														  </div>
													</article>
	
											</div>
										</div>
										<div class="col-3 col-12-medium">
											<div class="sidebar">
	
												<!-- Archives -->
													<ul class="divided">
														<div class="tab sidelinks">
															<h4><button class="tablinks" onclick="openCity(event, 'history')" id="defaultOpen">Our History</button></h4>							
															<h4><button class="tablinks" onclick="openCity(event, 'community')">Outreach</button></h4>							
															<h4><button class="tablinks" onclick="openCity(event, 'giving')">Giving Back</button></h4>
															<h4><button class="tablinks" onclick="openCity(event, 'paitent')">Our Paitents</button></h4>															
														</div>
													</ul>	
											</div>
										</div>
									</div>
								</div>
							</section>
	
					</div>
				</div>

						
					
		</section>

			<!-- Footer -->
				<footer id="footer" style="background-color:#8d8d8d;">
					<div class="container-fluid">
						<div class="row gtr-200">
							<!-- <div class="col-12"> -->

								<!-- About -->
									<!-- <section>
										<h2 class="major"><span>What's this about?</span></h2>
										<p>
											Suspendisse laoreet metus ut metus imperdiet interdum aliquam justo tincidunt. Mauris dolor urna,
													fringilla vel malesuada ac, dignissim eu mi. Praesent mollis massa ac nulla pretium pretium.
													Maecenas tortor mauris, consectetur pellentesque dapibus eget, tincidunt vitae arcu.
										</p>
									</section> -->

							<!-- </div> -->
							<div class="col-12">

								<!-- Contact -->
									<section>
										<h2 class="major"><span>Get in touch</span></h2>
										<ul class="contact">
											<li><a class="icon brands fa-facebook-f" href="#"><span class="label">Facebook</span></a></li>
											<li><a class="icon brands fa-twitter" href="#"><span class="label">Twitter</span></a></li>
											<li><a class="icon brands fa-instagram" href="#"><span class="label">Instagram</span></a></li>
											<li><a class="icon brands fa-dribbble" href="#"><span class="label">Dribbble</span></a></li>
											<li><a class="icon brands fa-linkedin-in" href="#"><span class="label">LinkedIn</span></a></li>
										</ul>
									</section>

							</div>
						</div>
						<!-- Copyright -->
						<div id="copyright">
							<ul class="menu">
								<li>&copy; Untitled. All rights reserved</li>
							</ul>
						</div>
					</div>					
				</footer>
			
		</div>

		<!-- Scripts -->
		<script>

			/* modal */
			// Get the modal
			var modal = document.getElementById('id01');

			// When the user clicks anywhere outside of the modal, close it
			window.onclick = function(event) {
			if (event.target == modal) {
				modal.style.display = "none";
			}
			}

			function openCity(evt, cityName) {
			var i, tabcontent, tablinks;
			tabcontent = document.getElementsByClassName("tabcontent");
			for (i = 0; i < tabcontent.length; i++) {
				tabcontent[i].style.display = "none";
			}
			tablinks = document.getElementsByClassName("tablinks");
			for (i = 0; i < tablinks.length; i++) {
				tablinks[i].className = tablinks[i].className.replace(" active", "");
			}
			document.getElementById(cityName).style.display = "block";
			evt.currentTarget.className += " active";
			}

			// Get the element with id="defaultOpen" and click on it
			document.getElementById("defaultOpen").click();



			var slideIndex = 1;
			showDivs(slideIndex);
			
			function plusDivs(n) {
			  showDivs(slideIndex += n);
			}
			
			function currentDiv(n) {
			  showDivs(slideIndex = n);
			}
			
			function showDivs(n) {
			  var i;
			  var x = document.getElementsByClassName("mySlides");
			  var dots = document.getElementsByClassName("demo");
			  if (n > x.length) {slideIndex = 1}
			  if (n < 1) {slideIndex = x.length}
			  for (i = 0; i < x.length; i++) {
				x[i].style.display = "none";  
			  }
			  for (i = 0; i < dots.length; i++) {
				dots[i].className = dots[i].className.replace(" w3-white", "");
			  }
			  x[slideIndex-1].style.display = "block";  
			  dots[slideIndex-1].className += " w3-white";
			}
			var myIndex = 0;
			carousel();

			function carousel() {
			var i;
			var x = document.getElementsByClassName("mySlides");
			for (i = 0; i < x.length; i++) {
				x[i].style.display = "none";  
			}
			myIndex++;
			if (myIndex > x.length) {myIndex = 1}    
			x[myIndex-1].style.display = "block";  
			setTimeout(carousel, 8000); // Change image every 2 seconds
}
			</script>
			<script src="assets/js/jquery.min.js"></script>
			<script src="assets/js/jquery.dropotron.min.js"></script>
			<script src="assets/js/jquery.scrolly.min.js"></script>
			<script src="assets/js/browser.min.js"></script>
			<script src="assets/js/breakpoints.min.js"></script>
			<script src="assets/js/util.js"></script>
			<script src="assets/js/main.js"></script>

	</body>
</html>

