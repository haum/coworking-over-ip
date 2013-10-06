:data-transition-duration: 1500
:css: css/coworking.css

----

:id: title

Coworking Over IP
=================

Outils et astuces over IP pour le travail collaboratif
------------------------------------------------------

.. image:: images/title.png

----

Avant de commencer
==================

- Qu'est ce que le **HAUM** ?
- Qu'est ce que la **Ruche Numérique** ?
- *TrollTime* Propriétaire ou libre ?

----

Le HAUM
=======

- Hackerspace de l'Université du Maine
- association de passionné(é)s de *hacking* et d'expérimentations
- par extension, association de technophiles :)
- Site Web : http://haum.org
- Twitter : *@haum72*
- Mailing-list : http://lists.matael.org/mailman/listinfo/haum_hackerspace
- IRC : *#haum@irc.freenode.org*

----

La Ruche Numérique
==================


*TODO*


----

Propriétaire ou Libre ?
=======================

::

    <troll></troll>

.. note::

    - pas de distinction
    - avantage du libre : souvent une communauté et la possibilité de pouvoir adapter l'outil à son besoin
    - propriétaire : produits souvent plus connus du public et des formateurs

----

:data-y: r-1000

Constat
=======

- augmentation du nombre de télétravailleurs
- important besoin de communication avec le reste du monde
- insuffisance des outils standards
- besoin de travailler en même temps sur un même produit...

----

Il existe alors une pléthore d'outils...
========================================

.. note::

    Dans la suite 3 catégories :

    - offline
    - online et bien connus
    - quelques nouveaux

----

:data-rotate-z: 90
:data-scale: 0.75

Depuis des outils très... *old school*...
=========================================

- téléphone
- lettre (oui oui...)
- rencontre IRL (in real life)

.. note::

    - lettre : tend à être remplacée (dans l'administration par ex.)
    - IRL : pas toujours possible


----

:data-y: r-1600

Avec leurs avantages...
-----------------------

- bien connus et maitrisés
- bullet proof
- canaux priviligiés desservant (presque) tout le monde

.. note::

    Attention à ne pas jurer **que** par ça

----

:data-y: r-1600

Et leurs inconvénients.
-----------------------

- pas toujours adaptés à la réalité actuelle
- ne permettent pas (ou peu) le travail collaboratif
- peuvent engendrer des frais (lettres recommandées, etc...)

----

:data-rotate-x: r-180
:data-y: r3200
:data-x: r-700

... à du standard online....
============================

- email
- Skype
- Twitter/Facebook

.. note::

    - email : hyper-répandu... nous y reviendrons
    - Skype : frais possible, pas de multicast vraiment efficace
    - FB/Twitter : malheureusement -> **dangers**

----

:data-y: r-1200

Avec leur bilan
---------------

- bien connus aussi mais souvent mal maîtrisés (ou partiellement)
- permettent l’envoi à plusieurs destinataires
- robustes et plus ou moins éprouvés


.. note::

    pas de traçage possible pour les modifications

----

:data-y: r1200
:data-x: r-700

... voire de l’inconnu
======================

- AdobeConnect (salle de réunion over IP), propriétaire
- Mumble : alternative libre de chat vocal par salon
- Hangout : avec tous les risques inhérents à Google

.. note::

    - Mumble : utilisé beaucoup dans le monde du libre et de l'opensource (pp, frama, lqdn, hackerspaces, etc...)

----

:data-y: r-1200

Avis
----

- méconnus mais puissants
- flexibles et peu couteux
- ...

----

:data-y: r1200
:data-x: r-700

A propos du mail
================

- Créé par la RFC822 en 1982
- joue le rôle électronique de La Poste physique ... avec tous ses travers (et d'autres en plus)

La poste est un intermédiaire de confiance, le mail aussi, mais on ne le connait pas ni ne pouvons le contrôler.

.. note::

    "et plus" : pour envoyer fr->fr, on passe par us....

    - passage par des serveurs tiers sous autre juridiction
    - risque d'interception/ de lecture (SNOWDEN)

    alors, que faire ?

----

:data-x: r-700

Vigilance Constante !!
----------------------

Il est important de :

- Signer ses messages (via PGP/GPG par exemple)
- Chiffrer les données sensibles
- Rester loin des CGU obscures et dangereuses de certains fournisseurs (Google,...)


.. note::

    - signer : intégrité, identité de l'expéfditeur
    - chiffrer : confidentialité

    peu le feront, mais sachez que ça existe et que c'est un plus

----

Enfin, il existe des outils moins courants...
=============================================

... mais tellement utiles !


.. note::

    parfois, il faut détourner un peu...

----

Pourquoi ces nouveaux outils ?
==============================

- Pour répondre à des besoins précis
- Pour adapter au mieux les outils à son travail et non l’inverse
- Pour rester réactif et efficace

Trois exemples pour trois jeux de besoins.

----

Exemple 1 : Besoins
===================

- rédiger en commun des documents
- brainstorming

----

:data-y: r-1200

Exemple 1: EtherPad(Lite)
=========================

- dispo dans de nombreux points du web (Framasoft, divers
- Partis Pirates, autres, ...)
- permet l’export, la création "d’équipes", etc...
- Attention charge maxi variable selon fournisseur
- mais simple à installer sur son propre serveur

Implémentations existantes
--------------------------

- Etherpad : Java (obsolète)
- EtherpadLite : Node.js

.. note::

    30 minutes d'installation pour la version lite (sur serveur Debian)

----

:data-y: r-1200

Et plein de variantes !
=======================

- WriteLaTeX : https://www.writelatex.com/
- stipy : https://stypi.com/
- jsFiddle : http://jsfiddle.net/ (en *alpha*)
- CoVim : https://github.com/FredKSchott/CoVim/ (ohhhhh YEAH !)

.. note::

    stipy : collaborative RT code editor online :) possibilité de le lier à un serveur de run ?
    jsFiddle : collaborative RT code editor spécialisé dans HTML/CSS/JS
    CoVim : Enfin du collab RT pour vim :) -> pair programming

