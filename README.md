# LSAC_IT
Proba IT - Backend

Lucruri necesare: php, Postman, Laravel, mysql, apache2, composer.

Rulare: 
  Dezarhivati arhiva. Deschideti un terminal in folderul "example-app" si executati comanda "php artisan serve" pentru a porni server-ul. 
   
  Pentru Postman: copiati in tab-ul "Tests" continutul fisierului "test.txt" si in tab-ul Pre-request Script continutul fisierului "pre-request.txt". Creati un environment cu orice nume si lucrati in el. Asigurati-va ca in tab-ul "Headers" (de sus) se afla header-ul cu numele "X-XSRF-TOKEN" si valoarea {{xsrf-token}}. Trimiteti un request GET prima oara pentru a asigura functionarea.
