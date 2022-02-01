
 # Révision JavaScript
Ce wiki n'a pour but que d'aider les autodidactes francophone a appréhender JavaScript et servir de rappel a ceux qui le connaisse déjà.

JavaScript est la base de la majorité des Librairies et Framework Front-end, dans ce contexte avoir une connaissance complète de JS est important.

N'oubliez pas que la connaissance de l'Anglais est une compétence primordiale dans le monde du développement et de la programmation.

J'ai fait ce wiki car JS est le premier vrai langage qu'un débutant apprend dans sa courbe d’apprentissage, ainsi vous pourrez débuter le développement web sans avoir ce mur de la langue sur votre chemin, mais vous devrez tôt ou tard le franchir aussi bien pour du JavaScript plus approfondi, que pour du Vue, React, Angular et tant d'autres !

## Table des matières
Les titres sont en Anglais puis en Français pour connaitre les termes utilisé partout ailleurs.

 1. [**Introduction**][1]
	 1. [What is JavaScript? | Qu'est-ce que JavaScript ?][1.1]
	 2. [Console][1.2]
	 3. [Comments | Commentaires][1.3]
	 4. [Data Types | Types de données][1.4]
	 5. [Arithmetic Operators | Opérateurs arithmétiques][1.5]
	 6. [String Concatenation | Concaténation de chaînes de caractères][1.6]
	 7. [Properties | Propriétés][1.7]
	 8. [Methods | Méthodes][1.8]
	 9. [Built-in Objects | Objets intégrés][1.9]
	 10. [Review][R1] 
 2. [**Variable**][2]
	1. [Create a Variable: var | Créer une variable : var][2.1]
	2. [Create a variable: let | Créer une variable : let][2.2]
	3. [Create a Variable: const | Crear una variable: const][2.3]
	4. [Mathematical Assignment Operators | Opérateurs d'assignation mathématiques][2.4]
	5. [The Increment and Decrement Operator | L'opérateur d'incrémentation et de décrémentation][2.5]
	6. [String Concatenation with Variables | Concaténation de chaînes de caractères avec des variables][2.6]
	7. [String Interpolation | Interpolation des chaînes de caractères][2.7]
	8. [typeof operator | opérateur typeof][2.8]
	9. [Review][R2] 
 3. [**Conditional Statements | Déclarations conditionnelles**][3]
	1. [Truthy and Falsy Assignment | Affectation de Truthy et Falsy][3.1]
	2. [Ternary operator | Opérateur ternaire][3.2]
	3. [The switch keyword | Le mot clé switch][3.3]
	4. [Review][R3]
 4. [**Function | Fonctions**][4]
	1. [Que sont les fonctions ?][4.1]
	2. [Function Declarations | Déclarations de fonctions][4.2]
	3. [Calling a function | Appeler une fonction][4.3]
	4. [Parameters and arguments | Paramètres et arguments][4.4]
	5. [Default parameters | Paramètres par défaut][4.5]
	6. [Return][4.6]
	7. [Helpers functions | Fonctions d'aide][4.7]
	8. [Function Expressions | Expressions de fonctions][4.8]
	9. [Arrow Functions | Fonctions fléchées][4.9]
	10. [Concise Body Arrow Functions | Fonctions Fléchées Concises][4.10] 
	11. [Review][R4]
5. [**Scope | Portée**][5]
	1. [Blocks and Scope | Blocs et champ d'application][5.1]
	2. [Global Scope | Portée Globale][5.2]
	3. [Block Scope | Portée locale][5.3]
	4. [Scope Pollution | Pollution de portée][5.4]
	5. [Practice Good Scoping | Pratiquer un bon scoping][5.5]
	6. [Review][R5]
6. [**Arrays | Tableaux**][6]
	1. [Create an Array | Créer un tableau][6.1]
	2. [Accessing Elements | Accès aux éléments][6.2]
	3. [Update Elements | Mise à jour des éléments][6.3]
	4. [Arrays with let and const | Tableaux avec let et const][6.4]
	5. [The .length property | La propriété .length][6.5]
	6. [The .push() Method | La méthode .push()][6.6]
	7. [The .pop() Method | La méthode .pop()][6.7]
	8. [More Array Methods | Plus de méthodes de tableaux][6.8]
	9. [Arrays and Functions | Tableaux et fonctions][6.9]
	10. [Nested Arrays | Tableaux imbriqués][6.10]
	11. [Review][R6]
	 

_Documentations Traduite en Français depuis la version gratuite du cours 'Learn Javascript' de [Codecademy.com][CC]_

[1]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/1.-Introduction
[1.1]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/1.-Introduction#11-what-is-javascript--quest-ce-que-javascript-
[1.2]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/1.-Introduction#12-console
[1.3]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/1.-Introduction#13-comments--commentaires
[1.4]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/1.-Introduction#14-data-types--types-de-donn%C3%A9es
[1.5]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/1.-Introduction#15-arithmetic-operators--op%C3%A9rateurs-arithm%C3%A9tiques
[1.6]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/1.-Introduction#16-string-concatenation--concat%C3%A9nation-de-cha%C3%AEnes-de-caract%C3%A8res
[1.7]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/1.-Introduction#17-properties--propri%C3%A9t%C3%A9s
[1.8]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/1.-Introduction#18-methods--m%C3%A9thodes
[1.9]:https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/1.-Introduction#19-built-in-objects--objets-int%C3%A9gr%C3%A9s
[R1]:https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/1.-Introduction#review
[2]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/2.-Variable
[2.1]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/2.-Variable#21-create-a-variable-var--cr%C3%A9er-une-variable--var
[2.2]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/2.-Variable#22-create-a-variable-let--cr%C3%A9er-une-variable--let
[2.3]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/2.-Variable#23-create-a-variable-const--crear-una-variable-const
[2.4]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/2.-Variable#24-mathematical-assignment-operators--op%C3%A9rateurs-dassignation-math%C3%A9matiques
[2.5]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/2.-Variable#25-the-increment-and-decrement-operator--lop%C3%A9rateur-dincr%C3%A9mentation-et-de-d%C3%A9cr%C3%A9mentation
[2.6]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/2.-Variable#26-string-concatenation-with-variables--concat%C3%A9nation-de-cha%C3%AEnes-de-caract%C3%A8res-avec-des-variables
[2.7]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/2.-Variable#27-string-interpolation--interpolation-des-cha%C3%AEnes-de-caract%C3%A8res
[2.8]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/2.-Variable#28-typeof-operator--op%C3%A9rateur-typeof
[R2]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/2.-Variable#review
[3]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/3.-Conditional-Statements-%7C-D%C3%A9clarations-conditionnelles
[3.1]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/3.-Conditional-Statements-%7C-D%C3%A9clarations-conditionnelles#3-1-truthy-and-falsy-assignment--affectation-de-truthy-et-falsy
[3.2]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/3.-Conditional-Statements-%7C-D%C3%A9clarations-conditionnelles#32-ternary-operator--op%C3%A9rateur-ternaire
[3.3]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/3.-Conditional-Statements-%7C-D%C3%A9clarations-conditionnelles#33-the-switch-keyword--le-mot-cl%C3%A9-switch
[R3]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/3.-Conditional-Statements-%7C-D%C3%A9clarations-conditionnelles#review
[4]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/4.-Function-%7C-Fonction
[4.1]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/4.-Function-%7C-Fonction#41-que-sont-les-fonctions-
[4.2]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/4.-Function-%7C-Fonction#42-function-declarations--d%C3%A9clarations-de-fonctions
[4.3]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/4.-Function-%7C-Fonction#43-calling-a-function--appeler-une-fonction
[4.4]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/4.-Function-%7C-Fonction#44-parameters-and-arguments--param%C3%A8tres-et-arguments
[4.5]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/4.-Function-%7C-Fonction#45-default-parameters--param%C3%A8tres-par-d%C3%A9faut
[4.6]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/4.-Function-%7C-Fonction#46-return
[4.7]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/4.-Function-%7C-Fonction#47-helpers-functions--fonctions-daide
[4.8]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/4.-Function-%7C-Fonction#48-function-expressions--expressions-de-fonctions
[4.9]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/4.-Function-%7C-Fonction#49-arrow-functions--fonctions-fl%C3%A9ch%C3%A9es
[4.10]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/4.-Function-|-Fonction#410-concise-body-arrow-functions--fonctions-fléchées-concises
[R4]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/4.-Function-%7C-Fonction#review
[5]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/5.-Scope-%7C-Port%C3%A9e
[5.1]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/5.-Scope-%7C-Port%C3%A9e#51-blocks-and-scope--blocs-et-champ-dapplication
[5.2]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/5.-Scope-%7C-Port%C3%A9e#52-global-scope--port%C3%A9e-globale
[5.3]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/5.-Scope-%7C-Port%C3%A9e#53-block-scope--port%C3%A9e-locale
[5.4]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/5.-Scope-%7C-Port%C3%A9e#54-scope-pollution--pollution-de-port%C3%A9e
[5.5]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/5.-Scope-%7C-Port%C3%A9e#55-practice-good-scoping--pratiquer-un-bon-scoping
[R5]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/5.-Scope-%7C-Port%C3%A9e#review
[6]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/6.-Arrays-%7C-Tableaux
[6.1]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/6.-Arrays-%7C-Tableaux#61-create-an-array--cr%C3%A9er-un-tableau
[6.2]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/6.-Arrays-|-Tableaux#62-accessing-elements--accès-aux-éléments
[6.3]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/6.-Arrays-%7C-Tableaux#63-update-elements--mise-%C3%A0-jour-des-%C3%A9l%C3%A9ments
[6.4]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/6.-Arrays-%7C-Tableaux#64-arrays-with-let-and-const--tableaux-avec-let-et-const
[6.5]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/6.-Arrays-%7C-Tableaux#65-the-length-property--la-propri%C3%A9t%C3%A9-length
[6.6]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/6.-Arrays-%7C-Tableaux#66-the-push-method--la-m%C3%A9thode-push
[6.7]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/6.-Arrays-%7C-Tableaux#67-the-pop-method--la-m%C3%A9thode-pop
[6.8]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/6.-Arrays-%7C-Tableaux#68-more-array-methods--plus-de-m%C3%A9thodes-de-tableaux
[6.9]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/6.-Arrays-%7C-Tableaux#69-arrays-and-functions--tableaux-et-fonctions
[6.10]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/6.-Arrays-%7C-Tableaux#610-nested-arrays--tableaux-imbriqu%C3%A9s
[R6]: https://github.com/Thoms-code/Javascript-Cheatsheet/wiki/6.-Arrays-%7C-Tableaux#review



[CC]: https://www.codecademy.com/
