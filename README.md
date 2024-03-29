
    

<div id="top"></div>



<!-- PROJECT LOGO -->
<br />
<div align="center">
    <img src="hatim/3.png" alt="Logo" width="800" height="360">
  <h2 align="center">application for class</h2>
  <h3 align="center">dynamic web page using  MVC.</h3>
</div>



<!-- TABLE OF CONTENTS -->
<details>
 <ol class="list-group list-group-numbered">
     <li class="list-group-item"> <a href="#Remerciements">Remerciements </a></li>
     <li class="list-group-item"> <a href="#Introduction">Introduction </a></li>
  <li class="list-group-item"> <a href="#Modélisation">Modélisation</a> </li>
  <li class="list-group-item"> <a href="#Les-outils-de-développement">Les outils de développement</a> </li>
   <li class="list-group-item"> <a href="#Les-interfaces-de-l’application">Les interfaces de l’application</a> </li>
</ol>
</details>

<div id="Remerciements">
  
<!-- ABOUT THE PROJECT -->
## Remerciements
    
Au nom d’Allah le tout miséricordieux,<br />
Tout d’abord, on remercie spécialement, Monsieur le Professeur Mr. AMAMOU AHMED, pour son encadrement, tous ses conseils, ses encouragements, et la confiance qu'il nous a accordée tout au long de la période de ce semestre.

On avait l'honneur d'être encadré au par le Professeur Mr. AMAMOU AHMED et on voudrait le remercier pour le temps qu'il nous a consacré tout au long de ce semestre, sachant répondre à toutes nos interrogations.

Finalement, nos vifs remerciements s'adressent à vous monsieur pour avoir agrée d’évaluer ce travail.


<div id="Introduction">
  
<!-- ABOUT THE PROJECT -->
## Introduction
    
 le but de cette application est offrir aux étudiants la possibilité de **s’inscrire** afin de **visualiser une description de la formation cycle d ingénierie TWM** avec une **description des module**s par semestre. Le compte administrateur doit permettre de **créer** le contenu et le **modifier**. De plus, il doit aussi pouvoir **gérer** les comptes utilisateurs.
    <br />
 un service de **messagerie** interne aux étudiants du TWM (sans utiliser d’API de messagerie) à l’aide duquel les utilisateurs inscrits peuvent: 
    
  * envoyer des messages à leurs contacts
  * créer et gérer les groupes de contacts
  * recevoir et consulter des notifications des messages entrants
  * gérer les messages (recherche et suppression)

    
<div align="center">
    <img src="hatim/4.png" alt="Logo" width="800" height="360">
   <p align="center">Overview of our application.</p>
</div>
    
  
<p align="right">(<a href="#top">back to top</a>)</p>
    

    
<div id="Modélisation">
  
<!-- ABOUT THE PROJECT -->
## Modélisation
    
UML, c’est l’acronyme anglais pour « Unified Modeling Language ». On le traduit par « Langage de modélisation unifié ». La notation UML est un **langage visuel** constitué d’un ensemble de schémas, appelés des **diagrammes**, qui donnent chacun une vision différente du projet à traiter.
UML nous fournit donc des diagrammes pour **représenter** le logiciel à développer : son fonctionnement, sa mise en route, les actions susceptibles d’être effectuées par le logiciel, etc. 
    
UML est une démarche qui se base sur une approche objet. Cette approche s’appuie sur 4 principes fondamentaux. C’est une démarche :
    
  * Itérative et incrémentale.
  * Guidée par les besoins du client et des utilisateurs
  * Centrée sur l’architecture du logiciel
  * Qui décrit les actions et les informations dans une seule entité
    
    Réaliser ces diagrammes revient donc à **modéliser les besoins** et **les solutions fonctionnelles et techniques** de l’application à développer.
    
    
 1. Diagramme de cas d’utilisation.
    
    C’est un diagramme fonctionnel. Il montre les interactions fonctionnelles des acteurs et du système étudié. Il délimite précisément le système, décrit ce que fera le système sans spécifier comment. Il exprime les services (use cases) offert par le système aux utilisateurs (actors).
    
    
   <p align="center">
     <img src="hatim/1.png">
         <p align="center">Diagramme de cas d’utilisation du admin et étudiant.</p>
   </p> 
    
    
 2. Diagramme de cas d’utilisation.
    
    C’est une représentation utilisée dans la phase de conception d’une application pour présenter les classes entités et les différentes relations entre celles-ci.
    
    Une classe est constituée d’un ensemble de fonctions (méthodes) et de données (attributs).
    
    Donc voilà le diagramme de classes qu’on a adopté pour la conception de notre application :

  
   
    
     <p align="center">
     <img src="hatim/2.png">
         <p align="center">Diagramme de classe de l’application.</p>
   </p> 
                   <p align="right">(<a href="#top">back to top</a>)</p> 
     
    

    
   
  
 <div id="Les-outils-de-développement">
  
