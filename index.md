---
---
<html>
	<head>
		<title>Grace Chinese Lutheran Church</title>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no" />
		<link rel="stylesheet" href="assets/css/main.css" />
		<!--[if lte IE 9]><link rel="stylesheet" href="assets/css/ie9.css" /><![endif]-->
		<noscript><link rel="stylesheet" href="assets/css/noscript.css" /></noscript>
	</head>
	<body>

		<!-- Wrapper -->
			<div id="wrapper">

				<!-- Header -->
					<header id="header">
						<div class="logo">
							<span class="icon" style="font-size:50px">&#x271D;</span>
						</div>
						<div class="content">
							<div class="inner">
								<h1>Grace Chinese Lutheran Church</h1>
								<p>Grace, Glory, God</p>
							</div>
						</div>
						<nav>
							<ul>
								<li><a href="#about">About</a></li>
								<li><a href="#work">Work</a></li>
								<li><a href="#news">News</a></li>
								<li><a href="#contact">Contact</a></li>
								<!--<li><a href="#elements">Elements</a></li>-->
							</ul>
						</nav>
					</header>

				<!-- Main -->
					<div id="main">

						<!-- About -->
							<article id="about">
								<h2 class="major">About</h2>
								<span class="image main"><img src="images/pic01.jpg" alt="" /></span>
								<h3>Mission</h3>
								<p>Led by the Holy Spirit, to gather and worship the triune God.  To grow in faith and obedience to God's Word.  To go and proclaim the Gospel to the world.  For the glory of our heavenly Father.</p>
								<p></p>
								<h3>Team</h3>
								<p>Pastor Jimmy Hao</p>
								<p>Pastor Wendy Cheung</p>
							</article>

						<!-- Work -->
							<article id="work">
								<h2 class="major">Work</h2>
								<span class="image main"><img src="images/pic02.jpg" alt="" /></span>
								<p>Adipiscing magna sed dolor elit. Praesent eleifend dignissim arcu, at eleifend sapien imperdiet ac. Aliquam erat volutpat. Praesent urna nisi, fringila lorem et vehicula lacinia quam. Integer sollicitudin mauris nec lorem luctus ultrices.</p>
								<p>Nullam et orci eu lorem consequat tincidunt vivamus et sagittis libero. Mauris aliquet magna magna sed nunc rhoncus pharetra. Pellentesque condimentum sem. In efficitur ligula tate urna. Maecenas laoreet massa vel lacinia pellentesque lorem ipsum dolor. Nullam et orci eu lorem consequat tincidunt. Vivamus et sagittis libero. Mauris aliquet magna magna sed nunc rhoncus amet feugiat tempus.</p>
							</article>

						<!-- News -->
							<article id="news">
								<h2 class="major">News</h2>
								<span class="image main"><img src="images/pic03.jpg" alt="" /></span>
								<ul class="post-list">
    {% for post in site.posts %}
      <li>
        <div class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</div>
        <div>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title | escape }}</a>
        </div>
      </li>
    {% endfor %}
  </ul>
							</article>

						<!-- Contact -->
							<article id="contact">
								<h2 class="major">Contact</h2>
								<p>Address: 538 NE 127th St. Seattle, WA 98125<br>
								Telephone: (206) 362-1888</p>
								<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1342.044467651188!2d-122.3239315843656!3d47.72152297919243!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x549011417d99d9ed%3A0x2f173776603a2852!2sGrace+Chinese+Lutheran+Church!5e0!3m2!1sen!2sus!4v1518246124534" id="myFrame"></iframe>
								
							</article>
						<!-- Elements -->
							<article id="elements">
								<h2 class="major">Elements</h2>

							</article>

					</div>

				<!-- Footer -->
					<footer id="footer">
						<p class="copyright">&copy; Designed by <a href="https://html5up.net">HTML5 UP</a>.
						Maintained by Paginate.</p>
					</footer>

			</div>

		<!-- BG -->
			<div id="bg"></div>

		<!-- Scripts -->
			<script src="assets/js/jquery.min.js"></script>
			<script src="assets/js/skel.min.js"></script>
			<script src="assets/js/util.js"></script>
			<script src="assets/js/main.js"></script>

	</body>
</html>
