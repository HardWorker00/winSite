<!DOCTYPE html>
<html>
	<head>
		<meta name="viewport" content="width=device-width, initial-scale=1">
		<meta charset="utf-8">
		<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
		<link rel="stylesheet" type="text/css" href="css/myStyle.css">
		<script type="text/javascript" src="jquery/jquery-3.3.1.min.js"></script>
		<script type="text/javascript" src="js/myJs.js"></script>
		<script type="text/javascript" src="js/bootstrap.min.js"></script>
		<title>acceuil</title>
	</head>
	<body>

		<div class="container-fluid">
			
			<header>
				<nav class="navbar navbar-inverted">
					<div class="navbar-header">
						<a href="" class="navbar-brand logo" >vendci.</a>
					</div>
					<ul class="nav navbar-nav navbar-left ">
						<li><a href="index.html">Accueil</a></li>
						<li><a href="produits.html">Produits</a></li>
						<li>

							<div class="dropdown">
								<button class="btn btn-primary dropdown-toggle" type="button" data-toggle="dropdown">Categories
								<span class="caret"></span></button>
								<ul class="dropdown-menu">
								    <li><a href="vivriers.html">Produits Vivriers</a></li>
								    <div class="divider"></div>
								    <li><a href="industriels.html">Produits Industriel</a></li>
								    <div class="divider"></div>
								</ul>
							</div>
						</li>
						<li><a href="vendeur.html">Espace vendeur</a></li>
					</ul>

					<ul class="nav navbar-nav navbar-right">
						<li>

							<div class="dropdown">
								<button class="btn btn-success dropdown-toggle" type="button" data-toggle="dropdown">Mon Compte
								<span class="caret"></span></button>
								<ul class="dropdown-menu">
								    <li><a href="inscription.html">s'enregistrer</a></li>
								    <div class="divider"></div>
								    <li><a href="connection.html">se connecter</a></li>
								    <div class="divider"></div>
								</ul>
							</div>
						</li>
					</ul>
				</nav>
			</header>

			<section id="carousel">


				<div class="container"> 
					<div id="myCarousel" class="carousel slide" data-ride="carousel">
					    <!-- Indicators -->
					    <ol class="carousel-indicators">
					      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
					      <li data-target="#myCarousel" data-slide-to="1"></li>
					      <li data-target="#myCarousel" data-slide-to="2"></li>
					      <li data-target="#myCarousel" data-slide-to="3"></li>
					      <li data-target="#myCarousel" data-slide-to="4"></li>
					    </ol>

					    <!-- Wrapper for slides -->
					    <div class="carousel-inner">

					      <div class="item active">
					        <img src="images/arrico_vert.png" alt="arrico_vert" style="width:100%;">
					      </div>

					      <div class="item">
					        <img src="images/riz_local.jpg" alt="riz_local" style="width:100%;">
					      </div>
					    
					      <div class="item">
					        <img src="images/manioc-aliment-phare.jpg" alt="manioc-aliment-phare" style="width:100%;">
					      </div>

					      <div class="item">
					        <img src="images/ananas-victoria.jpeg" alt="ananas-victoria" style="width:100%;">
					      </div>

					      <div class="item">
					        <img src="images/cacao_vente.jpg" alt="cacao_vente" style="width:100%;">
					      </div>

					    </div>


					    <!-- Left and right controls -->
					    <a class="left carousel-control" href="#myCarousel" data-slide="prev">
					      <span class="glyphicon glyphicon-chevron-left"></span>
					      <span class="sr-only">Previous</span>
					    </a>
					    <a class="right carousel-control" href="#myCarousel" data-slide="next">
					      <span class="glyphicon glyphicon-chevron-right"></span>
					      <span class="sr-only">Next</span>
					    </a>
					</div>
				</div>
				
			</section>

		</div>

	</body>
</html># winSite
