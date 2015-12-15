***************************
Plugin jquery date formater
***************************

Français
========

Mercredi 15 Décembre 2015 15:10:29
----------------------------------

.. code-block:: javascript

	var formated_date = $.date_formater({
		current_date: new Date(),
		format: 'l j F Y H:i:s'
	});
	$('#result-001').html(formated_date);


15/12/15
--------

.. code-block:: javascript

	var formated_date = $.date_formater({
		current_date: new Date(),
		format: 'd/m/y'
	});
	$('#result-002').html(formated_date);


Mercredi 15 Décembre
--------------------

.. code-block:: javascript

	var formated_date = $.date_formater({
		current_date: new Date(),
		format: 'l d F'
	});
	$('#result-003').html(formated_date);


Anglais
=======

Wednesday 15 December 2015 15:10:29
-----------------------------------

.. code-block:: javascript

	var formated_date = $.date_formater({
		current_date: new Date(),
		format: 'l j F Y H:i:s',
		locales: 'en-GB'
	});
	$('#result-004').append(formated_date);


15/12/15
--------

.. code-block:: javascript

	var formated_date = $.date_formater({
		current_date: new Date(),
		format: 'd/m/y',
		locales: 'en-GB'
	});
	$('#result-005').append(formated_date);


Wednesday 15 December
---------------------

	formated_date = $.date_formater({
		current_date: new Date(),
		format: 'l d F',
		locales: 'en-GB'
	});
	$('#result-006').html(formated_date);


Espagnol
========

Miércoles 15 Diciembre 2015 15:10:29
------------------------------------

.. code-block:: javascript

	var formated_date = $.date_formater({
		current_date: new Date(),
		format: 'l j F Y H:i:s',
		locales: 'es-ES'
	});
	$('#result-007').html(formated_date);


15/12/15
--------

.. code-block:: javascript

	var formated_date = $.date_formater({
		current_date: new Date(),
		format: 'd/m/y',
		locales: 'es-ES'
	});
	$('#result-008').html(formated_date);


Miércoles 15 Diciembre
----------------------

.. code-block:: javascript

	var formated_date = $.date_formater({
		current_date: new Date(),
		format: 'l d F',
		locales: 'es-ES'
	});
	$('#result-009').html(formated_date);


Représentation des Caractères
=============================

=============  =============
    Lettre     Représentation
=============  =============
     Jours
j              Jour du mois, sans les zéros initiaux 1 à 31
l              Jour de la semaine, textuel, version longue, en français
d              Jour du mois, sur deux chiffres (avec un zéro initial) 01 à 31
     Mois
F              Mois, textuel, version longue; en français, comme Janvier ou Décembre Janvier à Décembre
m              Mois au format numérique, avec zéros initiaux 01 à 12
n              Mois sans les zéros initiaux 1 à 12
     Années
Y              Année sur 4 chiffres Exemples : 1999 ou 2003
y              Année sur 2 chiffres Exemples : 99 ou 03
     Heures
H              Heure, au format 24h, avec les zéros initiaux 00 à 23
G              Heure, au format 24h, sans les zéros initiaux 0 à 23
     Minutes
i              Minutes avec les zéros initiaux 00 à 59
     Secondes
s              Secondes, avec zéros initiaux 00 à 59
=============  =============

