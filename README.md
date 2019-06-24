# Projet de groupe : Envoie d'email

## Installations

Istaller tous les gems :

```sh
$ bundle install
$ gem install twitter
```

Lancer le programme :

```sh
$ ruby app.rb
```

Coller votre fichier .env avec vos ID :

consumer_key="..."

consumer_secret="..."

access_token="..."

access_token_secret="..."

### Arborescence :

Envoi_email_en_masse_THP 
- .gitignore
- README.md
- Gemfile
- Gemfile.lock
- app.rb
- db
  - townhalls.json
- lib
  - app
    - townhalls_scrapper.rb
    - townhalls_mailer.rb
    - Twitter 
        - choper_handles_sur_internet.rb
        - enter_handles_in_json.rb
        - follow_gens_sur_twitter.rb
        - recup_nom_villes_du_json.rb
        - start_bot.rb
  - views
    - done.rb
    - index.rb

### Description du projet :

Le programme s'exécute en trois temps :

1) "Scrapping" des mairies des départements d'Outre Mer (Martinique, Guyane & île de la Réunion)
    On obtient ainsi le nom de l'élu "..." l'adresse e-mail de la ville "..." et enfin le code postal

2) "Follow des comptes Twitter" des 80 mairies via le handle @Rubyaskip

3) "Envoie d'e-mails" de présentation de THP, aux mairies scrappées

Entrer votre prénom et nom="..."

Entrer le début du login de votre e-mail (SANS @xxxxx.com)"..."

Entrer enfin le mot de passe de votre boîte mail

### Equipe :

- Gwen
- Nancy
- Joanne
- Jeremy
- Rid
- Louis
- Huguens
