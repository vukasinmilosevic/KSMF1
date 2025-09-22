# KSMF 1 zadaci
* Legenda: (v) - zadatak pokriven na vežbama
## 1. Osnovni pojmovi verovatnoće

1. (v) Kolmogorov aksiome: Pokazati da je: $P(A\cup B)=P(A)+P(B)-P(A\cap B)$.

2. (v) Uzimajući u obzir da je $f(x,y)$ definisano kao: $f(x,y)=4xy$ za $0\leq x\leq 1$ i $0\leq y \leq 1$, odrediti conditional i marginal p.d.fs.

3. (v) Snop čestica se sastoji od frakcije $10^{-4}$ elektrona, dok su ostalo fotoni. Čestice prolaze kroz dvoslojni detektor čiji detektorski odziv zapisuje informaciju da je čestica detektovana u 0, 1 ili 2 sloja.
Verovatnoće ovih ishoda za elektrone ($e$) i fotone ($\gamma$) su:

$$
P(0 \mid e) = 0.001, \quad P(0 \mid \gamma) = 0.99899
$$  

$$
P(1 \mid e) = 0.01, \quad P(1 \mid \gamma) = 0.001
$$  

$$
P(2 \mid e) = 0.989, \quad P(2 \mid \gamma) = 10^{-5}
$$  

* **(a)** Kolika je verovatnoća da je čestica foton ako je detektovan signal samo u jednom sloju?  

* **(b)** Kolika je verovatnoća da je čestica elektron ako je detektovan signal u oba sloja?

4. Razmotrimo joint funkciju gustine verovatnoće za dve kontinuirane promenljive $x$ i $y$ datu sa:

$$
f(x, y) =
\begin{cases}
x + y, & 0 \leq x \leq 1,\ 0 \leq y \leq 1 \\
0, & \text{u ostalim sl.}
\end{cases}
$$  

* **(a)** Pronaći marginal p.d.f. $f_x(x)$ i $f_y(y)$ i prikazati kako izgledaju pomoću jednostavnog skica grafa. Da li su $x$ i $y$ nezavisne promenljive? Obražložiti odgovor.

* **(b)** Pronaći conditional p.d.f. $f(x \mid y)$ i $f(y \mid x)$. Navesti kako su ove dve gustine povezane Bajesovom teoremom i pokazati da ona važi koristeći conditional p.d.f. zajedno sa marginal p.d.f. iz dela (a).

5. Razmotriti joint p.d.f. za kontinuirane slučajne promenljive \(x\) i \(y\):
$$
f(x, y) =
\begin{cases}
\frac{1}{\pi R^2}, & x^2 + y^2 \leq R^2 \\
0, & \text{u ostalim slučajevima}
\end{cases}
$$ Definisati nove promenljive:  
$$
u = \sqrt{x^2 + y^2}, \qquad v = \tan^{-1}\!\left(\frac{y}{x}\right).
$$
Pri čemu vidimo da \(u\) odgovara radijusu, a \(v\) azimutalnom uglu u ravnim polarnim koordinatama i važi da su $u \geq 0~\textrm{i}~0 \leq v < 2\pi$.


* **(a)** Pronaći joint p.d.fs za $u$ i $v$. Koristiti inverznu transformaciju $(x = u \cos v,\; y = u \sin v)$. Da li su $u$ i $v$ nezavisne promenljive? Obrazložiti svoj odgovor.  


* **(b)** Pronaći marginal p.d.fs za $u$ i $v$.  


## 2. Testiranje hipoteza

### 2.1 Z-test

6. (v) Populacija svih rezultata govornog testa pri polaganju TOEFL ispita iz engleskog jezika je poznata i ima standardnu devijaciju od 8.5. Trening centar u Beogradu se nada da će polaznici imati TOEFL ocenu preko 210. Ovogodišnji rezultati nalažu da je srednja vrednost, za uzorak od 42 studenta, je bila 212.79. Koristeći vrednost $\alpha=0.05$ odrediti da li je dobijena srednja vrednost statistički značajnija od 210. Obrazložiti zaključak iz perspektive trening centra u Beogradu.

