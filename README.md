- š Hi, Iām @AXIWAR-STUDIOS
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
AXIWAR-STUDIOS/AXIWAR-STUDIOS is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html>
  <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
  <head>
    <title>AXIWAR STUDIOS</title>
    <link rel="icon" type="image/x-icon" href="LOGOAXIWARSTUDIOS2.png" />
    <style>
      form{margin-top:20px;}
      #boutoninscription {
    font-size: 15px;
    height: 20px;
    width: 100px;
    display: block;
    background-color: red;
    margin-left: 1400px;
}
#utilisateur {
  font-size: 15px;
  height: 20px;
  width: 100px;
  display: block;
  margin-left: 1400px;
  margin-top: -505px;
}
#Bug {
  margin-left: 1370px;
  margin-bottom: 1000px;
}
#logoaxiwarstudios {
  height: 500px;
  width: 800px;
  margin-top: 0px;
  margin-left: 355px;
}
#boutonconnexion {
    font-size: 15px;
    height: 20px;
    width: 100px;
    display: block;
    background-color: blue;
    margin-left: 1400px;
    }
    h1 {
      color: lightblue;
      background-color: black;
    }
    </style>
    </head>
    <body>
    <h1><center>Bienvenue sur le site officiel d'AXIWAR STUDIOS<center></h1>
    <input type="button" id="boutoninscription" onclick="inscriptionUtilisateur()" value="s'inscrire"/>
    <input type="button" id="boutonconnexion" onclick="connexionUtilisateur()" value="se connecter"/>
    <img src="AXIWARSTUDIOS3.png" id="logoaxiwarstudios" alt="survolimageaxiwarstudios" title="Logo AXIWAR STUDIOS">
    <input type="button" id="utilisateur" onclick="utilisateurInformation()" value= "utilisateur" />
   <script>
	window.addEventListener('load',false);
  var MotDePasseAdministrateur = "axiwarstudioslabase";
  var NomDutilisateurAdministrateur = "AXIWAR STUDIOS";
  var MDPU;
  var MDPU1;
  var MDPU2;
	window.addEventListener('click',"boutonconnexion",false);
	window.addEventListener('click',"boutoninscription",false);
  window.addEventListener('click',"utilisateur",false);
  window.addEventListener('mouseover',"logoaxiwarstudios",false);
function connexionUtilisateur(){
	var MDPU3 = prompt("veuillez saisir votre nom d'utilisateur :");
	MDPU1 = prompt("veuillez saisir votre mot de passe "); 
  if (MDPU3 === NomDutilisateurAdministrateur && MDPU1 === MotDePasseAdministrateur) {
    alert("BIENVENUE ADMINISTRATEUR "+ MDPU3 + " !");
  }
  else {
      if (MDPU3 === MDPU  && MDPU2 === MDPU1  ) {
      alert("rebonjour " + MDPU3 + " !");
      }
  }
  }
function inscriptionUtilisateur(){
	MDPU = prompt("veuillez saisir un nom d'utilisateur :");
	MDPU1 = prompt("veuillez saisir un mot de passe :");
	MDPU2 = prompt("veuillez confirmer votre mot de passe :")
	if (MDPU1 === MDPU2) {
		alert("BIENVENUE "+ MDPU + " !");
    MotDePasseUtilisateurs.push(MDPU);
    MotDePasseUtilisateurs.push(MDPU2);
	}
	}
  function utilisateurInformation(){
    document.write("Nom d'utilisateur :" + MDPU)
    document.write(" Mot de passe :" + MDPU2)
  }
  function survolimageaxiwarstudios(){
    document.getElementById("logoaxiwarstudios").style.width: "810px";

  }
</script>
</body>
<a id="Bug" href="mailto:Espacewarshelp@gmail.com?subject=Bug">signaler nous un bug</a>
</html>
