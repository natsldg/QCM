# QCM


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="styesheet" href="qcm.css">
    <title>QCM</title>
</head>
<body>
    <form action="reponset.php" method="post">
        <fieldset class="idclient">
            <label for="nom">Nom : </label>
            <input type="text" id="nom" name="nom"><br>
            <label for="prenom">Prénom : </label>
            <input type="text" id="prenom" name="prenom"><br>
        </fieldset> 

        <fieldset>
            <legend>QCM de 10 questions</legend>
            
            <h4>Question 1 <br>
                Parmis les sigles suivants,
                lequel est un protocole d'internet?</h4>
                <input type="radio" name="1" >
                <label for="html">TCP</label><br>
                <input type="radio" name="1">
                <label for="css">CSS</label><br>
                <input type="radio" name="1" >
                <label for="javascript">POP</label>
                <br><br>

                <h4>Question 2 <br>
                    Un réseau informatique local regroupe des ordinateurs:</h4>
                <input type="radio" name="2">
                <label for="html">qui ont accès à Internet.</label><br>
                <input type="radio" name="2">
                <label for="css">éloignés géographiquement.</label><br>
                <input type="radio" name="2">
                <label for="javascript">reliés au sein d'un même espace restreint.</label>
                <br><br>

                <h4>Question 3 <br>
                    Un réseau informatique étendu est un:
                </h4>
                <input type="radio" name="3" >
                <label for="html">réseau comprenant plusieurs machines.</label><br>
                <input type="radio" name="3" >
                <label for="css">réseau électrique premettant aux ordinateurs de fonctionner.</label><br>
                <input type="radio" id="javascript" name="3">
                <label for="javascript">ensemble de réseaux de machine couvrant
                    une grande zone géographique.
                </label><br><br>

                <h4>Question 4 <br>
                    Un commutateur permet de relier:</h4>
                <input type="radio" name="4" >
                <label for="html">un ordinateur à Internet.</label><br>
                <input type="radio" name="4">
                <label for="css">plusieurs compasants informatiques.</label><br>
                <input type="radio"  name="4" >
                <label for="javascript">un smartphone à un ordinateur.</label>
                <br><br>

                <h4>Question 5 <br>
                    Un routeur permet de relier:</h4>
                <input type="radio" name="5">
                <label for="html">plusieurs composants informatiques.</label><br>
                <input type="radio" name="5">
                <label for="css">un smartphone à un ordinateur.</label><br>
                <input type="radio" name="5">
                <label for="javascript">un ordinateur à internet.</label><br><br>

                <h4>Question 6 <br>
                    Une borne wifi connecte des composants informatiques 
                    au réseau local:</h4>
                <input type="radio" name="6">
                <label for="html">par fibre optique.</label><br>
                <input type="radio" name="6">
                <label for="css">sans fil.</label><br>
                <input type="radio" name="6">
                <label for="javascript">par câble.</label><br><br>

                <h4>Question 7 <br>
                    Les données écha,gées entre deux ordinateurs au sein 
                    d'un réseau local sont:</h4>
                <input type="radio" name="7">
                <label for="html">envoyées par satellite.</label><br>
                <input type="radio" name="7">
                <label for="css">codés sous forme d'une suite de 0 à 1? appelés "bit".</label><br>
                <input type="radio" name="7">
                <label for="javascript">codées de manière à être compréhensibles 
                    uniquement pour le destinataire.</label><br><br>

                 <h4>Question 8 <br>
                    La transmission des informations sur un réseau peut se faire par:</h4>
                <input type="radio" name="8">
                <label for="html">ondes radios.</label><br>
                <input type="radio" name="8">
                <label for="css">clef USB.</label><br>
                <input type="radio" name="8">
                <label for="javascript">télévision.</label><br><br>

                <h4>Question 9 <br>
                    En quoi consiste le routage sur Internet:</h4>
                <input type="radio" name="9">
                <label for="html">construire des routes.</label><br>
                <input type="radio" name="9">
                <label for="css">envoyer des objets par la route.</label><br>
                <input type="radio" name="9">
                <label for="javascript">acheminer des données dans un réseau.</label><br><br>

                <h4>Question 10 <br>
                    Le protocole IP s'exécute:</h4>
                <input type="radio" name="10">
                <label for="html">uniquement sur l'émetteur, 
                    certains routeurs de l'épine dorsale
                    d'Internet et sur le destinataire.</label><br>
                <input type="radio" name="10">
                <label for="css">sur chaque machine rencontrée
                     lors du parcours du paquet IP et en particulier
                     sur les routeurs.</label><br>
                <input type="radio" name="10">
                <label for="javascript">uniquement sur la machine de l'émetteur
                     et du destinataire.
                    </label><br><br>


        <fieldset>
            <legend>Validation</legend>
            <input type ="submit" value="Valider"/>
        </fieldset>
    </form>
</body>
</html>
