# Évaluation individuelle

## Programmation - Coaching

```
Nom : Tran	
Prénom : Linh
URL de votre compte Github : https://github.com/linhtran02
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
L'interaction client-serveur est la communication entre le client et un serveur. C'est l'échange de donnés. Le(s) serveur(s) donne(ent) des informations finales au(x) client(s). 
```



 ### 2. HTML est un langage côté... 

```
client
```



### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<!-- Completez après cette ligne -->
<html>
<head>
    <metacharset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>page title</title>
    <link rel="stylesheet" href="style.css">
    <script src="script.js"></script>
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
div p.rose {
    color: rosybrown;
}
```



### 5. Qu'est-ce que Bootstrap ?

```
Bootstrap est un open source framework avec les codes de HTML, CSS, JS pour le développement web. 
```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">

    <title>Hello, world!</title>
  </head>
  <body>
    <h1>Hello, world!</h1>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
  </body>
</html>
```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
<div class="container">
  <div class="row">
    <div class="col-4">
        Google
    </div>

    <div class="col-4">
        Microsoft
    </div>

    <div class="col-4">
        Apple
    </div>
</div>
```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
<div class="container">
  <div class="row">
    <div class="col-4">
        <img src="https://www.google.fr/images/branding/googlelogo/2x/googlelogo_color_120x44dp.png" />
    </div>

    <div class="col-4">
        <img src="https://img-prod-cms-rt-microsoft-com.akamaized.net/cms/api/am/imageFileData/RE1Mu3b?ver=5c31" />
    </div>

    <div class="col-4">
        <img src="http://ekladata.com/kExaqhlE10B53pMEMmv6opvXdK0@274x331.png" />
    </div>
</div>
```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html
<div class="container">
  <div class="row">
    <div class="col-4">
      <a href="https://google.com">
        <img src="https://www.google.fr/images/branding/googlelogo/2x/googlelogo_color_120x44dp.png" />
      </a>
    </div>

    <div class="col-4">
      <a href="https://microsoft.com">
        <img src="https://img-prod-cms-rt-microsoft-com.akamaized.net/cms/api/am/imageFileData/RE1Mu3b?ver=5c31" />
      </a>
    </div>

    <div class="col-4">
      <a href="https://apple.com">
        <img src="http://ekladata.com/kExaqhlE10B53pMEMmv6opvXdK0@274x331.png" />
      </a>
    </div>
</div>
```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
serveur
```



### 11. Listez-moi tous les types de données que vous connaissez.

```
string = "Chaine de caractere" 
array = ["Array", 1, true]
boolean = true 
float = 1.5
interger = 23 
absence = nil 
first_name = "Linh"
last_name = "Tran"
concatenation = first_name + ' ' + last_name 
interpolation = "#{first_name} #{last_name}"
puts concatenation 
```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
first_name = "Linh"
last_name = "Tran"
githubname = "https://github.com/linhtran02"
puts first_name
puts last_name
puts github
```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby
a = 674
b = 311
c = a%b
puts c
# Le résultat attendu est 52. 
```



### 14. Qu'est-ce qu'une gem ? 

```texte
Une gem est un module de Ruby qui offre des fonctionnalités particulières au programme Ruby.
```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
API est l'abréviation d'Application Programming Interface. C'est un ensemble de routines, de protocoles de communication et d'outils pour la création d'applications logicielles. 
Nous pouvons profiter des services d'un site sans passer par l'interface graphique du site. Les clés d'APIs nous permettent de nous y connecter. 
```



### 14. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
# <- Demander le prénom de l'utilisateur

hour = 15

# Si hour est inférieur à 12
	# j'écris mon code permettant de dire Bonjour prénom

# sinon
	# j'écris mon code permettant de dire Bonsoir prénom

puts "Prenom?"
name = gets
time = Time.now
if time.hour <= 12
  puts "Bonjour " + name
else
  puts "Bonsoir " + name
end

```



### 15. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
require 'bundler/inline'

gemfile true do
  source 'http://rubygems.org'
  gem 'twitter'
end

client = Twitter::REST::Client.new do |config|
  config.consumer_key        = "5PxshDkX3Kc5wsgsT8UbitlV9"
  config.consumer_secret     = "UiSFfQEDuQeWSFzaNQJ6ZbLUqldXciz41NQZc3NgND7XHmfN5f"
  config.access_token        = "1067712149965979648-jnkr7tTynC8GYENDGLHVw09No80WQn"
  config.access_token_secret = "qeYZ5u1ufsKpHWrmwpsFtJmh9wS6LeUjog64e7oygx7dW"
end

handles = ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]

handles.each do |username|
  client.follow(username)
  puts "Followed" + "username"
end

```



### 16. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