----

:data-y: r1400
:data-x: r-700

Exemple 2 : Besoins
===================

- rédaction de gros documents en collaboratif
- code communautaire
- gestion de projet
- gestion de liste de tâches et attribution

.. note::

    vous êtes dans le numérique après tout :)

    alors pourquoi ne pas utiliser le premier VCS au monde ?
    (GUI existante)

----

:data-y: r-1200

Exemple 2: Serveur Git!
=======================

- Github : payant pour un compte privé
- BitBucket : compte privés/publics gratuit
- Gitolite sur un serveur perso

Possibilités
------------

- un suivi des modifications
- gestion des tickets
- attribution des tâches

.. note::

    et on peut aussi détourner les fonctionnalité de certains fournisseurs pour aller vers de la gestion de projet pure.
    Parlons en ....

----

:data-y: r-1200

Gestion de projet pure ?
========================

- Redmine
- Indefero
- Trac
- PivotalTracker (privé, payant)
- Project Mountain

Autres infos
------------

- Github a une appli Android et des clients Windows et Mac
- Tortoise-git est une appli git pour Windows

----

:data-y: r2400
:data-x: r-700

Exemple 3 : Besoins
===================

- partage de fichiers sur plusieurs machines avec plusieurs personnes
- agenda commun
- serveur perso
- data-parano :)

----

:data-y: r1200

Exemple 3 : OwnCloud
====================

- enfin un cloud libre et privé
- supporté par une vraie communauté
- utilisation sur serveur communautaire ou personnel

.. note::

    Pourquoi pas DropBox ?

    vous faites bien de poser la question !

----

:data-rotate-z: r-90
:id: arnaques

Gare Aux Arnaques
=================


**Avant de choisir définitivement un service, pensez à lire les CGU.**

Des sites peuvent aider :

http://tosdr.org/


----

:data-x: r-1200

Dropbox
=======

Dropbox et autres gardent souvent des droits sur les contenus déposés.

Elles restent malheureusement très utilisées par certaines
entreprises....

----

Google
======

Connu pour ses pratiques douteuses (suppression de compte sans
préavis, statistiques sur les mails, etc...).

Qui plus est, sous juridiction américaine (*PatriotAct*).

.. note::

    on sait aujourd'hui que des personnes sont espionnées

    on sait aussi que le knowledge Graph de google est un outil puissant de recoupement de données...

    ne l'oublions pas.

----

Apple iCloud
============

C’est globalement une mauvaise idée : Apple Inc se réserve un
contrôle total sur les données déposées

----

Mega
====

Tout nouveau sur le marché, Mega peut sembler intéressant, attention à
l’article 8 des CGU...

    8. Our service may automatically delete a piece of data you upload or
    give someone else access to where it determines that that data is an
    exact duplicate of original data already on our service. In that case, you
    will access that original data.

.. note::

    "Notre service est susceptible de détruire automatiquement une partie des données que vous téléverséz ou d'en donner
    accès à un tiers si il détermine que cette donnée et un doublon exact de l'original déjà présent sur notre service.
    Dans ce cas, vous accèderez à cette donnée originale".

----


:data-rotate-x: 180

Remerciements
=============

- La Ruche Numérique et la CCI
- LinuXMaine
- Le HAUM
- Les relecteurs de ces slides et du plan

A VOUS bien sûr !

----

**THE END**
===========
