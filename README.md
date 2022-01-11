# 2dgame
Tämä 2d-tasohyppelypeli on toteutettu Unityllä.
https://www.mediafire.com/file/9z447wpmb5yytal/2d_game_newest_version.zip/file


Peli on 2D-tasohyppelypeli, jossa pelaajan täytyy löytää tie loppuun ja matkan varrella ilmenee monstereita, esteitä jne...
pelaaja pystyy ampumaan ja pelissä on vain yksi ainut ase (spritessä itsessään kiinni) ampumisnopeutta pystyy nopeuttamaan kun pelissä etenee ja onnistuu saamaan siihen tarvittavan itemin.

Olen käyttänyt assetteja pelissä, jotka ovat sivustolta https://opengameart.org/
Item assetit (mitä pelaaja voi kerätä) ovat lempipeleistäni (Call of Duty: Black Ops, Pokemon)
Pelissä olevat äänet ovat myös lempipeleistäni (Runescape, Pokemon Trading Card Game Online, Call of Duty: Black Ops)

Pelissä on pelaajalla HP-BAR, joka vähenee sen mukaan kun pelaaja ottaa vahinkoa. Se on Barin transform.scale.x (max hp 1.00)
Jos pelaaja kuolee (hpbar.transform.scale.x <= 0) tulee näkyviin GAME OVER ja REPLAY-nappi. REPLAY-nappia painamalla peli alkaa alusta, ensimmäisestä tasosta.

Rahalla pystyy ostamaan tasoista löytyvistä arkuista tavaraa ja jokaisen arkun yllä näkyy että minkälaisia itemeitä sieltä pystyy tulemaan. Arkku tuhoutuu heti kun tavara on ostettu.

Itemien toiminnot näkyy INFO:sta (Startmenu -> info/Pause menu -> info)

Pelin tekemisessä vaikeinta oli tason luominen sekä keksiminen, että minkälainen se on.
Itemit keksin heti toisensa perään ja osasin koodata niiden toiminnot.