<!-- ABOUT THE PROJECT -->
## Les outils de développement 
    
Les outils de développement sont les outils nécessaires pour l’environnement de développement de l’application, et de même les différentes techniques web utilisées soient de back end ou de front end.

Parmi les outils de développement qu’on utiliser pour développer notre application sont :
     
    
     


    
     
     
     
   * **java EE**
    </br>
         **Jakarta EE** (anciennement **Java 2 Platform**, **Enterprise Edition**, ou **J2EE** , puis **Java Platform**, **Enterprise Edition ou Java EE**), est une spécification pour la plate-forme **Java d'Oracle**, destinée aux applications d'entreprise.
         
     La plate-forme étend Java Platform, Standard Edition (Java SE) en fournissant une API de mapping objet-relationnel, des architectures distribuées et multitiers, et des services web. La plate-forme se fonde principalement sur des composants modulaires exécutés sur un serveur d'applications.
    
     <p align="center">
     <img src="hatim/5.png">
         <p align="center">Logo de Java EE.</p>
   </p>
   
   * **Wamp** 
    </br>
         **WampServer** est une plateforme de développement Web de type WAMP, permettant de faire fonctionner localement (sans avoir à se connecter à un serveur externe) des scripts **PHP**.
         
WampServer n'est pas en soi un logiciel, mais un environnement Comprenant :

   -	Trois serveurs (Apache, MySQL et MariaDB) .
   -	Un interpréteur de script (PHP).
   -	PhpMyAdmin pour l'administration Web des bases MySQL

</br>
     <p align="center">
     <img src="hatim/6.png">
         <p align="center">Logo du WAMP.</p>
   </p>
   
   
      
   * **HTML**
    </br>
        **L’Hype Text Markup Language**, généralement abrégé HTML, C’est un langage permettant d’écrire r de l’hypertexte, et c’est le langage de balisage conçu pour représenter les pages web
         
    
     <p align="center">
     <img src="hatim/7.png">
         <p align="center">Logo de HTML.</p>
   </p>
   
  * **CSS** 
    </br>
        **Cascading Style Sheets** , les feuilles de style en cascade forment un langage informatique qui  décrit   la   présentation   des   documents HTML et XML.  Les standards définissant CSS sont publiés par le World  Wide  Web Consortium (W3C). 
         


</br>
     <p align="center">
     <img src="hatim/8.png">
         <p align="center">Logo du CSS.</p>
   </p>
   
   * **JS** 
    </br>
        **JavaScript** est un langage de programmation de scripts principalement employé dans les pages web interactives mais aussi pour les serveurs. 
         


</br>
     <p align="center">
     <img src="hatim/9.png">
         <p align="center">Logo du JS.</p>
   </p>
   
   
   * **BOOTSTRAP** 
    </br>
**Bootstrap** est une collection d'outils utiles à la création du design (graphisme, animation et interactions avec la page dans le navigateur, etc.) de sites et d'applications web. C'est un ensemble qui contient des codes HTML et CSS, des formulaires, boutons, outils de navigation et autres éléments interactifs, ainsi que des extensions JavaScript en option. C'est l'un des projets les plus populaires.        


</br>
     <p align="center">
     <img src="hatim/10.png">
         <p align="center">Logo de BOOTSTRAP.</p>
   </p>  
   
   * **JQuery** 
    </br>
**jQuery** est une bibliothèque JavaScript libre et multiplateforme créée pour faciliter l'écriture de scripts côté client dans le code HTML des pages web3. La première version est lancée en janvier 2006 par John Resig.        


</br>
     <p align="center">
     <img src="hatim/11.png">
         <p align="center">Logo de JQuery.</p>
   </p>
   
   * **architect entreprise** 
    </br>
    
C’est un logiciel de modélisation et de conception UML, édité par la société australienne Sparx Systems. Couvrant, par ses fonctionnalités, l'ensemble des étapes du cycle de conception d'application, il est l'un des logiciels de conception et de modélisation les plus reconnus.       


</br>
     <p align="center">
     <img src="hatim/12.png">
         <p align="center">Logo d'Entreprise Architect.</p>
   </p>
   
   * **Eclipse IDE** 
    </br>
