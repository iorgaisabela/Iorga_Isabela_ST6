# Testing Project for OrangeHrm..com- Leave module
Scopul proiectului final pentru ITF Testare Manuala este de a acumula cunostinte si practica cu ajutorul cursului, folosind o aplicatie reala

Aplicatia testata:OrangeHrm.com

Tools folosite:Jira,Zephyer Squad

### OrangeHrm - Leave module - Jira-Cerinte business

Am ales modulul Leave al aplicatiei ( in cadrul cursului s-a studiat Personal detailes si Myinfo module)

Ca utlilzator vreau sa completez datele de concediu pentru angajatii companiei pentru a tine evidenta corecta a datelor.
![image](https://github.com/user-attachments/assets/1c1f4c8e-b567-46ee-9048-03855284f61e)

Ca utilizator vreau sa completez dreptul de concediu al angajatilor companiei pe tip si perioada pentru a tine o evidenta corecta a datelor.
![image](https://github.com/user-attachments/assets/fe9a0dcd-b89a-4e79-9435-c91e9e5ef80d)

Aici puteti regasii release-ul care a fost creat pentru acest proiect

![image](https://github.com/user-attachments/assets/c225a978-da81-4e93-aed6-a2860350150b)

### Testing process

Procesul testarii s-a realizat pe baza standardelor descrise mai jos.

## 1.1 Test planing

Planul de testare este conceput pentru a descrie toate detaliile testării pentru toate modulele din aplicația OrangeHrm.

Planul identifică elementele de testat, caracteristicile de testat, tipurile de testare care trebuie efectuate, personalul responsabil de testare, resursele și programul necesar pentru finalizarea testării și riscurile asociate cu planul. Planul de testare care a fost creat pentru acest proiect poate fi găsit aici [plan de testare](https://github.com/iorgaisabela/Iorga_Isabela_ST6/blob/main/Plan_de_testare_Orangehrm.com_st6)

## 1.1.1. Rolurile atribuite proiectului și persoanele alocate


Manager de proiect: Iorga Ionut

Proprietar de produs: Slotan Olivia

Dezvoltator software: Matei Ovidiu

Inginer QA : Iorga Anamaria Isabela

## Entry criteria 

-	Ar trebui să avem un mediu de testare disponibil și să putem fi accesați de toți membrii de testare
- Ar trebui să avem cerințele de afaceri definite
- Ar trebui să avem rolurile și responsabilitățile stabilite și alocate
- Ar trebui să avem planul de testare descris
- Sunt definite, analizate riscurile potențiale ale proiectului și se stabilește un plan de atenuare

## Exit criteria:
-	Ar trebui să executăm toate cazurile de testare
- Ar trebui să închidem toate erorile majore
- Au fost raportate toate defectele descoperite
- Toate cerințele de afaceri au fost acoperite de cazuri de testare
- S-au efectuat teste de regresie
- Au fost identificate riscuri potențiale ale produselor și este stabilit un plan de atenuare

## Scopul testarii:
- Pentru echipa actuală de testare, funcționalitățile care fac obiectul testării sunt:
- Leave modul care permite administratorului de resurse umane sa configureze (perioada de concediu, tipuri de concediu, Săptămâna de lucru, Sărbători)
-	Leave Entitlements  - permite utilizatorilor să adauge și să vadă leave entitlement al angajaților
  
Pe tot parcursul procesului de testare echipa de testare va efectua teste funcționale, testare pozitivă, testare negativă.

## Funcționalități și teste în afara scopului

-Toate modulele OrangeHRM, cu excepția celor menționate mai sus, sunt în afara domeniului de aplicare.

-Testarea nefuncțională este în afara domeniului de aplicare.

-Testarea automatizării este în afara domeniului de aplicare.


###  Riscuri:
Project risks: 
-	A. Echipa de testare are un singur tester disponibil -poate duce la intarzierea predarii
-	B. Clientul cere des schimbari – intarziere , bug-uri, costuri suplimentare
-	C. Bugetul pentru testare este putin – testarea nu este facuta pe toate functionalitatile, poate duce la multe bug-uri dupa predare sau chiar esuarea proiectului.

Product risks: 

- E. Testarea non-functionala nu este in planul de testare – performanta poate fi slaba 
- F. Testarea pe partea securitatii nu se gaseste in planul de testare- aplicatia poate pierde date

## Evaluarea criteriilor de intrare:

 Criteriile de intrare definite in planul de testare au fost atinse iar procesul testarii poate continua.

 ## Monitorizare si control

 - In această fază sunt generate rapoarte periodice și trimise conducerii pentru a informa despre nivelul de calitate al aplicației
   
![image](https://github.com/user-attachments/assets/40baa5a5-414c-4e9f-b642-974c2892d976)

### Analiza 

Procesul de testare va fi executat pe baza cerințelor aplicației.

Aici gasiti următoarele condiții de testare:

![image](https://github.com/user-attachments/assets/99ca42e6-bb74-4d75-9666-7223f9e25aff)


### Test Design

Cazurile de testare funcționale au fost create în Zephyr Squad pe baza analizei specificațiilor.

Cazurile de testare pot fi accesate aici *[teste](https://github.com/iorgaisabela/Iorga_Isabela_ST6/blob/main/Teste_jira.csv)

## Implementarea testului
- În această fază acordăm prioritate cazurilor de testare scrise în faza anterioară
- De asemenea, ne asigurăm că mediul de testare este actualizat cu cele mai recente modificări

## Executarea testelor
Testele sunt executate in Cycle Summary creat-Configure tests-

Defectele au fost create pe baza testelor picate, aici gasiti raportul defectelor gasite [raport defecte](https://github.com/iorgaisabela/Iorga_Isabela_ST6/blob/main/Raport_defecte_oranghrm_st6.csv)
- Search button dosen't work - 1 defect -prioritate mare-severitate 2
- OrangeHrm application not responding - prioritate foarte mare-severitate 1
- Dropdown button not responding - 1 defect -prioritate medie -severitate 2
- Button Save not responding - 1 defect -prioritate mare -severitate 3
- User with no admin rights complete Leave Period - 1 defect - prioritate foarte mare-severitate 2


## Finalizarea testului
Deoarece criteriile de ieșire au fost îndeplinite și satisfăcute așa cum se menționează în secțiunea corespunzătoare, echipa de testare sugerează această caracteristică pentru „Go live”
Matricea trasabilitati a fost generata si o puteti gasi aici [matricea trasabilitatii](https://github.com/iorgaisabela/Iorga_Isabela_ST6/blob/main/Matricea%20trasabilitatii_Orangehrm_ST6.csv)
Diagrama de execuție a testului a fost generată și poate fi găsită mai jos. [Diagrama testului de executie](https://itfclasses.atlassian.net/jira/dashboards/10510?maximized=10948)



Raportul final arată că un număr de 3 teste au eșuat dintr-un total de 14.

Un nr de 5 defecte au fost gasite in total, dintre care 3 au fost reparate, au ramas 2 defecte cu prioritate medie.

Au fost create 14 teste si executate, au fost acoperite 50% din cerintele de business, defectele nu impacteaza lansarea produsului, pot fi fixate ulterior.



