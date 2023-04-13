# Lexikà
Lexikà è un modulo Drupal che installa i vocabolari utilizzati dalle scuole.
Lexikà, oltre ai vocabolari, importa le configurazioni degli url. 

## Installazione
Per aggiungere il modulo alla tua installazione esegui:
```
$ composer require drupal/pathauto ouitoulia/lexika
```
Installa il modulo `pathauto` e configuralo:
```
$ drush -y pm:install pathauto
$ drush -y config:set pathauto.settings punctuation.slash 1
```
Infine, installa Lexikà
```
$ drush -y en lexika
```

Questo è il risultato:

![Screenshot con l'elenco dei vocabolari installati](docs/vocabolari.png "Screenshot con l'elenco dei vocabolari installati")

## Moduli consigliati
Per importare le voci di tassonomia nei vocabolari puoi usare: 
[Sunchronìzo lexikà](https://github.com/ouitoulia/sunchronizo_lexika)