Patrice PERRET - CV Online
==========================

Ce CV a été réalisé dans le cadre d'un TP responsive design.

Les technologies utilisées sont html5, css3, jQuery.


##Objectifs


- Présenter mes compétences professionnelles dans le domaine du web
- Optimiser la navigation sur différents supports
- Favoriser l'ergonomie


##Utilisation de jQuery

jQuery a été utilisé de façon très simple, uniquement pour masquer et afficher les blocs en fonctions de la navigation par l'utilisateur.

Exemple :

```html
$( "#bth, #logo" ).click(function() {
	$( "#motivation" ).show( 500 );
	$("#competences, #contact_c, #portfolio, ul#c1, ul#c2, ul#c3, ul#c4, ul#c5").hide();
	$('#menu .active').removeClass('active');
	$("#bth").addClass('active');
});
```


##Responsive design

Le site est optimisé pour trois types de support :

- Desktop : taille supérieure à 961 px
- Tablette : Taille comprise entre 641 px et 960px
- Smartphone : Taille inférieure à 641px