7. (v) (two tailed test) Korporacija "Lotte" i njihova farmaceutska divizija je proizvela lek za koji tvrde da podiže IQ. Test na pacijentima je pokazao da, za 36 pacijenata, imamo srednji IQ od 97.65 nakon korišćenja leka. Poznato je da je standardna devijacija za IQ u generalnoj populaciji 15.
* **(a)**  Koristeći $\alpha=0.05$, da li ovaj srednji IQ izmeren kod test suubjekata značajno odstupa od average IQ koji iznosi 100? 
* **(b)** Obrazložiti tip testa hipoteza koji koristite.
* **(c)**  Sta korporacija "Lotte" može da izvede kao zaključak vašeg testa?

8. (v) Kompanija "Pfizer" testira lek za podizanje broja otkucaja srca u minuti. Test uzorak je sastavljen od 100 ljudi i, nakon kompletirane terapije, zabeležen je porast od 1.4 otkucaja u minuti. Standardna devijacija raspodele je poznata i iznosi 3.6. Kompanija je trenutno u lošem medijskom svetlu i oprezna prilikom predstavljanja novog lega, te žele da koriste statistički test sa $\alpha=0.01$. Na osnovu datih podataka, da li "Pfizer" treba da reklamira ovaj proizvod ili ne? Obrazložiti svaki korak počevši od izbora testa pa sve do finalnog odgovora koji bi ste dali kompaniji.

9. (v) Kompanija "Tigar" proizvodi gume čiji se period života može modelirati sa srednjom vrednošću od 40000 km i standardnom devijacijom od 3000 km. Inženjeri veruju da će promena u procesu proizvodnje dovesti do novog i boljeg tipa guma. Na osnovu iznete prezentacije i primene novih metoda, pokrenut je novi tip proizvodnje i proizvedeno je 100 novih guma. Kompanija je kroz svoje testove odredila da je srednje trajanje novih guma 40900km. Može li se zaključiti da su nove gume značajno bolje od starih, koristeći $\alpha=0.05$? Obrazložiti svaki korak počevši od izbora testa pa sve do finalnog odgovora koji bi ste dali kompaniji.

10. (v) Prosecna tezina gradjana u Ričmondu (Virdžinija) je 168 lbs. Nutricionista veruje da je prava srednja vrednost drugačija. Koristeći merenje težine 36 osoba, zaključio je da je srednja vrednost 169.5 lbs sa standardnom devijacijom od 3.9.
* **(a)**  Definisati null i alternativnu hipoteze.
* **(b)**  Koristeći 95% CL, da li postoji dovoljno dokaza da odbacimo H0? Rešiti zadatak koristiti klasični i p-value pristup uz detaljno objasnjenje svakog.

11. (v) Fabrika proizvodi automobile sa garancijom od 5 godina. Inženjer je posmatrajući protok kola kroz servis zaključio da će motor ili sistem za transmisiju otkazati za kraće od 5 godina i upozorio je kompaniju. Nakon detaljne analize servisnih podataka, iz uzorka od 40 automobila, zaključeno je da je prosečno vreme do kvara 4.8 godina, dok je standardna devijacija 0.5 godina. 
* **(a)**  Definisati null i alternativnu hipoteze iz perspektive inženjera.
* **(b)**  Koristeci $\alpha=0.02$, pokazati da li postoji dovoljno dokaza koji podržavaju tvrdnju inženjera da treba promeniti uslove garancije.

### 2.2 t-test

12. (v) Srednje vreme života komercijalne baterije za uzorak od 33 baterije (isti tip i proizvođać) je 99.5h, dok je standardna devijacija 18.49h. Fabrika očekuje da baterije traju 100h, dok inženjerima deluje da to očekivanje nije baš opravdano. Koristeći $\alpha=0.05$, detaljno opisati da li su inženjeri u pravu da budu zabrinuti. Obrazložiti izbor testa.

13. (v) Da bi se testirala hipoteza da dva standardna turbopunjača \(A\) i \(B\) imaju isto vreme reakcije na gas, uzet je slučajni uzorak od 7 automobila koji su opremljeni gorepomenutim turbopunjačima i izmerena su vremena reakcije na gas. Rezultati su sledeći:

| **Automobil** | 1     | 2     | 3     | 4     | 5     | 6     | 7     |
|---------------|-------|-------|-------|-------|-------|-------|-------|
| Vreme reakcije za A: $R_1$ | 0.223 | 0.212 | 0.201 | 0.205 | 0.216 | 0.211 | 0.209 |
| Vreme reakcije za B: $R_2$ | 0.208 | 0.207 | 0.203 | 0.204 | 0.205 | 0.202 | 0.206 |
| D = $R_1 - R_2$              | 0.015 | 0.005 | -0.002 | 0.001 | 0.011 | 0.009 | 0.003 |


