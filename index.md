<!DOCTYPE html>
<html>
<head>
	<title>Stephen Yap</title>


	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, minimum-scale=1" />

	<link href="https://fonts.googleapis.com/css2?family=Russo+One&display=swap" rel="stylesheet">

	<link href="https://fonts.googleapis.com/css2?family=Roboto+Mono:wght@500&family=Russo+One&display=swap" rel="stylesheet">

	<link rel="stylesheet" type="text/css" href="default.css">
	<link id="theme-style" rel="stylesheet" type="text/css" href="">
</head>
<body>

	<section class="s1">
		<div class="main-container">
			<div class="greeting-wrapper">
				<h1>Hi, I'm Stephen Yap</h1>
			</div>


			<div class="intro-wrapper">
				<div class="nav-wrapper">

					<!-- Link around dots-wrapper added after tutorial video -->
					<a href="index.html">
						<div class="dots-wrapper">
							<div id="dot-1" class="browser-dot"></div>
							<div id="dot-2" class="browser-dot"></div>
							<div id="dot-3" class="browser-dot"></div>
						</div>
					</a>
					

					<ul id="navigation">
						<li><a href="index.html#contact">Contact</a></li>

					</ul>
				</div>

				<div class="left-column">
					<img id="profile_pic" src="images/baw.jpg">
					<h5 style="text-align: center;line-height: 0;"></h5>					
				</div>

				<div class="right-column">

					<div id="preview-shadow">
						<div id="preview">
							<div id="corner-tl" class="corner"></div>
							<div id="corner-tr" class="corner"></div>
							<h3>What I Do</h3>
							<p>I'm a frontend web developer.</p>
							<div id="corner-br" class="corner"></div>
							<div id="corner-bl" class="corner"></div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>

	<section class="s2">
		<div class="main-container">

			<div class="about-wrapper">
				<div class="about-me">
					<h4>More about me</h4>

					<p>I build new projects just to tickle my brain and love teaching others how they're made.</p>

					<p>While I keep busy teaching courses, I still take interviews in search of a great team & projects that interest me.</p>


					<hr>

					<h4>TOP EXPERTISE</h4>

					<p>Frontend developer with primary focus on React: <a target="_blank" href="">Download Resume</a></p>

					<div id="skills">
						<ul>
							<li>HTML/CSS</li>
							<li>JavaScript</li>
							<li>React</li>
							<li>Python</li>
							<li>Flask</li>
													
						</ul>

						<ul>
							<li>SQL/NoSQL</li>	
							<li>Postgres</li>
							<li>Oracle APEX</li>
							<li>Servoy</li>							
						</ul>

					</div>

				</div>

				
				<div class="social-links">					
					<h3>Find me on Twitter & Youtube</h3>

					<a target="_blank" href="https://www.youtube.com/user/stephenjamesyap">YouTube: @stephenjamesyap</a>
					<br>
					<a target="_blank" href="https://twitter.com/firstxtiansaint">Twitter: @firstxtiansaint</a>
				</div>
			</div>

		</div>
	</section>	

	<section class="s2">
		<div class="main-container">
			<a href=""></a>
			<h3 style="text-align: center;">Get In Touch</h3>

			<form id="contact-form">
				<a name="contact"></a>

				<label>Name</label>
				<input class="input-field" type="text" name="name">

				<label>Subject</label>
				<input class="input-field" type="text" name="subject">

				<label>Email</label>
				<input class="input-field" type="text" name="email">

				<label>Message</label>
				<textarea class="input-field" name="message"></textarea>

				<input id="submit-btn" type="submit" value="Send">
			</form>
		</div>
	</section> 

	<script type="text/javascript" src="script.js"></script>
</body>
</html>
