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
____________________________________________________________________________________________________________________

This 2D platformer game has been implemented using Unity. https://www.mediafire.com/file/9z447wpmb5yytal/2d_game_newest_version.zip/file

The game is a 2D platformer where the player must find their way to the end. Along the way, there are monsters, obstacles, etc. The player can shoot, and there is only one weapon (attached to the sprite itself). The shooting speed can be increased as the player progresses in the game and successfully acquires the necessary item.

I have used assets in the game from the website https://opengameart.org/. The item assets (collectibles) are from my favorite games (Call of Duty: Black Ops, Pokemon). The sounds in the game are also from my favorite games (Runescape, Pokemon Trading Card Game Online, Call of Duty: Black Ops).

The player in the game has an HP bar that decreases as the player takes damage. It is based on the bar's transform.scale.x (max HP 1.00). If the player dies (hpbar.transform.scale.x <= 0), the GAME OVER screen and REPLAY button appear. Pressing the REPLAY button restarts the game from the first level.

Money can be used to purchase items from chests found in the levels, and above each chest, you can see what kind of items can be obtained from it. The chest is destroyed immediately once the item is purchased.

The functions of items are visible in the INFO section (Start menu -> Info/Pause menu -> Info).

The most challenging part of creating the game was designing and creating the levels, deciding what they would be like. I came up with items one after another and knew how to code their functionalities.
