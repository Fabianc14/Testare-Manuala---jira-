<h1>Testing Project for WOLT</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: WOLT

Tools used: Jira, Zephyr Squad.

<h2>Functional specifications:</h2>

The below story Browse a list of available restaurants was created in Jira and describes the functional specifications of the WOLT module, for which the final project is performed upon.

![image](https://github.com/user-attachments/assets/e578b6a8-5bc8-4354-a2d4-f6f887b13d3a)


Here you can find the release that was created for this project:

![image](https://github.com/user-attachments/assets/ff4a8440-7fce-449a-a625-b7084c868c36)


<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here [Test plan.pdf](https://github.com/user-attachments/files/20853242/Test.plan.pdf)


<h4>1.1.1. Roles asigned to the project and persons allocated</h4>


<ul>
  <li>Project manager: Oana Calugarescu</li> 
  <li>Product owner: Gabriel Popa</li>
  <li>Software developer: Andreea Diaconu</li>
  <li>QA Engineer: Cojocaru Fabian</li>
</ul>

<h4> 1.1.2 Entry criteria defined </h4>

Utilizatorul trebuie să fie autentificat 
Aplicația trebuie să fie funcțională și instalată 
Feature-urile să fie dezvoltate și integrate în mediu de testare – presupus de existența testelor.
Date de test valabile trebuie să existe – cum ar fi comenzi anterioare, restaurante favorite etc.
Acces la infrastructura Wolt (website, conturi test) – evident din toți pașii de reproducere.
Bugurile critice anterioare să fie rezolvate sau izolate – implicat prin numărul limitat de defecte active.



<h4> 1.1.3 Exit criteria defined </h4>

Toate cazurile de testare definite au fost executate 
Toate bug-urile critice și majore au fost rezolvate 
Funcționalitatea este conformă cu descrierea user stories-urilor 
Aplicația afișează comportamente previzibile în cazuri negative
Notificările și interacțiunile UX funcționează conform așteptărilor 
Feedback-ul stakeholderilor sau al testerilor UAT este pozitiv
Aplicația nu mai conține buguri blocate sau netestate legate de funcționalitățile analizate



<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

1. The user can browse a list of available restaurants
2. The user can choice by type of food
3. The user can search based on his order history and preferences
4. The user can filter based on recommended restaurants, cuisine, rating
5. The user can customize his dish before adding it to the cart. ( add toppings, remove ingredients)
6. The user can show restaurant status (open/closed)
7. A friendly message is shown when no restaurants are available
8. The user can add to favorite an restaurant
9. Tapping a restaurant opens its details
10. The users can search restaurants by name
11. The restaurant list updates after changing the location
12. The user can acces the current order



<h5>Tests not in scope: </h5>

....

<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>

Riscurile de proiect sunt următoarele: 
Comunicarea defectuoasă între echipele de dezvoltare și testare poate duce la interpretări greșite ale cerințelor și scenariilor de testare. Poate apărea un blocaj în procesul de testare din cauza dependenței de restaurante reale pentru testarea statusului „închis/deschis”. 
Dependența de conectivitate și browsere moderne poate crea probleme de compatibilitate în scenarii reale (ex. diferite sisteme de operare, browsere mai vechi). 



<h5> Product risks: </h5>

Riscurile de produs sunt următoarele:
Lista restaurantelor nu se actualizează automat după schimbarea locației, ceea ce poate duce la o experiență frustrantă pentru utilizator. Aplicația nu afișează corect statusul restaurantelor (deschis/închis), ceea ce poate genera comenzi către restaurante indisponibile. 
Informațiile privind evaluările (rating-uri) sunt uneori greșite sau lipsesc, ceea ce afectează încrederea utilizatorului în platformă. În caz de eșec la plasarea comenzii (ex: plată respinsă), lipsa unui mesaj clar de eroare poate reduce încrederea în aplicație.
Funcționalitatea de personalizare a produselor (ex: adăugare toppinguri) poate fi afectată dacă produsul nu e deja în coș.



<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control<h3>


<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements. <b>(The requirements analysis has been done in order to implement the <i>early testing</i> test principle and the results can be found here - inserati linkul catre documentul de review. Parte asta specificata intre paranteze o puneti doar daca aveti cerinte si daca ati facut review)</b>. <br><br>

The following test conditions were found: <br>

1. The user can browse a list of available restaurants
2. The user can choice by type of food
3. The user can search based on his order history and preferences
4. The user can filter based on recommended restaurants, cuisine, rating
5. The user can customize his dish before adding it to the cart. ( add toppings, remove ingredients)
6. The user can show restaurant status (open/closed)
7. A friendly message is shown when no restaurants are available
8. The user can add to favorite an restaurant
9. Tapping a restaurant opens its details
10. The users can search restaurants by name
11. The restaurant list updates after changing the location
12. The user can acces the current order



<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here [ZFJ-issue-export-06-22-2025-617c36affff94b9-0001.pdf](https://github.com/user-attachments/files/20853283/ZFJ-issue-export-06-22-2025-617c36affff94b9-0001.pdf)


<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

Se crează datele de testare, se grupează testele în funcție de importanța față de business și respectiv de riscuri și organizarea lor în suite de testare
crearea unui program de execuție a testelor
crearea mediului de testare și validarea acestuia prin smoke testing



<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: Wolt v1.0.1

Bugs have been created based on the failed tests. The complete bug reports can be found here: [ZFJ-issue-export-06-22-2025-617c36affff94b9-0001.pdf](https://github.com/user-attachments/files/20853343/ZFJ-issue-export-06-22-2025-617c36affff94b9-0001.pdf)[Bugs.pdf](https://github.com/user-attachments/files/20853344/Bugs.pdf)




The following is a summary of the bugs that have been found

1. Restaurant List Not Updating After Location Change
   Prioritate: Medie
   Severitate: Medie
2. Filter by Cuisine Returns Empty List Incorrectly
   Prioritate: Medie
   Severitate: Medie
4. Restaurant Status Label Missing (Open/Closed)
   Prioritate: Medie
   Severitate: Medie

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

<h3> 1.7 Test Completion</h3>
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: ![image](https://github.com/user-attachments/assets/3aa81212-e29f-408b-b320-57e8ed2fd3e0)


Test execution chart was generated and can be found below. 
[Uploading ZFJ-Executions-06-22-2025.csv…]()



The final report shows that a number 20 tests have failed of a total of 3

A number of 2 total bugs were found, from which the priority is: medium.

Concluzie:

1. Au fost scrise un număr total de:
Epic 1 – Wolt restaurant section: 5 stories
Epic 2 – My orders: 5 stories
2. Numărul de story-uri acoperite de teste:
10 din 10 stories au cel putin un test case asociat
3. Numărul total de teste scrise comparativ cu cele executate:
10 pentru Wolt restaurant section
10 pentru Wolt orders section
4. Numărul total de bug-uri descoperite:
2 buguri critice (#1 și #3) afectează direct capacitatea de a comanda corect.  1 bug major (#2) afectează navigabilitatea și căutarea.  1 bug mediu (#4) afectează decizia de cumpărare, dar nu împiedică comanda în sine.


