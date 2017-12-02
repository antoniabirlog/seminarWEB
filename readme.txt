Single Page Applcation - Manager de contacte integrat cu Google Contacts

Functionalitati

1) Posibilitate de a vizualiza contacte - All contacts/Family/Coworkers/Friends oferita de API
2) Filtrare contacte dupa data modificarii, data crearii
3) Afisare First Name, Last Name sau Last Name, First Name, dupa preferinta utilizatorului
4) Afisare resultate sub forma tabelara cu informatii oferite de Google Contacts (nume, prenume, tag, nickname, adresa etc)
5) Pe fiecare contact afisat, posibilitate de editare
6) Vizualizare numar de contacte returnate
7) Vizualizare pozitie/job pentru fiecare contact


Componente utilizate

1) Search bar pentru cautare dupa cuvinte cheie continute in descriere
2) Contacts list
3) Contacts total ( x contacts returned)
4) Buton de delete la expandarea (afisarea ferestrei de popup) pentru contactul selectat
5) Buton de adaugare contacte noi
6) Sort by
7) Show criterion



User actions

1) Vizualizare contacte dupa un anumit criteriu de cautare - date created, modified 
2) Alegere mod de afisare
3) Aduagare contact
4) Editare + stergere contacte
5) Adaugare imagine asignata contactului selectat



API Calls

1) get/contacts
2) get/contacts/?search=
4) post/contacts
5) put/contacts
6) get/contacts-updated-min='date'
7) delete/contacts