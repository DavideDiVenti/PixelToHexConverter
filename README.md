# PixelToHexConverter Website
https://davidediventi.github.io/PixelToHexConverter/

* L'idée de ce logiciel est que l'utilisateur puisse créer des icones et animations de ces-derniers en pixelart. 
* A chaque interraction le logiciel exporte l'image sous forme d'une chaine hexadécimale et/ou binaire. 
* L'utilisateur peut ensuite copier cette chaine et l'introduire dans le code de son microcontroleur.
* Le code du microcontroleur interpretera cette chaine hexadécimale ou binaire afin de créer des objets de classe respectif à chaque chaine (icone d'un ventilateur, d'un termomètre, d'un buzzer, ...). 
* La [classe](https://github.com/DavideDiVenti/myVacuum/blob/main/myVacuumCode/myClass_DrawOnTheScreen.cpp) pourra ensuite proposer divers méthodes afin d'afficher les pixels sur l'écran correspondant à l'objet en question.

<p align="left">
  <img align="center" width="80%" src="https://github.com/DavideDiVenti/myVacuum/blob/main/Documents/Images/Pixel_To_Hex_Converter.gif" />
</p>