Kakav zaključak o hipotezi možemo doneti? Detaljno obrazložiti izabrani test hipoteza.

14. Dva različita metoda analize korišćena su za određivanje nivoa nečistoća prisutnih u određenoj aluminijumskoj leguri avionskog kvaliteta. Analizirano je 8 uzoraka korišćenjem oba metoda. Da li dostupni dokazi ukazuju na to da oba metoda dovode do istih rezultata? Detaljno obrazložiti izabrani test hipoteza.

| **Uzorak legure** | 1    | 2    | 3    | 4     | 5    | 6    | 7    | 8    |
|-------------------|------|------|------|-------|------|------|------|------|
| Test 1            | 1.24 | 1.23 | 1.24 | 1.20  | 1.21 | 1.22 | 1.23 | 1.22 |
| Test 2            | 1.23 | 1.20 | 1.20 | 1.21  | 1.20 | 1.20 | 1.21 | 1.25 |
| D = Test1 - Test2 | 0.01 | 0.03 | 0.04 | -0.01 | 0.01 | 0.02 | 0.02 | -0.03 |


### 2.3 $\chi^2$ test

15. (v)  Direktor škole želi da sazna tokom kojih dana u nedelji učenici najčešće izostaju. On očekuje da će učenici izostajati podjednako tokom petodnevne školske nedelje. Direktor bira slučajan uzorak od 100 nastavnika i pita ih kog dana u nedelji su primetili najveći broj izostanaka učenika. Posmatrani i očekivani rezultati prikazani su u tabeli ispod. Na osnovu ovih rezultata, da li se dani sa najvećim brojem izostanaka javljaju sa jednakim frekvencijama, kao što je direktor pretpostavio? Koristiti nivo značajnosti od $5\%$.

| **Dan**         | Ponedeljak | Utorak | Sreda | Četvrtak | Petak |
|-----------------|------------|--------|-------|----------|-------|
| Posmatrani izostanci | 23         | 16     | 14    | 19       | 28    |
| Očekivani izostanci  | 20         | 20     | 20    | 20       | 20    |


16. (v) Standardna devijacija rezultata ispita na odeljenju za matematiku na lokalnom koledžu iznosi 8.6.  
Profesor veruje da je ova vrednost u realnosti manja. On uzima uzorak od 20 rezultata ispita i nalazi da je standardna devijacija 6.9.  
Da li ovaj uzorak pruža dovoljno dokaza da se zaključi da je prava standardna devijacija manja od 8.6?

### 2.4 Confidence intervals (CI)

17. (v) Iz slučajnog uzorka od 100 muškaraca dobijena je prosečna visina od 180 cm. Varijansa populacije je $\sigma^2 = 49~\text{cm}^2$. Pronaći 95\% CI za $\mu$, prosečnu visinu populacije.
18. (v) Vek trajanja 10 sijalica posmatran je (u satima) i iznosi:
    
| 1052 | 1271 | 836 | 962 | 1019 | 1051 | 512 | 1027 | 1219 | 1040 | 
|------|------|------|------|------|------|------|------|------|------|

Pretpostavljajući da je standardna devijacija za sijalice ovog tipa $\sigma = 80~\text{h}$,  

* **(a)** Pronaći 95\% CI za prosečan vek trajanja ovog tipa sijalica;  

* **(b)** Pronaći procenat intervala poverenja koji ima ukupni raspon od 80 h;  

* **(c)** Odrediti veličinu uzorka $n$ koja je potrebna da bi se raspon 95\% intervala poverenja sveo na 50 h.
  
## 3. Maximum likelihood estimator (MLE)

19. (v) Ako se eksperiment sastoji od $n$ Bernoulli trial sa verovatnoćom uspeha p, odrediti MLE.
20. (v) Procena metodom MLE može se primeniti na vektorski parametar. Za jednostavan slučajni uzorak od $n$ normalnih slučajnih promenljivih, iskoristiti osobine eksponencijalne funkcije zarad pojednostavljivanja likelihood-a. Odrediti MLE.


