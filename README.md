# Robotica Tema 2

Tema 2 este bazate pe jocul TypeRacer Game 

Am folosit :  Arduino UNO (ATmega328P microcontroller) ,  1x LED RGB (pentru a semnaliza dacă cuvântul corect e scris greșit sau nu) , 2x Butoane (pentru start/stop rundă și pentru selectarea dificultății) , 5x Rezistoare (3x 220/330 ohm, 2x 1000 ohm) , Breadbord , Fire de legătură .


Schema:

![img_tema2_robotica](https://github.com/user-attachments/assets/c9ed7270-35f3-40c1-94e3-d5dea6404040)

Descriere:

La inceput, jocul este repaus si LED-ul RGB lumineaza alb. Se selecteaza nivelul de dificultate prin apasarea butonului , iar in terminal va fi 
afișat mesajul “Easy/Medium/Hard mode on!”. Jocul incepe prin apasarea butonului de start/stop. LED-ul clipeste timp de 3 secunde, dupa
numaratoare inversa in terminal: 3, 2, 1. Cand LED-ul devine verde, incep sa apara cuvintele de tastat. La tastarea corectă a unui cuvant, urmatorul cuvant 
apare imediat. Dacă timpul specific dificultatii expira fara a tasta cuvantul corect, un nou cuvant va fi afisat. Daca nu avem  greseaala face ca LED-ul sa 
devina rosu, iar corectarea se poate face folosind tasta BackSpace. După 30 de secunde, runda se incheie, iar în terminal se afiseaza scorul: numarul total 
de cuvinte  tastate corect. Jocul poate fi oprit în orice moment folosind butonul de start/stop. (Cuvinte Folosite : "robotica", "arduino", "masina", "tren", "avion", "bicicleta", "metrou", "tir", "tricicleta", "autobuz")

Imagine Montaj:

![imagine tema 2 montaj](https://github.com/user-attachments/assets/3bb78cf8-abd8-4540-a4b0-52fe8a60b041)

Video: https://www.youtube.com/watch?v=6BOAYRkq8ys