Outils pour les développeurs Java créant des applications Java EE et Web, y compris un IDE Java, des outils pour Java EE et JSF, Mylyn et autres.       


</br>
     <p align="center">
     <img src="hatim/13.png">
         <p align="center">Logo d'Eclipse IDE.</p>
   </p>
                            
   
   
   
   
   <div id="Les-interfaces-de-l’application">
  
<!-- ABOUT THE PROJECT -->
## Les interfaces de l’application 
    
   
     
    
   
    
   avant d'accéder a notre application on une page d'accueil.
    </br>
     <p align="center">
     <img src="hatim/3.png">
         <p align="center">page d'accueil.</p>
   </p>
   un utilisateur de notre application et un étudiant et il doit avoir un compte et etre enregistré avant d'accéder à l'application ,il y'a  deux type de compte:
   
   * **admin(qui sont nous)** .
   * **étudiant**.
   
   tout d'abord on l'interface pour créer un compte .</br>
    on crée compte admin.
    </br>
     <p align="center">
     <img src="hatim/14.png">
         <p align="center">compte admin.</p>
   </p>
   on crée deux compte pour étudiant.
   </br>
     <p align="center">
     <img src="hatim/22.png">
         <p align="center">compte souhaila.</p>
   </p>
   </br>
     <p align="center">
     <img src="hatim/23.png">
         <p align="center">compte amin.</p>
   </p>
   
   maintenant on passe au login.
   1. **admin**
   </br>
     <p align="center">
     <img src="hatim/15.png">
         <p align="center">login admin.</p>
   </p>
   quand il click sur log in l'admin accède la page principale de l'application.
   </br>
     <p align="center">
     <img src="hatim/16.png">
         <p align="center">page principale.</p>
   </p>
   comme vous pouvez voir on a une sidebar composée d'une liste de choix et une navbar ou il y'a deux icônes une pour les notification des messages reçus l'autre pour modifer notre profile où pour se déconnecté.
   
   voici l'interface pour modifier son profile.
   </br>
     <p align="center">
     <img src="hatim/17.png">
         <p align="center">interface modifier profile.</p>
   </p>
   si on change nos infos et on click sur edit ils vont etre changer.
     </br>
     <p align="center">
     <img src="hatim/24.png">
         <p align="center">modification.</p>
   </p>
   
   maintenant on passe a l'interface où il ya les étudiants qui sont inscrit.
      </br>
     <p align="center">
     <img src="hatim/18.png">
         <p align="center">interface étudiant.</p>
   </p>
   comme vous pouvez voir l'admin a la possibilité de modifier ou de supprimer un étudiant.
   
   * **modification**  
   quand il click sur l'icône de modifcation une modale va apparaître pour modifier.
     </br>
     <p align="center">
     <img src="hatim/25.png">
         <p align="center">modification étudiant.</p>
   </p>
     </br>
     <p align="center">
     <img src="hatim/26.png">
         <p align="center">test modification.</p>
   </p>
   
  * **suppression** 
  
   si il click sur l'icone de suppression l'etudiant vas etre supprimer 
     </br>
     <p align="center">
     <img src="hatim/27.png">
         <p align="center">suppression.</p>
   
   maintenant on passe a l'interfaces pour la gestion des modules.
        </br>
     <p align="center">
     <img src="hatim/28.png">
         <p align="center">interface modules1.</p>
     </br>
     <p align="center">
     <img src="hatim/29.png">
         <p align="center">interface modules2.</p>
       si l'admin veut ajouter module il click sur add module.   
         </br>
     <p align="center">
     <img src="hatim/30.png">
         <p align="center">ajouter modules.</p>
             </br>
    si il veut modifier un module il sélectionne le module désiré apres une modale apparaît pour editer.
             </br>
     <p align="center">
     <img src="hatim/31.png">
         <p align="center">modifier modules.</p>
         changement des infos du module désiré 
             </br>
     <p align="center">
     <img src="hatim/32.png">
         <p align="center"> modifier modules1.</p>
                </br>
     <p align="center">
     <img src="hatim/33.png">
         <p align="center"> test modifier modules.</p>
       maintenant on passe a la suppression d'un module,quand l'admin click sur delete le module sera supprimé.
         </br>
     <p align="center">
     <img src="hatim/34.png">
         <p align="center">  suppression modules.</p>
         </br>
     <p align="center">
     <img src="hatim/35.png">
         <p align="center"> test suppression modules.</p>
      on fin on passe a la partie qui concerne l'envoie des messages,pour ce test on a ajouter quelque étudiant .
         </br>
     <p align="center">
     <img src="hatim/36.png">
         <p align="center"> interface envoie des messages.</p>
     ily'a deux option  on peux envoyer un message a un étudiant bien défini ou a un groupe d'étudiants </br>
          
     
     
   * **un seul étudiant**    </br>
   quand l'admin veut envoyer le message il click sur la flèche et une modale apparaît . 
   </br> 
     <p align="center">
     <img src="hatim/37.png">
         <p align="center"> envoie des messages.</p>
          </br>
     <p align="center">
     <img src="hatim/38.png">
         <p align="center"> envoie du message avec succès.</p>
         
   * **groupe d'étudiants** </br>
   quand l'admin veut envoyer un message a un groupe d'étudiants il sélectionne  les étudiants a ceux il veut envoyer et le message désiré. 
     </br>
     <p align="center">
     <img src="hatim/39.png">
         <p align="center"> sélection du groupe.</p>
              </br>
     <p align="center">
     <img src="hatim/40.png">
         <p align="center"> envoie du message a un groupe.</p>
      </br>
     <p align="center">
     <img src="hatim/41.png">
         <p align="center"> envoie du message avec succès.</p>
         pour etre sur de l'envoi de vais a l'interface de des messages envoyés.
         </br>
     <p align="center">
     <img src="hatim/42.png">
         <p align="center"> interfaces messages envoyé.</p>
         comme vous voyiez j'ai les messages que j'ai envoyé. </br>
       maintenant si on se déconnecte avec l' admin et on se  connecte avec un étudiant par exemple souhaila et je vais a la partie message reçu.
       </br>
     <p align="center">
     <img src="hatim/43.png">
         <p align="center"> interfaces messages reçus.</p>
      on constate que elle recu deux notif .</br>
      si elle veut répondre elle click sur la fleche du message  a qui elle veut répondre une modale apparaît où elle peut répondre .
      </br>
     <p align="center">
     <img src="hatim/44.png">
         <p align="center"> répondre aux messages reçus.</p>
          quand elle envoie le message un message de succès  apparaît pour indiquer que sa reponse a été bien envoyer  .
          </br>
     <p align="center">
     <img src="hatim/45.png">
         <p align="center"> répondre aux messages reçus avec succès.</p>
          elle aussi l'option de visualiser le message.
          </br>
     <p align="center">
     <img src="hatim/50.png">
         <p align="center"> visualiserle message reçu.</p>
         l'option de la recherche du message( la recherche par n'importe quelle caractère ).
          </br>
     <p align="center">
     <img src="hatim/46.png">
         <p align="center">  recherche du message.</p>
          et aussi l'option de suppression 
          </br>
     <p align="center">
     <img src="hatim/47.png">
         <p align="center"> suppression d'un message reçu.</p> 
         quand on supprime on voie que les notification sont décrémentées.</br>
      maintenant je me déconnecte avec souhaila et je reviens a l'admin et je me rends au message reçu je constate que j'ai eu une notif qu'est la reponse de souhaila .
              </br>
     <p align="center">
     <img src="hatim/48.png">
         <p align="center"> réponse d'un message envoyé.</p> 
         quand je me rend maintenant aux messages envoyés je constate que nos messages on était vu car la bouton seen et on vert. 
         </br>
     <p align="center">
     <img src="hatim/49.png">
         <p align="center"> message vue.</p> 
     
 2. **étudiants** </br>
     pour les interfaces des étudiants sont les mêmes que l'admin sauf que les etudiant n'ont pas d'ajouter ou de modifier ou de supprimer un module ils ont juste la possibilité de voir le module 
     </br>
     <p align="center">
     <img src="hatim/52.png">
         <p align="center"> interface module .</p>
         comme vous voyez il n'a pas le droit de supprimer un module il peut just voir la description on cliquant sur le module.
         </br>
     <p align="center">
     <img src="hatim/53.png">
         <p align="center"> description du module .</p>
        il n' pas aussi la possibilité de modifier.</br>
        et aussi au niveau de l'interface de la visualisation des étudiants il n'a pas le droit ni de modifier ni de supprimer un étudiant.
         </br>
     <p align="center">
     <img src="hatim/51.png">
         <p align="center"> interface des étudiants .</p>
         
 
 
Realiser par - [darkaoui hatim](https://github.com/hatimdeve) 
      </br>


   <p align="right">(<a href="#top">back to top</a>)</p>
