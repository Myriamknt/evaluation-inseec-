# Évaluation individuelle

## Programmation - Coaching

```
Nom : KANTÉ
Prénom : Myriam-sophie
URL de votre compte Github : https://github.com/Myriamknt
```

## Déroulé et fonctionnement. 

L'évaluation est à faire sur [Typora](https://typora.io/). Les réponses sont à écrire dans les blocks de code. 
Pour la partie Ruby, testez votre code sur [repl.it](https://repl.it/) et copiez le dans les blocks de code prévu à cet effet. 
Une fois fini, pushez votre feuille sur Github, dans un nouveau repository que vous appelerez "evaluation-inseec".
L'évaluation est individuelle et durera 1h30. Elle intègre des notions d'HTML, CSS, Ruby et computer science. 

![alt](https://media.giphy.com/media/26xBBfd0ii1khakpy/giphy.gif)

## Quelques mises en garde.

Je connais très bien ce merveilleux site qu'est Wikipédia. Je vous saurais gré de ne pas me remplir certaines questions avec les définitions de Wikipédia. Accessoirement, je sais aussi faire une recherche Google. Si j'ai un doute, je n'hésiterais pas rechercher "Qu'est-ce qu'une API" et comparer les définitions en tête de recherche avec les votre. Si je trouve une similarité trop grande et que je doute de votre bonne foi, je n'hésiterais pas à mettre 0 à la question. 
Pareil pour la copie sur les voisins. Si c'est trop gros et que j'ai un doute trop prononcé... 🔫

![alt](https://media.giphy.com/media/BtedgmzGNCiuk/giphy.gif)



------

### 1. Avec vos mots, expliquez l'interaction client-serveur

```t
L'interaction client-serveur correspond à l'action du client qui demande via un réseau comme internet une information à un serveur qui lui fourni une réponse (requête - réponse)
```



 ### 2. HTML est un langage côté... 

```
Client car il est accessible par les utilisateurs.
```



### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<!-- Completez après cette ligne -->
    <html>
<head>
   
<title> XXX </title>
</head>
    <body>
        </body>
</html>
```



### 4. Changez la couleur du texte "J'adore la programmation" en rose en utilisant du CSS.

```html
<div>
   <p>J'adore la programmation</p>
</div>
```

```css
/* Ecrire le code CSS sous cette ligne */
p {
    color: pink;
 
}
```



### 5. Qu'est-ce que Bootstrap ?

```
Bootsrap est une site internet qui propose différents outils de programmataion en langage HTML, CSS mais aussi Javascitpt. Cet outil permet d'obtenir des lignes de codes structurées constituant une base pour le code informatique d'un site internet.
```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html
<!DOCTYPE html>
<html>
<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    
   <!-- Bootstrap CSS -->
    
     <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
        
<title> XXX </title>
</head>
    <body>
    </body>
</html>
```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
<div class="row">
<div class="col-sm-4">
    Google
</div>

<div class="col-sm-4">
    Microsoft
</div>

<div class="col-sm-4">
    Apple
</div>
```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
<div class="row">
<div class="col-sm-4">
  <img src="Google.png"border=0 width=100 height=100>
</div>

<div class="col-sm-4">
    <img src="Microsoft.png"border=0 width=100 height=100>
</div>

<div class="col-sm-4">
   <img src="Apple.png"border=0 width=100 height=100>
</div>
```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html
<div class="row">
    
<div class="col-sm-4">
   <a href="https://www.google.fr/webhp?hl=fr&sa=X&ved=0ahUKEwitltKc067fAhVI6RoKHToNC3QQPAgH"> <img src="Google.png"> </a>

</div>

<div class="col-sm-4">
                     <a href="https://www.microsoft.com/fr-fr/"> <img src="Microsoft.png"border=0 width=100 height=100> </a>
                   </div>

<div class="col-sm-4">
    <a href="https://www.apple.com/fr/"> <img src="Apple.png"border=0 width=100 height=100> </a>
   
</div>
```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
Serveur
```



### 11. Listez-moi tous les types de données que vous connaissez.

```
Float(chiffre à virgule), integer(nombre entier), string (texte)
```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
print "What's your first name? "
first_name = Myriam

print "What's your last name? "
last_name = Kanté

print "What's your Github link? "
Github_link = https://github.com/Myriamknt
```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby
1 loop do
2 a = 674
3 b = 311
4 puts  "#{a} : #{b} ?" 
5 answer = gets.modulo
6 result = a * b 
12 end
# Le résultat attendu est 52. 
```



### 14. Qu'est-ce qu'une gem ? 

```texte
Structure de code 
```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
Carte d'identité de programmation/ plateformede programmation
```



### 14. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby

# <- Demander le prénom de l'utilisateur

hour = 15
prenom = gets.chomp
# Si hour est inférieur à 12
puts "bonjour #{prenom}"
else
puts "Bonsoir #{prenom}"
end
	# j'écris mon code permettant de dire Bonjour prénom

# sinon
	# j'écris mon code permettant de dire Bonsoir prénom

```



### 15. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
harry = ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]
array.each do |follow|

end

```



### 16. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

