<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"></script>


<style type="text/css">
	
			#colo  {
  

  background: linear-gradient(to bottom ,  white, skyblue);
 
 /*mise en forme de la couleur du fond*/
}

#spe  {
  background: Lavender;
}

#gi  {
  background: Cornsilk;
}
		</style>
</head>
<body >

<nav class="navbar navbar-expand-sm bg-dark navbar-dark">
  <!-- Brand -->
  <a class="navbar-brand" href="index.html"><img src="image/cereale.png" alt="Logo" style="width:100px; height=100px;"></a>
  

  <!-- Links -->
  <ul class="navbar-nav">
    <li class="nav-item">
      <a class="nav-link" href="index.html">HOME</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="BartChartIndex.html">Stacked Bart Chart </a>
    </li>
  
   <li class="nav-item">
      <a class="nav-link" href="evolution.html"> Graphe évolutif </a>
    </li>
    
    <!-- Dropdown -->
    <li class="nav-item dropdown">
      <a class="nav-link dropdown-toggle" href="#" id="navbardrop" data-toggle="dropdown">
        Carte Graphique 
      </a>
      <div class="dropdown-menu">
        <a class="dropdown-item" href="importexport.html">Importation - exportation</a>
        <a class="dropdown-item" href="production.html"> Production </a>
      </div>
    </li>
    
    <li class="nav-item">
      <a class="nav-link" href="propos.html"> A propos </a>
    </li>
    
  </ul>
</nav>
<br>
  

  
  
<div id="spe" style="border-radius:  10px;">
  <h3> <mark>Specifications </mark> </h3>
  <p >La demande alimentaire de la population ouest africaine est de plus en plus focalisée sur les
céréales. La consommation céréalière a donc triplé en moins de 30 ans, pendant que la
population a été multipliée par 2,5. Compte tenu des réalités sociales (subsahariennes), nous avons jugé bon d’effectuer nos visualisations sur six (06) céréales qui sont le Riz, le Sorgho, le Fonio, Le Mais, le Mil, le Blé. En plus de cela s’ajoute la période d’observation qui a été réduite sur les dix (10) dernières années en vue d’obtenir une visualisation plus crédible. </p>
</div>
<br>
<br>

<div class= "container-fluid">

<div class="row"  >
<div class="col-md-4" id="spe" style="border-radius:  10px;" >
<marquee id="id1"  direction="up" behavior="alternate" scrollamount="5" height="600" width="244"  style="border:pink 3px SOLID" ><span onmouseover="getElementById('id1').stop();" onmouseout="getElementById('id1').start();"/>
<img src="image/Ble.jpg" class="img-thumbnail" alt="" width="304" height="236"/> 
 <img src="image/Fonio.jpg" class="img-thumbnail" alt="" width="304" height="236"/> 
 <img src="image/Sorgho.jpg" class="img-thumbnail" alt="" width="304" height="236"/> 
 <img src="image/Mil.jpg" class="img-thumbnail" alt="" width="304" height="236"/> 
 <img src="image/Riz.jpg" class="img-thumbnail" alt="" width="304" height="236"/> 
 <img src="image/Mais.jpg" class="img-thumbnail" alt="" width="304" height="236"/> 
</marquee></div>
<div class="col-md-8" id="gi" style="border-radius:  10px;" > 
<ul style="list-style-type:square;">
  <li style="text-align: justify;">Pour les différentes visualisations, utiliser la barre de menu pour y accéder</li><br>
  <li style="text-align: justify;">Nous precisons qu'elles sont toutes dynamiques</li><br>
  <li style="text-align: justify;">Par ailleurs nous précisions que les visualisations portant sur la quantité sont exprimées en tonnes 	et ceux portant sur la valeur en milliers de dollars</li><br>
</ul>
<br>

<img src="gg.gif" class="img-thumbnail" alt="" width="700" height="500" /> 
</div></div>
