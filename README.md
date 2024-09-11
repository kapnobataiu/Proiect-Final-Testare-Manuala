**Proiect de testare pentru eMAG**

Scopul proiectului final pentru cursul de Testare Manuală ITF este de a utiliza toate cunoștințele dobândite pe parcursul cursului și de a le aplica în practică, folosind o aplicație live.

**Aplicația supusă testării: Platforma ecommerce eMAG**

Platforma de comerț electronic eMAG este una dintre cele mai mari și populare platforme de retail online din România și din alte țări din regiune. eMAG permite utilizatorilor să caute, să compare și să cumpere o gamă largă de produse, de la electronice și electrocasnice la cărți, haine, produse pentru casă și multe altele. De asemenea, platforma oferă funcționalități complexe de gestionare a contului, incluzând setări de securitate, lista de produse favorite, istoricul comenzilor, metode de plată și multe altele.

**Instrumente utilizate: Jira, Zephyr Squad**

**Specificații funcționale**

Story-urile de mai jos au fost create în Jira și descriu specificațiile funcționale ale modulelor „Favorite” și „Setări Siguranță” pentru care se realizează proiectul final.

![Story Favorite](https://github.com/user-attachments/assets/85aa4abd-6246-4bcf-92c0-3cefeba4af30)

![Story Security Settings](https://github.com/user-attachments/assets/e308c147-366e-4e80-9bbc-99621ad1cbb2)

**Aici puteți găsi versiunea care a fost creată pentru acest proiect:**

**v3.0 Launch of Enhanced Features in the "Favorites" and "Security Settings" Modules**

![Release](https://github.com/user-attachments/assets/a007b8e4-ac38-41d4-a48b-660b72c6b9ce)

**Procesul de testare**

Procesul de testare a fost realizat pe baza procesului standard de testare, descris mai jos.

**1.1 Planificarea testării**

Planul de testare este conceput pentru a descrie toate detaliile testării pentru toate modulele aplicației web ecommerce eMAG.
Planul identifică elementele care urmează să fie testate, funcționalitățile care vor fi testate, tipurile de testare ce vor fi efectuate, persoanele responsabile pentru testare, resursele și programul necesar pentru a finaliza testarea, precum și riscurile asociate planului. Planul de testare creat pentru acest proiect poate fi găsit aici.

**1.1.1 Roluri atribuite proiectului și persoane alocate**

- Project Manager - Florin Constantinescu (monitorizarea proiectului și asigurarea respectării termenelor)
- Product Owner - Matei Marinescu (garantarea produsului final că va corespunde cerințelor utilizatorilor și celor de business)
- Software Developer - Alexandra Iordache (rezolvarea defectelor raportate)
- Test lead - Ovidiu Bratu (coordonarea echipei de testare și raportarea progresului)
- Tester 1 - Mihai Tudosie (testarea funcționalității “Favorite”)
- Tester 2 - Ramona Nicolae (testarea funcționalității “Setări Siguranță”)

**1.1.2 Criteriile de intrare**

- Definirea și aprobarea cerințelor funcționale pentru „Favorite” și „Setări Siguranță”
- Cerințele pentru funcționalitățile din modulele „Favorite” și „Setări Siguranță” sunt clar definite și aprobate de Product Owner și echipa de dezvoltare
- Acces la mediul de testare: mediul de testare pentru modulele „Favorite” și „Setări Siguranță” sunt complet configurate și accesibile
- Disponibilitatea specificațiilor de testare și a planului de testare: specificațiile și test case-urile pentru modulele „Favorite” și „Setări Siguranță” sunt documentate și aprobate. Planul de testare detaliază toate testele necesare pentru aceste module.
- Finalizarea dezvoltării funcționalităților: funcționalitățile pentru modulele „Favorite” și „Setări Siguranță” au fost complet dezvoltate și sunt disponibile pentru testare
- Disponibilitatea instrumentelor de testare: instrumentele de testare necesare pentru a verifica modulele „Favorite” și „Setări Siguranță” sunt configurate și funcționale
- Alocarea resurselor: echipa de testare este alocată și pregătită să testeze modulele „Favorite” și „Setări Siguranță”, cu roluri și responsabilități clar definite

**1.1.3 Criteriile de ieșire**

- Execuția completă a test case-urilor pentru „Favorite” și „Setări Siguranță”: toate test case-urile relevante pentru modulele „Favorite” și „Setări Siguranță” au fost executate
- Număr acceptabil de defecte deschise: defectele critice și majore au fost rezolvate și verificate. Defectele minore sunt în limitele acceptabile.
- Confirmarea din partea Product Owner-ului și Stakeholderilor: Product Owner-ul și stakeholderii au revizuit rezultatele testării pentru „Favorite” și „Setări Siguranță” și au aprobat rezultatul
- Actualizarea documentației de testare: documentația de testare este completă și actualizată, inclusiv test case-urile și rapoartele de defecte pentru „Favorite” și „Setări Siguranță”
- Raport de testare finalizat: raportul final de testare pentru modulele „Favorite” și „Setări Siguranță” a fost generat și include o analiză detaliată a rezultatelor.
- Confirmarea de pregătire pentru lansare: Echipa de dezvoltare și echipa de testare confirmă că funcționalitățile din „Favorite” și „Setări Siguranță” sunt stabil și gata pentru lansare în producție.

**1.1.4 Domeniul testării**

Pentru echipa de testare curentă, funcționalitățile care sunt în scopul testării sunt:
- Modulul „Favorite” - permite utilizatorilor să adauge și să gestioneze produsele preferate pe platforma eMAG, incluzând notificarea utilizatorilor despre reduceri sau revenirea în stoc a produselor
- Modulul „Setări Siguranță” - oferă utilizatorilor funcționalități avansate de securitate pentru protecția contului lor pe eMAG
Pe parcursul procesului de testare, echipa de testare va efectua testare funcțională, testare pozitivă, testare negativă, testare de integrare.
Pentru echipa de testare curentă, funcționalitățile care nu sunt în scopul testării sunt:
- Toate modulele eMAG, cu excepția celor menționate mai sus, sunt în afara scopului testării.
- Testarea non funcțională și testarea automatizată nu sunt în scopul testării.

**1.1.5 Riscuri detectate**

Riscuri de proiect:
- Lipsa personalului necesar sau a echipamentelor necesare pentru testare poate afecta calitatea și amploarea testării 
- Probleme de comunicare între echipele de dezvoltare și testare
- Schimbări frecvente sau de ultim moment în cerințele funcționale
- Documentația insuficientă sau inexactă

Riscuri de produs:
- Funcționalitatea „Favorite” nu funcționează conform specificațiilor
- Defecte în implementarea setărilor de securitate
- Funcționalitățile de „Favorite” sau „Setări Siguranță” afectează performanța generală a platformei eMAG
- Funcționalitățile nu sunt complet compatibile cu toate browserele folosite de utilizatori


**1.1.6 Evaluarea criteriilor de intrare**

Criteriile de intrare definite în faza de planificare a testării au fost îndeplinite și procesul de testare poate continua.

**1.2 Monitorizarea și Controlul Testării**

Etapa de monitorizare și control a fost realizată pentru a asigura că procesul de testare se desfășoară conform planului stabilit și pentru a identifica și aborda problemele care ar putea afecta calitatea și eficiența testării. Această etapă este esențială pentru menținerea transparenței în desfășurarea testelor, pentru ajustarea planurilor de testare în funcție de progres și pentru garantarea că toate cerințele și obiectivele de testare sunt îndeplinite. Monitorizarea ajută la detectarea devierilor de la planul inițial și permite echipei să ia măsuri corective la timp, minimizând impactul asupra proiectului.
Modul de desfășurare a acestei etape a fost compus din monitorizarea progresului, raportarea defectelor, revizuirea rezultatelor testelor, actualizarea planului de testare și gestionarea riscurilor.

![daily test execution](https://github.com/user-attachments/assets/5e52730c-b8ce-4de1-8278-326de9fd6e57)

**1.3 Analiza testelor**

Procesul de testare va fi executat pe baza cerințelor aplicației. 
Următoarele condiții de testare au fost găsite:

![Test conditions 1](https://github.com/user-attachments/assets/ef459b3a-3bc1-41da-8b08-5cfa3dda3409)
![Test conditions 2](https://github.com/user-attachments/assets/5f09b640-b598-473d-8e21-028478dc3c4d)

**1.4 Designul testelor**

Cazurile de testare funcționale au fost create în Zephyr Squad pe baza analizei specificațiilor. Cazurile de testare pot fi accesate [aici](https://drive.google.com/file/d/1VL5W1ZctoL6l9VulkjQgdC5vH3RExprk/view?usp=sharing).

**1.5 Implementarea testelor**

În această fază, prioritizăm cazurile de testare scrise în faza anterioară. De asemenea, ne asigurăm că mediul de testare este actualizat cu cele mai recente modificări.
- Toate cazurile de testare și scenariile de testare trebuie să fie complet documentate, inclusiv pașii de execuție, rezultatele așteptate și datele de test. Acestea trebuie să fie revizuite și aprobate.
- Mediul de testare este pregătit, incluzând accesul și permisiunile pentru toți testerii.
- Asigurați-vă că Jira este configurat și toți membrii echipei sunt instruiți cum să înregistreze, să urmărească și să gestioneze eficient bug-urile și problemele.
- Toate datele de test necesare trebuie pregătite în avans. Acestea includ date de autentificare valide pentru utilizatori, date dummy pentru favorite, setări de siguranță, notificări și aplicații conectate.
- Sumarul ciclului este creat, iar testele sunt adăugate.

**1.6. Execuția testelor**

Cazurile de testare sunt executate pe baza rezumatului ciclurilor de testare create: Tests for the "Favorites" Functionality și Tests for the "Security Settings" Functionality.

Testele vor fi executate pe următoarele browsere: Chrome, Safari, Mozilla, Opera, Edge.

Au fost create bug-uri pe baza testelor eșuate. Rapoartele complete ale bug-urilor pot fi găsite [aici](https://docs.google.com/document/d/1Xvh3GQCF32aF76knQT7iz_FJrQMjYdguxSJs-6rYP7M/edit).

Următorul este un rezumat al bug-urilor care au fost găsite:
- The list of favorite products is not persistent after logging out and logging back in (Severity: Major, Priority: High)
- Notification for Discounted Product in Favorites List Not Received (Severity: Major, Priority: Medium)
- Notification for Product Returned to Stock Not Received (Severity: Major, Priority: Medium)
- Disconnected device still appears in the list of connected devices after the disconnection process (Severity: Major, Priority: High)
- Missing Revoke Option for Some Connected Applications (Severity: Major, Priority: High)
- Notification for Suspicious Activity Not Received (Severity: Critical, Priority: High)
  
Testarea completă de regresie este necesară în zonele afectate după ce erorile sunt corectate, iar retestarea va fi efectuată pentru fiecare funcționalitate care a eșuat anterior.

**1.7 Finalizarea Testării**

Întrucât criteriile de ieșire au fost îndeplinite și satisfăcute, așa cum este menționat în secțiunea corespunzătoare, echipa de testare sugerează ca această funcționalitate să fie disponibilă pentru „Go Live”.

Matricea de trasabilitate a fost generată și poate fi găsită [aici](https://docs.google.com/spreadsheets/d/1qylwSlRnXzwF16JnvaGR52lhspMr9dBz/edit?usp=sharing&ouid=110544527443428695516&rtpof=true&sd=true).

Graficul de execuție a testelor a fost generat și poate fi găsit mai jos.

![dashboard111](https://github.com/user-attachments/assets/265c58f5-645d-4cca-96cd-9e1a38eb4165)

Raportul final arată că un număr de 6 teste au eșuat dintr-un total de 18 teste.
Au fost găsite un număr de 6 bug-uri, dintre care prioritatea este: 2 sunt de prioritate mare și 4 sunt de prioritate medie.

Proiectul de testare manuală pentru eMAG pe care l-am realizat a fost complet și a acoperit toate cerințele stabilite. Am avut un total de 2 story-uri care au definit cerințele funcționale pentru modulele „Favorite” și „Setări Siguranță”. Toate story-urile au fost acoperite de 18 teste și toate testele scrise au fost executate.

Testarea a fost efectuată pe principalele versiuni actuale ale browserelor populare (Chrome, Safari, Mozilla, Opera, Edge). Totuși, nu am testat compatibilitatea cu unele browsere mai puțin populare.

Testarea s-a concentrat pe interfața de desktop. Ar fi recomandat să se efectueze și testarea pe diferite dispozitive mobile pentru a verifica responsivitatea și compatibilitatea completă.

Numărul de bug-uri identificate a fost în număr de 6, dintre care 5 cu severitate majoră și 1 cu severitate critică. 
- Bug-ul cu severitate critică “Notification for Suspicious Activity Not Received” afectează funcționalități critice ale aplicației și are un impact direct asupra securității și integrității platformei eMAG pentru utilizatori.
- Bug-urile cu severitate majoră afectează funcționalități mai puțin critice, dar au un impact semnificativ asupra utilizării și pot cauza frustrare utilizatorilor deoarece notificările listei de favorite este foarte importantă, în special în scenarii precum reduceri de preț și suplimentări de stoc, dar și prin faptul că anumite aplicații și dispozitive nu pot fi deconectate din contul utilizatorului.

Orice schimbare târzie în cerințele funcționale poate afecta stabilitatea modulelor testate.
  
Pentru lansarea produsului, recomand remedierea bug-urilor cu prioritate mare înainte de finalizarea fazei de producție. Este necesară o testare suplimentară de regresie după remedierea bug-urilor pentru a valida corectitudinea soluțiilor implementate.

Comunicarea eficientă între echipele de dezvoltare și testare este esențială pentru asigurarea unei înțelegeri comune a cerințelor și pentru prevenirea problemelor cauzate de implementări incorecte sau incomplete. 

Pentru a asigura o lansare de succes, este necesară testarea pe cât mai multe browsere, dispozitive și platforme diferite pentru a acoperi toate scenariile posibile.

Prin urmare, lansarea în producție a funcționalităților „Favorite” și „Setări Siguranță” ar trebui să aibă loc numai după rezolvarea problemelor critice identificate și efectuarea unei testări suplimentare de regresie pentru a asigura stabilitatea și funcționalitatea completă a platformei.

