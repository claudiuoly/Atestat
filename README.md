# Atestat
## Atestat de informatica
### Agentie imobiliara
Agentiile imobiliare reprezinta un aspect foarte important in viata oameniilor. Oameni din intreaga lume cauta locuri in care pot locui oriunde calatoresc. Ei bine ,,ImobiliareOLY.SRL” a venit cu solutia potrivita. Poti inchiria de oriunde din lume un apartament chiar de pe site-ul nostru. Tot pe site ai si agentii nostri bine pregatiti care te pot ajuta la orice ora cu informatii si ajutor in legatura cu apartamentul de inchiriat. Apartamentele de inchiriat pot fi de la un apartament cu o camera pana la cea mai mare casa pe care o doriti. Cand vine vorba de cumparatul apartamentelor sau chiar si a caselor, depide de nevoile dumneavoastra, tot pe site puteti contacta agentii nostri prin diferite metode de pe site(email, telefon, chatul de pe site).
Deoarece avem mai multe sedii peste tot in lume pentru fiecare dintre acestea retinem: (ID_sediu, denumire, localitate, tara, adresa, telefon si email). Agentii nostri apartin unui singur sediu si retinem pentru ei:(ID_agent, ID_sediu, nume, tel, email). 
Pentru fiecare proprietate avem un ID_unic, localitate, tara, adresa, tip_proprietate si daca este listata pentru vanzare sau pentru inchiriere si tipul de proprietate caruia ii corespunde. Pentru fiecare tip de proprietate retinem o categorie(apartament, casa, studio), numar de camere, numar de nivele, si informatii despre terasa, vedere, permitere animale.
Clientii pot rezerva o proprietate doar daca sunt inscrisi astfel pt fiecare client se retine ID_client, nume, email, tel, CNP. Atunci cand o proprietate este inchiriata sau vanduta se creeaza un contract pentru care se retine NR_contract, tipcontract, ID_client, ID_agent, ID_proprietate, data_semnare, data_inchidere.

Constrangeri: 
-	Categoriile in care sunt inscrise prop sunt apartament, casa, studio;
-	Tipul contractului poate sa fie doar de vanzare sau inchiriere;
-	Un agent nu poate lucra decat la un singur sediu;
-	O proprietate poate apartine doar unui tip;
-	Un contract este valabil pentru un singur client;
-	Daca un client inchiriaza sau cumpara mai multe proprietati pentru fiecare se va construi un nou contract.



