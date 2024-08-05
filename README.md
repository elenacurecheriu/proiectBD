  Baza de date gestioneaza o aplicatie tip Spotify/Apple Music/Youtube Music/aplicatie generala de streaming de muzica, avand ca entitati:

  - ABONAMENT, care poate fi detinut de catre un unic utilizator, care la randul sau poate detine un singur abonament
  - UTILIZATOR, care poate detine mai multe playlist-uri, care pot fi gestionate de catre un singur utilizator
  - PLAYLIST, care poate contine mai multe melodii
  - MELODIE, care se poate afla in mai multe playlist-uri, se poate incadra in mai multe genuri, se poate afla intr-un singur album si poate fi interpretata de cel putin un artist
  - ALBUM, care se poate incadra in mai multe genuri si poate apartine unui singur artist
  - GEN, care poate contine mai multe albume si melodii
  - ARTIST, care poate detine mai multe albume si apartine unei unice case de discuri
  - CASA_DE_DISCURI, care poate avea contractati mai multi artisti
  - tabele intermediare (GEN_ALBUM, GEN_MELODIE, ARTIST_MELODIE, MELODIE_PLAYLIST), pentru a rezolva relatiile de tip many-to-many

  Diagrama conceptuala:

  ![diagrama conceptuala finala finala](https://github.com/user-attachments/assets/97dd353b-7df1-4e25-9e21-17ac7fa93472)

