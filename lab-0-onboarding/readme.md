\# Ghid de Onboarding - Laborator SSATR

\## Managementul proiectelor prin GitHub



\### 📋 Introducere



Bun venit la laboratorul SSATR! 



\*\*GitHub va fi platforma centrală\*\* pentru toate activitățile de laborator. GitHub este standardul de facto pentru managementul codului sursă.



\### Obiective și Așteptări



La finalul acestui setup, veți avea:

\- Un repository GitHub personal pentru laborator

\- Structura inițială de proiect configurată

\- Înțelegerea workflow-ului de dezvoltare cu GitHub

\- Pregătirea pentru utilizarea GitHub Issues și Pull Requests



\### Workflow-ul de Dezvoltare



În cadrul laboratoarelor, veți folosi următorul workflow standardizat:



1\. \*\*Issues\*\* - Pentru fiecare temă/exercițiu, veți crea un issue care descrie sarcina



2\. \*\*Branch-uri\*\* - Veți lucra pe branch-uri separate pentru fiecare issue



3\. \*\*Pull Requests\*\* - Fiecare soluție va fi propusă prin Pull Request



4\. \*\*Code Review\*\* - Codul va fi revizuit înainte de merge



5\. \*\*Merge în Main\*\* - După aprobare, codul va fi integrat în branch-ul principal



&nbsp;  



\### Pașii de Setup Inițial



\#### Pasul 1: Crearea Repository-ului



1\. \*\*Accesați GitHub\*\* și autentificați-vă în cont

2\. \*\*Creați un repository nou:\*\*

&nbsp;  - Numele: `ssatr-ia-lab-\[numeleprenumele]` (ex: `ssatr-ia-lab-ioanpopescu`)

&nbsp;  - Descrierea: "Repository pentru laboratorul SSATR IA - \[Anul Academic]"

&nbsp;  - Setați repository-ul ca \*\*Public\*\*

&nbsp;  - Bifați "Add a README file"

&nbsp;  - Bifați "Add .gitignore" și selectați \*\*Java\*\*



\#### Pasul 2: Configurarea README-ului Inițial



Editați fișierul `README.md` cu următoarea structură:



```markdown

\# Laborator SSATR - \[Numele și Prenumele]



\## Despre

Repository pentru lucrarile de laborator din cadrul cursului Sisteme Software pentru Aplicații în Timp Real.



```



\#### Pasul3: Structura Inițială de Directoare



Creați următoarea structură în repository:



```

📁 ssatr-ia-lab-\[numele]

├── 📄 .gitignore

└── 📄 README.md

```



\### 🔧 Workflow pentru Fiecare Laborator



\#### 1. Crearea unui Issue



Pentru fiecare laborator/exercițiu:

\- Accesați tab-ul \*\*Issues\*\*

\- Creați un issue nou cu titlul: `Lab \[X] - \[Descrierea scurtă]`

\- Adăugați o descriere detaliată a cerințelor

\- Assignați issue-ul la voi înșivă

\- Adăugați label-uri relevante (ex: `lab`, `enhancement`, `bug`)



\#### 2. Crearea unui Branch



```bash

\# Clonarea repository-ului (prima dată)

git clone https://github.com/username/ssatr-lab-numele.git

cd ssatr-lab-numele



\# Crearea și switch pe branch nou pentru issue

git checkout -b lab01-setup

\# sau

git checkout -b issue-\[numărul-issue]

```



\#### 3. Dezvoltarea și Commit-urile



```bash

\# Adăugarea modificărilor

git add .



\# Commit cu mesaj descriptiv

git commit -m "Lab01: Add initial project structure



\- Create main package structure

\- Add sample Hello World application

\- Configure build tools



Closes #\[numărul-issue]"



\# Push branch-ul

git push origin lab01-setup

```



\#### 4. Crearea Pull Request-ului



1\. Accesați repository-ul pe GitHub

2\. Veți vedea un banner pentru crearea PR-ului

3\. Completați:

&nbsp;  - \*\*Titlu\*\*: descriptiv și clar

&nbsp;  - \*\*Descriere\*\*: explicați ce schimbări ați făcut

&nbsp;  - \*\*Link către issue\*\*: `Closes #\[numărul]`

4\. Solicitați review (de la colegi sau instructor)



\#### 5. Review și Merge



\- Așteptați feedback-ul

\- Implementați sugestiile primite

\- După aprobare, faceți merge în `main`

\- Ștergeți branch-ul după merge



\### 📚 Resurse și Comenzi Utile





\#### Convențiile de Naming



\- \*\*Branch-uri\*\*: `lab\[X]-\[descriere-scurta]` sau `issue-\[număr]`

\- \*\*Commit messages\*\*: Format standard cu titlu și descriere

\- \*\*Issue titles\*\*: `Lab \[X] - \[Descrierea scindicită]`

\- \*\*PR titles\*\*: Similar cu issue-urile, dar mai descriptiv





\###  Verificarea Setup-ului



Pentru a confirma că ați configurat totul corect:



\- \[ ] Repository-ul există și este public

\- \[ ] README.md conține informațiile cerute

\- \[ ] .gitignore este configurat pentru Java

\- \[ ] Ați creat primul issue pentru Lab01

\- \[ ] Ați făcut primul commit pe un branch separat

\- \[ ] Ați creat primul Pull Request



\### 🔜 Pașii Următori



1\. \*\*Completați setup-ul\*\* conform acestui ghid

2\. \*\*Creați primul issue\*\* pentru Lab01

3\. \*\*Așteptați instrucțiunile\*\* pentru primul exercițiu Java

4\. \*\*Familiarizați-vă\*\* cu interfața GitHub

