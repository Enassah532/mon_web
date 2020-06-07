# mon_web

<!doctype html>
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="fr" lang="fr">
<head>
<title>tourisme dschang</title>
<meta http-equiv="content-type" content="text/html" charset="utf-8"/>
<meta name="author" content="TCHINDA TCHOFO FRANCK HERMAN,TSIDA PARFAIT,HASSANE MOUSTAPHA OUSMANE"/>
<meta name="description" content="Site touristique de presentation des point attractif de la ville de dschang"/>
<meta name="keywords" content="Dschang,tourisme, cite attractif, presentation, cenajes,universite de dschang"/>
<meta name="subject" content="site de presentation de la ville de dschang"/>
<meta name="viewport" content="width=device-width" />
<!--[if lt IE 9]>
<script
src="http://html5shiv.googlecode.com/svn/trunk/html5.js"></script>
<![endif]-->
<link rel="stylesheet" href="style.css"/>
<script>
	myForm.onreset = function() {
	for (var i = 0 ; i < inputsLength ; i++) {
	if (inputs[i].type == 'text' || inputs[i].type ==
	'email') 
	{
		inputs[i].className = '';
	}
	}
	};
</script>
</head>
<body>
<div id="blog_page">
	<header>
		<div id="principal_title">
			<img src="#" alt="logo du site" id="logo"/>
			<h1>TOURISME DSCHANG</h1>
			<h2>Dschang, le tourisme n'a jamais ete aussi facile</h2>
		</div>
		<nav>
			<ul id="menu">
				<li><a href="attraction.html">attractions</a>
					<ul>
					<li><a href="../LE CENAJES/LE CENAJES.html">le cenajes</a></li>
					<li><a href="#">le musee</a></li>
					<li><a href="#">centre climatique</a></li>
					<li><a href="#">l'universite</a></li>
					</ul>
				</li>
				<li><a href="hotels.html">hotels</a>
				</li>
				<li><a href="restaurant.html">restaurant</a>
				</li>
				<li><a href="activites.html">les activites</a>
				</li>
			</ul>
		</nav>
	</header>
	<section>
	<div id="asides">
			<aside id="inscription">
					<h1>ISNSCRIVEZ VOUS AU SITE</h1>
					<h2>pour pouvoir acceder a toutes les pages</h2>
				<form method="POST" action="inscription.php">
					<label for="nom">nom</label> :<input type="text" maxlength="20" placeholder="votre nom" name="nom" id="nom" autofocus required />
					<br/><label for="prenom">prenom </label>:<input type="text" maxlength="20" placeholder="votre prenom" name="prenom"
					id="prenom" required />
					<br/>sexe : <label for="mas">masculin </label><input type="radio" name="sexe" value="m"id="mas" checked />
					<label for="fem">feminin </label><input type="radio" name="sexe"value="f"id="fem"/>
					<br/><label for="email">email :</label><input type="email" name="email" id="email" placeholder="addresse email" required />
					<br/><input type="submit" value="s'inscrire"/>
					<input type="reset" value="annuler"/>
				</form>
			</aside>
			<aside id="images">
			<a href="photos.html"><h1>QUELQUES PHOTOS</h1></a>
			<img src="../images/ds1" width="100" height="100"/>
			<img src="../images/cl2" width="100" height="100"/>
			<img src="../images/mc1" width="100" height="100"/>
			</aside>
		</div>
		<article>
			<div id ="banniere_image">
				<div id="banniere_description">
					<img src= "../images/b.JPEG"  width="100" height="100" alt="b" class="floatan"/>
					invenue sur ce site de presentation de la ville de Dschang
					<a href="#" id="red_botton">voir l'articlele<img src="../images/ds0"/></a>
				</div>	
			</div>
			<p id="after_float">
				Vous avez peut-etre lut plusieurs articles(wikipedia,foreke Dschang.net,bafou.org...)concernant la ville de dschang ou 
				peut-etre pas mais une chose est sur si vous etes sur se site web c'est que vous desirez connaitre la ville de dschang.
				soyez rassure cher visiteur car vous etes sur le bon site.
				en effet Dschang est une ville magnifique, au diverse aspet touristique mais ici nous allons plus nous attarder sur l'aspet des 
				infrastructures. Nous allons donc vous faire une presentation sur <font color="maroon">quatre</font> aspet:
				<ul><font color="teal">
					<li>Les attraction</li>
					<li>Les HOTELS</li>
					<li>Les restaurant</li>
					<li>Les activites</li>
				</font></ul>
			</p>
			Dobord vous devez connaitre l'histoire de la ville de dschang.
			<br/>deja cette ville a ete decouverte par les Allemands en 1895 
			</p>
		</article>
	</section>
	<footer>
		<ul id="footid">
			<li><span class="item">site</span>
				<ul>
					<li><a href="equipe.php">L'equipe</a></li>
					<li><a href="livre_d_or.php">livre d'or et suggestion</a></li>
				</ul>
			</li>
			<li>contact
				<ul>
					<li><a href="#">promouvoir le sites</a></li>
					<li><a href="#">signaler un bug</a></li>
				</ul>
			</li>
			<li>communication
				<ul>
					<li><a href="#">forum</a></li>
					<li><a href="#">recrutement</a></li>
				</ul>
			</li>
			<li>
				<a href="#"><img src="../images/f"width="20" height="20" class="floatan"/>facebook</a>
			</li>	
		</ul>
	</footer>
</div>
</body>
</html>
