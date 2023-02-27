# h10-task


## Kone 

## a)

Aloitin asentamalla virtuaaliympäristön ``virtualenv`` virtuaalikoneelle. Komennolla ``$ sudo apt-get update`` hain ensin päivitykset, jonka jälkeen asensin ``virtualenv`` komennolla:

    $ sudo apt-get -y install virtualenv
    
Loin uuden virtuaaliympäristön ``virtualenv`` python3 paketin asentamiseksi komennolla

    $ virtualenv --system-site-packages -p python3 env/

  - Komento luo uuden ``env`` kansion, jossa on uusimmat paketit. ``--system-site-packages`` sallii virtuaaliympäristön ulkopuolisten pakettien asentamisen. 
  
Otin virtuaaliympäristön käyttöön komennolla ``$ source env/bin/activate``

![Add file: 