\# Ghid de Onboarding - Laborator SSATR

\## Managementul proiectelor prin GitHub



\### 📋 Introducere



Bun venit la laboratorul SSATR! 



\*\*GitHub va fi platforma centrală\*\* pentru toate activitățile de laborator. GitHub este standardul de facto pentru managementul codului sursă.



\### Obiective și Așteptări



La finalul acestui setup, veți avea:

\- Un repository GitHub personal pentru laborator

\- Structura inițială de proiect configurată

\- Înțelegerea workflow-ului de dezvoltare cu GitHub

\- Pregătirea pentru utilizarea GitHub Issues și Pull Requests



\### Workflow-ul de Dezvoltare



În cadrul laboratoarelor, veți folosi următorul workflow standardizat:



1\. \*\*Issues\*\* - Pentru fiecare temă/exercițiu, veți crea un issue care descrie sarcina



2\. \*\*Branch-uri\*\* - Veți lucra pe branch-uri separate pentru fiecare issue



3\. \*\*Pull Requests\*\* - Fiecare soluție va fi propusă prin Pull Request



4\. \*\*Code Review\*\* - Codul va fi revizuit înainte de merge



5\. \*\*Merge în Main\*\* - După aprobare, codul va fi integrat în branch-ul principal



&nbsp;  



\### Pașii de Setup Inițial



\#### Pasul 1: Crearea Repository-ului



1\. \*\*Accesați GitHub\*\* și autentificați-vă în cont

2\. \*\*Creați un repository nou:\*\*

&nbsp;  - Numele: `ssatr-ia-lab-\[numeleprenumele]` (ex: `ssatr-ia-lab-ioanpopescu`)

&nbsp;  - Descrierea: "Repository pentru laboratorul SSATR IA - \[Anul Academic]"

&nbsp;  - Setați repository-ul ca \*\*Public\*\*

&nbsp;  - Bifați "Add a README file"

&nbsp;  - Bifați "Add .gitignore" și selectați \*\*Java\*\*



\#### Pasul 2: Configurarea README-ului Inițial



Editați fișierul `README.md` cu următoarea structură:



```markdown

\# Laborator SSATR - \[Numele și Prenumele]



\## Despre

Repository pentru lucrarile de laborator din cadrul cursului Sisteme Software pentru Aplicații în Timp Real.



```



\#### Pasul3: Structura Inițială de Directoare



Creați următoarea structură în repository:



```

📁 ssatr-ia-lab-\[numele]

├── 📄 .gitignore

└── 📄 README.md

```



\### 🔧 Workflow pentru Fiecare Laborator



\#### 1. Crearea unui Issue



Pentru fiecare laborator/exercițiu:

\- Accesați tab-ul \*\*Issues\*\*

\- Creați un issue nou cu titlul: `Lab \[X] - \[Descrierea scurtă]`

\- Adăugați o descriere detaliată a cerințelor

\- Assignați issue-ul la voi înșivă

\- Adăugați label-uri relevante (ex: `lab`, `enhancement`, `bug`)



\#### 2. Crearea unui Branch



```bash

\# Clonarea repository-ului (prima dată)

git clone https://github.com/username/ssatr-lab-numele.git

cd ssatr-lab-numele



\# Crearea și switch pe branch nou pentru issue

git checkout -b lab01-setup

\# sau

git checkout -b issue-\[numărul-issue]

```



\#### 3. Dezvoltarea și Commit-urile



```bash

\# Adăugarea modificărilor

git add .



\# Commit cu mesaj descriptiv

git commit -m "Lab01: Add initial project structure



\- Create main package structure

\- Add sample Hello World application

\- Configure build tools



Closes #\[numărul-issue]"



\# Push branch-ul

git push origin lab01-setup

```



\#### 4. Crearea Pull Request-ului



1\. Accesați repository-ul pe GitHub

2\. Veți vedea un banner pentru crearea PR-ului

3\. Completați:

&nbsp;  - \*\*Titlu\*\*: descriptiv și clar

&nbsp;  - \*\*Descriere\*\*: explicați ce schimbări ați făcut

&nbsp;  - \*\*Link către issue\*\*: `Closes #\[numărul]`

4\. Solicitați review (de la colegi sau instructor)



\#### 5. Review și Merge



\- Așteptați feedback-ul

\- Implementați sugestiile primite

\- După aprobare, faceți merge în `main`

\- Ștergeți branch-ul după merge



\### 📚 Resurse și Comenzi Utile





\#### Convențiile de Naming



\- \*\*Branch-uri\*\*: `lab\[X]-\[descriere-scurta]` sau `issue-\[număr]`

\- \*\*Commit messages\*\*: Format standard cu titlu și descriere

\- \*\*Issue titles\*\*: `Lab \[X] - \[Descrierea scindicită]`

\- \*\*PR titles\*\*: Similar cu issue-urile, dar mai descriptiv





\###  Verificarea Setup-ului



Pentru a confirma că ați configurat totul corect:



\- \[ ] Repository-ul există și este public

\- \[ ] README.md conține informațiile cerute

\- \[ ] .gitignore este configurat pentru Java

\- \[ ] Ați creat primul issue pentru Lab01

\- \[ ] Ați făcut primul commit pe un branch separat

\- \[ ] Ați creat primul Pull Request



\### 🔜 Pașii Următori



1\. \*\*Completați setup-ul\*\* conform acestui ghid

2\. \*\*Creați primul issue\*\* pentru Lab01

3\. \*\*Așteptați instrucțiunile\*\* pentru primul exercițiu Java

4\. \*\*Familiarizați-vă\*\* cu interfața GitHub



