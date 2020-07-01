# LSZE-TEST

## Logika és számításelmélet kvíz

---

f(n)=n^4 + 2n g(n)=(2/3)^n  
1\. állítás: f(n)=Ω(g(n))  
2\. állítás: g(n)=Ω(f(n))  
Melyik igaz?

- csak az 1. (tipp)
- ~~csak a 2.~~
- mindkettő
- egyik se

---

f(n)=9n<sup>4</sup>+5n g(n)=2<sup>n-2</sup>  
1\. állítás: f(n)=O(g(n))  
2\. állítás: g(n)=O(f(n))  
Melyik igaz?  

- csak az 1. (tipp)
- ~~csak a 2.~~
- mindkettő
- egyik se

---

f(n)=log<sub>2</sub>(n/2), g(n)=3log<sub>2</sub>(2n)  
1\. állítás: f(n)=O(g(n))  
2\. állítás: g(n)=O(f(n))  
Melyik igaz?  

- ~~csak az 1.~~
- csak a 2.
- mindkettő (tipp)
- egyik se

---

f(n)=3log<sub>8</sub>n, g(n)=5log<sub>2</sub>n.  
1\. állítás: f(n)=Ω(g(n))  
2\. állítás: g(n)=Ω(f(n))  
Melyik igaz?  

- csak az 1.
- ~~csak a 2.~~
- mindkettő
- egyik se

---

Tegyük fel, hogy a nemnegatív értékű f(n) és g(n) függvényekre f(n)/g(n)->1/3. Ekkor  
1\. állítás: f(n)=O(g(n))  
2\. állítás: g(n)=O(f(n))  
Melyik állítás igaz?

- csak az 1.
- csak a 2.
- mindkettő
- ~~egyik se~~

---

Legyenek f, g: N->R0+ függvények.  
1\. Ha ∃ c>0 és N∈N, hogy ∀n≥N-re f(n)≥cg(n), akkor f(n)=Θ(g(n)).  
2\. Ha f(n)=Θ(g(n)), akkor ∃ c>0 és N∈N, hogy ∀n≥N-re f(n)≥cg(n).  
Melyik állítás igaz?  
(N a természetes számok, R0+ a nemnagatív valós számok halmaza.)  

- csak az 1.
- csak a 2.
- mindkettő
- ~~egyik se~~

---

Legyen M = (Q, Σ, Γ, δ, q0 , qi , qn) egy tetszőleges egyszalagos Turing-gép. Ha δ(q,a)=(r,c,R), akkor mi lesz az ubqav konfiguráció rákövetkezője?  
(q,r∈Q, u,v ∈Γ*, v≠ε, a,b,c∈Γ)

- ubrcv
- urcbv
- **ubcrv**
- ucbrv

---

Legyen M = (Q, Σ, Γ, δ, q0 , q<sub>i</sub> , q<sub>n</sub>) egy tetszőleges egyszalagos Turing-gép. Ha δ(q,a)=(r,b,L), akkor mi lesz az ucqav konfiguráció rákövetkezője?  
(q,r∈Q, u,v ∈Γ*, v≠ε, a,b,c∈Γ)

- ~~uvrbv~~
- urcbv
- ucrbLv
- ucbrv

---

Legyen M = (Q, Σ, Γ, δ, q0 , q<sub>i</sub> , q<sub>n</sub>) egy tetszőleges egyszalagos Turing-gép. Ha δ(q,a)=(r,c,R), akkor mi lesz az ubqav konfiguráció rákövetkezője?  
(q,r∈Q, u,v ∈Γ*, v≠ε, a,b,c∈Γ)  

- ubrcv
- urcbv
- **ubcrv**
- ucbrv

---

Legyen M = (Q, Σ, Γ, δ, q0 , q<sub>i</sub> , q<sub>n</sub>) egy NEMDETERMINISZTIKUS Turing gép és u∈Σ*.  
1\. állítás: ha létezik többlépéses konfigurációátmenet az u-hoz tartozó kezdőkonfigurációból egy elfpgadó konfigurációba, akkor u eleme L(M)-nek.  
2\. állítás: ha létezik többlépéses konfigurációátmenet az u-hoz tartozó kezdőkonfigurációból egy elutasító konfigurációba, akkor u nem eleme L(M)-nek.  
Melyik állítás igaz?  

- csak az 1.
- csak a 2.
- mindkettő
- egyik se

---

Melyik lehet egy M = ({q0,q1,q2}, {0,1}, {0,1,#,\_}, δ, q0 , qi , qn) egyszalagos Turing-gép kezdőkonfigurációja?  
q0\_ vagy q001#01_? (_jelöli a blank karaktert)  

- csak q0_ (tipp)
- csak q001#01_
- ~~mindkettő~~
- egyik se

---

Melyik lehet egy M = ({q0,q1,q2}, {a,b}, Γ, δ, q0 , q<sub>i</sub> , q<sub>n</sub>) egyszalagos Turing-gép kezdőkonfigurációja?  
q<sub>1</sub>aab vagy aabq<sub>1</sub>?

- csak az 1.
- csak a 2.
- ~~mindkettő~~
- egyik se

---

Legyen  M = (Q, Σ, Γ, δ, q0 , qi , qn) egy tetszőleges kétszalagos Turing-gép. Ha δ(q,a,b)=(r,c,d,L,S), akkor mi lesz a (q,ue,av,x,by) konfiguráció rákövetkezője?  
(u,v,x,y∈ ​Γ*, v,y≠ε, a,b,c,d,e∈Γ)  

- (r,u,ebv,xd,y)
- ~~(r,uec,v,x,dy)~~
- (r,u,ecv,xd,y)
- (r,u,ecv,x,dy)

---

Legyen  M = (Q, Σ, Γ, δ, q0 , qi , qn) egy tetszőleges kétszalagos Turing-gép. Ha δ(q,a,b)=(r,c,d,R,L), akkor mi lesz a (q,u,av,xe,by) konfiguráció rákövetkezője?  
(u,v,x,y∈ ​Γ*, v,y≠ε, a,b,c,d,e∈Γ)  

- (r,uc,v,x,edy)
- ~~(r,uc,v,xe,dy)~~
- (r,ua,v,x,eby)
- (r,uc,v,xed,y)

---

Legyen  M = (Q, Σ, Γ, δ, q0 , qi , qn) egy tetszőleges kétszalagos Turing-gép. Mi az abb szóhoz tartozó kezdőkonfiguráció?

- (q0,ε, abb,ε,_) (tipp)
- ~~(q0,abb,_)~~
- (q0,ε,abb,ε,ε)
- (q0,abb,ε)

---

Legyen M = (Q, Σ, Γ, δ, q0 , q<sub>i</sub> , q<sub>n</sub>) egy 2 szalagos Turing gép és jelölje _ a blank karaktert (_∈Γ\Σ).  
1\. M ε bemenethez tartozó kezdőkonfigurációja (q<sub>0</sub>,ε,_,ε,_).  
2\.(q<sub>0</sub>,ε,ε,ε,ε) az M egy elutasító konfigurációja.  
Melyik állítás igaz?  

- **csak az 1.**
- csak az 2.
- mindkettő
- egyik se

---

1\. állítás: Egy 2-szalagos Turing gép állapothalmaza tetszőleges olyan halmaz lehet, ami tartalmaz egy kezdő, egy elfogadó és egy elutasító állapotot.  
2\. állítás: Legyen M = (Q, Σ, Γ, δ, q0 , q<sub>i</sub> , q<sub>n</sub>) egy tetszőleges 2-szalagos determinisztikus Turing gép. Ekkor az átmenetfüggvényére δ:( Q \\{ q<sub>i</sub>,q<sub>n</sub>}) x Γ<sup>2</sup> -> Q<sup>2</sup> x Γ<sup>2</sup> {L, S, R}<sup>2</sup> teljesül.  
Melyik állítás igaz?  

- ~~csak az 1.~~
- csak a 2.
- mindkettő
- egyik se

---

Legyen L⊆{0,1}* egy nyelv. Az M determinisztikus Turing gépről tudjuk, hogy ∀u∈L-re elfogadó konfigurációba jut.  
1\. következtetés: Tehát M felismeri L-et  
2\. következtetés: Tehát M eldönti L-et.  
Melyik következtetés helyes?

- ~~csak az 1.~~
- csak a 2.
- ~~mindkettő~~
- egyik se (tipp)

---

Legyen L⊆{0,1}* egy nyelv. Az M determinisztikus Turing gépről tudjuk, hogy pontosan az L-beli szavakra jut elfogadó konfigurációba.  
1\. Tehát M eldönti az L nyelvet.  
2\. Tehát L∈R.  
Melyik következtetés helyes?  

- csak az 1.
- csak a 2.
- mindkettő
- **egyik se**

---

(2)
Egy M determinisztikus Turing gép pontosan az {ab<sup>n</sup>a|n>0} nyelv szavaira jut qn-be.  
1\. L(M) az {ab<sup>n</sup>a|n>0} nyelv komplementere.  
2\. M eldönti az {ab<sup>n</sup>a|n>0} nyelv komplementerét.  
Melyik következtetés helyes?

- ~~csak az 1.~~
- ~~csak a 2.~~
- mindkettő
- egyik se (tipp)

---

Egy determinisztikus Turing gép pontosan az {a<sup>n</sup>b<sup>n</sup>|n>0} nyelv szavaira jut q<sub>i</sub>-be.  
1\. állítás: M eldönti az {a<sup>n</sup>b<sup>n</sup>|n>0} nyelvet.  
2\. állítás: L(M)={a<sup>n</sup>b<sup>n</sup>|n>0}.  
Melyik állítás igaz?  

- csak az 1.
- **csak a 2.**
- ~~mindkettő~~
- egyik se

---

(2)  
Ha L eldönthető egy  f(n)=3<sup>n</sup>+2n<sup>2</sup> időkorlátos determinisztikus Turing géppel, akkor  
1\. Tehát L P-beli nyelv  
2\. Tehát L nem P-beli nyelv  
Melyik következtetés helyes?

- ~~csak az 1.~~
- ~~csak a 2.~~
- mindkettő
- egyik se (tipp)

---

Ha L eldönthető egy f(n)=2n+3log<sub>2</sub>n időkorlátos determinisztikus Turing géppel, akkor  
1\. L P-beli nyelv  
2\. L NP-beli nyelv  
Melyik következtetés helyes?  

- csak az 1.
- csak a 2.
- **mindkettő**
- egyik se

---

Melyik az az állítás, amelyikről NEM tudjuk kijelenteni, hogy igaz?  

- Minden determinisztikus Turing-géphez van vele ekvivalens nemdeterminisztikus Turing-gép.  
- Minden nemdeterminisztikus Turing-géphez van vele ekvivalens determinisztikus Turing gép.  
- Minden polinom időigényű 3 szalagos determinisztikus Turing-géphez van vele ekvivalens polinom időigényű 2 szalagos determinisztikus Turing-gép.
- **Minden polinom időigényű nemdeterminisztikus Turinghez van vele ekvivalens polinom időigényű determiniszitkus Turing-gép.**

---

1\. Ha A megszámlálható, akkor létezik A-ból a természetes számok halmazába injektív leképezés.  
2\. Ha nem létezik A-ból  a természetes számok halmazába injektív leképezés, akkor A continuum számosságú.  
Melyik állítás igaz?

- csak az 1.
- csak a 2.
- mindkettő
- ~~egyik se~~

---

1\. állítás: {0,1}* számossága contunuum.  
2\. állítás: a {0,1} feletti nyelvek halmazának számossága continuum.  
Melyik állítás igaz?  

- csak az 1.
- **csak a 2.**
- mindkettő
- egyik se

---

Legyen M egy nemdeterminisztikus Turing gép.  
1\. Ha egy u szóhoz tartozó nemdeterminisztikus számı́tási fának van olyan levele, ami elfogadó konfiguráció, akkor M elfogadja u-t.  
2\. Ha minden n-re minden L(M)-beli n hosszú u input szóra az u-hoz tartozó nemdeterminisztikus számı́tási fa véges és minden levele a gyökértől legfeljebb 2n2 távolságra van, akkor M f(n)=2n2 időkorlátos.  
Melyik állítás igaz?  

- _csak az 1._
- ~~csak a 2.~~
- mindkettő
- egyik se

---

1\. Legyen M egy n<sup>2</sup> időkorlátos 2-szalagos determinisztikus Turing gép. Ekkor megadható egy M-mel ekvivalens O(n<sup>4</sup>) időkorlátos M' egyszalagos determinisztikus Turing gép.  
2\. Legyen M egy n<sup>2</sup> időkorlátos egyszalagos nemdeterminisztikus Turing gép. Ekkor megadható egy M-mel ekvivalens O(n<sup>4</sup>) időkorlátos M' determinisztikus Turing gép.  
Melyik állításról tudjuk, hogy igaz?  

- **csak az 1.**
- csak a 2.
- mindkettő
- egyik se

---

Legyen M egy nemdeterminisztikus Turing gép.  
1\. Ha az u-hoz tartozó nemdeterminisztikus számı́tási fának van olyan levele, ami elfogadó konfiguráció, akkor M elfogadja u-t.  
2\. Ha minden n-re minden L(M)-beli n hosszú u input szóra az u-hoz tartozó nemdeterminisztikus számı́tási fának van olyan gyökerétől legfeljebb 2n távolságra lévő levele, ami elfogadó konfiguráció, akkor M f(n)=2n időkorlátos.  
Melyik állítás igaz?  

- **csak az 1.**
- csak a 2.
- mindkettő
- egyik se

---

Egy M nemdeterminisztikus Turing gépre és egy L nyelvre L(M)=L teljesül. Mire következtetünk ebből?

- L ∈ R
- L ∈ RE (tipp)
- ~~mindkettőre következtethetünk~~
- egyikre sem következtethetünk

---

Egy M nemdeterminisztikus Turing gép egy u szóra vett nemdeterminisztikus számítási fájában 4 ág van:  
egy elfogadó, 2 elutasító és egy nem termináló  
Ekkor

- **u ∈ L(M)**
- u nem eleme L(M)-nek
- egyik következtetés se helyes

---

1\. állítás: Van olyan nem Turing-felismerhető nyelv, ami eldönthető.  
2\. állítás NP (valódi)⊆ RE.  

- csak az 1.
- **csak a 2.**
- mindkettő
- egyik se

---

1\. állítás: Van olyan eldönthetetlen nyelv, ami Turing-felismerhető.  
2\. állítás R (valódi)⊆ NP.  
Melyik állítás igaz?  

- **csak az 1.**
- csak a 2.
- mindkettő
- egyik se

---

1\. állítás: Minden nyelv felismerhető Turing géppel.  
2\. állítás: Van eldönthetetlen nyelv.  
Melyik állítás igaz?  

- csak az 1.
- **csak a 2.**
- mindkettő
- egyik se

---

1\. van olyan eldönthető nyelv, amire L<sub>PMP</sub> visszavezethető.  
2\. L<sub>PMP</sub>  komplementere RE-ben van.  
Melyik állítás igaz?  

- ~~csak az 1.~~
- csak a 2.
- mindkettő
- egyik se (tipp)

---

1\. van olyan eldönthető nyelv, amire L<sub>u</sub> visszavezethető.  
2\. L<sub>u</sub>  komplementere RE-ben van.  
Melyik állítás igaz?

- csak az 1.
- csak a 2.
- mindkettő
- **egyik se**

---

1\. L<sub>átló</sub> nem eleme NP-nek.
2\. L<sub>átló</sub> komplementere eldönthetetlen.  
Melyik állítás igaz?  

- csak az 1.
- csak a 2.
- mindkettő
- ~~egyik se~~

---

(2)
1\. L<sub>h</sub> 2. L<sub>PMP</sub> 3. L<sub>átló</sub> 4. TSP  
5\. RE-ben van, de nem R beli,  
6\. komplementere R-beli.  
7\. komplementere nem R-beli.  
8\. nincs RE-ben.  
Melyik egy helyes párosítás?  

- 1-7 2-6 3-8 4-5
- 1-8 2-7 3-5 4-6
- 1-7 2-6 3-5 4-8
- **1-5 2-7 3-8 4-6**

---

1\. L<sub>átló</sub> 2. L<sub>PMP</sub> 3. L<sub>u</sub> 4. TSP  
5\. RE-ben van, de nem R beli,  
6\. komplementere R-beli.  
7\. komplementere nem R-beli.  
8\. nincs RE-ben.  
Melyik egy helyes párosítás?  

- ~~1-8 2-6 3-7 4-5~~
- 1-5 2-7 3-8 4-6
- 1-8 2-7 3-5 4-6 (tipp)
- 1-5 2-6 3-7 4-8

---

(2)
Legyen D={(u,v),(w,x)} (u,v,w,x,y,z∈Σ+) a Post Megfelelkezési Probléma egy bemenete. (Az első dominón u a felső szó, v az alsó, a másodikon w a felső, x az alsó.) Ekkor  
1\. D bármely megoldása legfeljebb 2 dominóból áll.  
2\. Ha |u|>|v| és |w|>|x|, akkor D-nek nincs megoldása.  
Melyik állítás igaz?  

- csak az 1.
- **csak a 2.**
- mindkettő
- egyik se

---

Legyen D={(u,v),(w,x),(y,z)} (u,v,w,x,y,z∈Σ+) a Post Megfelelkezési Probléma egy bemenete. Tegyül fel, hogy wuu=xvv.  
Következik-e ebből, hogy D-nek van megoldása?

- **igen**
- nem következik
- mivel a probléma eldönthetetlen, ezért ezt nem tudjuk eldönteni

---

1\. Polinom időben eldönthető, hogy egy nulladrendű formula tautológia-e.  
2\. Eldönthető, hogy egy elsőrendű formula logikailag igaz-e.  
A fentiek közül melyik állításról jelenthető ki, hogy igaz?  

- csak az 1.
- ~~csak a 2.~~
- mindkettő
- egyik se

---

1\. A nulladrendű logika kielégíthetetlen formuláinak nyelve P-beli.  
2\. Az elsőrendű logika logikailag igaz formuláinak nyelve eldönthetetlen.  
A fentiak közül melyik állításról jelenthető ki, hogy igaz?  

- csak az 1.
- csak a 2. (tipp)
- ~~mindkettő~~
- egyik se

---

Az alábbi nyelvek közül melyik NEM NP-beli?  

- ELÉR (tipp)
- ~~2SAT~~
- L<sub>ECF</sub>
- ~~TSP~~

---

Az alábbi nyelvek közül melyik NEM NP-beli?  

- GRÁFIZOMORFIZMUS (tipp)
- ~~L<sub>h</sub>~~
- ~~TSP~~
- ~~2SAT~~

---

Az alábbiak közül melyik elsőrendű formula egy olyan elsőrendű logikában, ahol f egy függvényjel, p pedig egy predikátumszimbólum (mindkettő 2 aritású; x és y individuumváltozók)?  
1\. ∀xf(x,a)  
2\. p(x,y)∨p(f(y,y),x)  

- csak az 1.
- csak a 2.
- ~~mindkettő~~
- egyik se

---

1\. Rice tétele alapján eldönthetetlen, hogy egy Turing gép a {01,11,110} nyelvet ismeri-e fel.  
2\. Rice tétele alapján eldönthetetlen, hogy egy Turing gép rekutrívan felsorolható nyelvet ismeri-e fel.  
Melyik állítás igaz?  

- csak az 1.
- ~~csak a 2.~~
- mindkettő
- egyik se

---

1\. Ha P=NP, akkor 3SZÍNEZÉS P-beli.  
2\. Ha 3SZÍNEZÉS P-beli, akkor P=NP.  
Melyik állítás igaz?  

- ~~csak az 1.~~
- ~~csak a 2.~~
- mindkettő (tipp)
- egyik se

---

1\. Ha 2SZÍNEZÉS P-beli, akkor P=NP.  
2\. Ha LEFOGÓ PONTTHALMAZ P-beli, akkor P=NP.  
Melyik állítás igaz?  

- csak az 1.
- **csak a 2.**
- mindkettő
- egyik se

---

1\. Ha 2SAT P-beli, akkor P=NP.
2\. Ha KLIKK P-beli, akkor P=NP.
Melyik igaz?

- ~~csak az 1.~~
- csak a 2.
- mindkettő
- egyik se

---

(2)
1\. Ha P=NP hamis, akkor  nem fogunk sohase polinomiális idejű, 3SAT-ot eldöntő algoritmust találni.  
2\. Ha P=NP hamis, akkor  nem fogunk tudni sohase LPMP-t eldöntő Turing gépet konstruálni.  
Melyik állítás igaz?  

- csak az 1.
- csak a 2.
- **mindkettő**
- egyik se

---

1\. Ha P=NP hamis, akkor  nem fogunk sohase polinomiális idejű 3SAT-t eldöntő algoritmust találni.  
2\. Ha P=NP hamis, akkor nem fogunk sohase az elsőrendű formilák kielégíthetetlenségét eldöntő algoritmust találni  
Melyik állítás igaz?

- ~~csak az 1.~~
- csak a 2.
- **mindkettő**
- egyik se

---

1\. Ha P=NP hamis, akkor van olyan NP\P-beli probléma, mai nem NP-teljes.  
2\. Ha P=NP, akkor PRÍMFAKTORIZÁCIÓ nem NP-köztes.  
Melyik állítás igaz?  

- csak az 1.
- csak a 2.
- mindkettő (tipp)
- ~~egyik se~~

---

(2)  
Egészítse ki a mondatot úgy, hogy az állítás igaz legyen!  
Ha ....., akkor P=NP.  

- ~~létezik NP-teljes probléma NP-ben~~
- ha TSP determinisztikus Turing géppel polinom időben eldönthető (tipp)
- minden NP-teljes probléma eldönthető
- ~~minden NP-beli probléma polinom időben visszavezethető egy NP-teljes problémára~~

---

Egészítse ki a mondatot úgy, hogy az állítás igaz legyen!  
Ha ....., akkor P=NP.  

- **nem létezik NP-köztes probléma NP-ben**
- ELÉR P-beli
- ha minden NP-teljes probléma eldönthető
- minden NP-beli probléma polinom időben visszavezethető egy NP-teljes problémára

---

(2)
Legyenek L és L' nyelvek. Az L eldönthetőségének bizonyításához elég:  

- **L' nem eleme R-nek és L'≤L**
- L' nem eleme R-nek és L≤L'
- ~~L' nem eleme RE-nek és L≤L'~~
- L' nem eleme RE-nek és L≤<sub>p</sub>L'

---

Legyenek L és L' nyelvek. L Turing-felismerhetőségének bizonyításához elég:

- ~~L' eleme R-nek és L'≤L~~
- L' eleme R-nek és L≤L' (tipp)
- L' eleme RE-nek és L≤L'
- L' eleme RE-nek és L'≤L

---

Legyenek L és L' nyelvek. Az L NP-beli nyelv NP-teljességének bizonyításához elég:

- L≤L', L' NP teljes
- L≤<sub>p</sub>L', L' NP teljes
- **L'≤<sub>p</sub>L, L' NP teljes**
- L'≤L, L' NP teljes

---

(2)  
1\. Ha L<sub>1</sub>≤<sub>p</sub> L<sub>2</sub> , akkor L<sub>1</sub>≤ L<sub>2</sub>.  
2\. Ha L<sub>1</sub>≤<sub>p</sub> L<sub>2</sub> , akkor L<sub>1</sub> komplementere ≤<sub>p</sub> L<sub>2</sub> komplementere.  
Melyik állítás igaz?

- ~~csak az 1.~~
- ~~csak a 2.~~
- mindkettő
- egyik se (tipp)

---

Legyen G egy tetszőleges 20 csúcsú egyszerű gráf.  
1\. Ha G-nek van 7 méretű klikkje akkor G-nek van 13 méretű független ponthalmaza.  
2\. Ha G-nek van 13 méretű független ponthalmaza, akkor van 7 méretű lefogó ponthalmaza.  
Melyik igaz?  

- csak az 1.
- **csak a 2.**
- mindkettő
- egyik se

---

Legyen G egy tetszőleges 20 csúcsú egyszerű gráf.  
1\. ha G 5-színezhető, akkor G 4-színezhető is.
2\. ha G-nek van 4 csúcsú független részhalmaza, akkor van 5 csúcsú is.
Melyik igaz?  

- ~~csak az 1.~~
- csak a 2.
- mindkettő
- egyik se (tipp)

---

Legyen G egy tetszőleges 10 csúcsú egyszerű gráf.  
1\. Ha G-nek van 4 méretű független ponthalmaza, akkor G-nek van 6 méretű klikkje.  
2\. Ha G-nek van 6 méretű lefogó ponthalmaza, akkor van 4 méretű független ponthalmaza.  
Melyik igaz?

- ~~csak az 1.~~
- csak a 2. (tipp)
- mindkettő
- egyik se

---

1\. állítás: Ha  <G,17>∈TSP, akkor G-ben van Hamilton kör.  
Legyen K<sub>33</sub> az a teljes (irányítatlan)  páros gráf, ahol mindkét csúcsosztály 3 csúcsból áll (azaz |A|=|B|=3, és a gráf élei éppen azon {a,b} párok, melyre a∈A és b∈B).  
2\. állítás: K<sub>33</sub>-ban van Hamilton kör.  
Melyik állítás igaz?  

- csak az 1. (tipp)
- ~~csak a 2.~~
- mindkettő
- ~~egyik se~~

---

1\. Ha  <G,11>∈TSP, akkor G-ben van Hamilton-kör.  
2\. Ha egy összefüggő irányítatlan G gráfban van 1-fokú csúcs, akkor G-ben nincs Hamilton kör
Melyik állítás igaz?  

- csak az 1. (tipp)
- ~~csak a 2.~~
- mindkettő
- ~~egyik se~~

---

(2)  
1\. A GRÁFIZOMORFIZMUS probléma NP-köztes.  
2\. Az NP-köztes problémák R-beliek.  
Melyik állítás az, amelyikről tudjuk, hogy igaz?  

- ~~csak az 1.~~
- csak a 2.
- mindkettő
- egyik se

---

1\. NL ⊆ coNL  
2\. A coNL tárbonyolultsági osztály az NL tárbonyolultsági osztály komplementere.  
Melyik állítás igaz?  

- csak az 1.
- csak a 2.
- mindkettő
- ~~egyik se~~

---

1\. coNL ⊆ R  
2\. A coNL időbonyolultság osztály az NP időbonyolultság osztály komplementere.  
Melyik állítás igaz?  

- csak az 1.
- csak a 2.
- ~~mindkettő~~
- egyik se

---

1\. A coNP időbonyolultsági osztály az NP időbonyolultsági osztály komplementere.  
2\. P ⊆ coNP  
Melyik állítás igaz?  

- csak az 1.
- **csak a 2.**
- mindkettő
- egyik se

---

Az alábbi formulák közül melyik 2KNF?  
1\.  (¬x ∨ y) ∧ (¬x ∨ ¬z ) ∧ (¬y ∨ z )  
2\. (¬x ∧ y) ∨ (¬x ∧ ¬z )  
(x,y,z ítéletváltozók)  

- **csak az 1.**
- csak a 2.
- mindkettő
- egyik se

---

Az alábbi formulák közül melyik 3KNF?  
1\. ((¬x ∨ y ∨ ¬z) ∧ (¬x ∨ ¬z ∨ ¬w)) ∨ (y ∧ z ∧ w)  
2\. (¬x ∧ y) ∨ (¬z ∧ ¬y )  
(x,y,z ítéletváltozók) 

- csak az 1.
- csak a 2.
- mindkettő
- **egyik se**

---

(2)
1. Nincs olyan nemdeterminisztikus offline Turing gép által O(n<sup>3</sup>)
tárral eldönthető nyelv, ami ne lenne eldönthető determinisztikus offline Turing gép által polinom tárral.  
2. Nincs olyan NP-beli nyelv, ami ne lenne eldönthető determinisztikus offline Turing gép által polinom
tárral.  
Melyik állítás igaz?  

- csak az 1.
- csak a 2.
- **mindkettő**
- ~~egyik se~~

---

1\. Van olyan nemdeterminisztikus offline Turing gép által O(n log n) tárral eldönthető nyelv, ami nem dönthető el determinisztikus offline Turing gép általá polinom tárral.  
2\. Van olyan NP-beli nyelv, ami nem dönthető el determinisztikus offline turing gép általá polinom tárral.  
Melyik állítás igaz?

- csak az 1.
- csak a 2.
- ~~mindkettő~~
- egyik se

---

1\. Ha L∈NSPACE( n<sup>2</sup> ), akkor L∈TIME( n<sup>2</sup> ).  
2\. Ha L∈NSPACE( n<sup>2</sup> ), akkor L∈SPACE( n<sup>5</sup> ).  
Melyik állításról tudjuk, hogy igaz?

- csak az 1.
- **csak a 2.**
- mindkettő
- ~~egyik se~~

---

1\. Ha L∈NSPACE( f(n) ), akkor L∈TIME( 2<sup>O( f(n) )</sup> ).  
2\. Ha L∈NSPACE( f(n) ), akkor L∈SPACE( f(n) ).  
Melyik állításról tudjuk, hogy igaz?

- csak az 1.
- ~~csak a 2.~~
- mindkettő
- egyik se

---

1\. állítás TIME(n<sup>2</sup>)⊆NSPACE(n<sup>2</sup>)  
2\. állítás SPACE(n<sup>2</sup>)⊆NTIME(n<sup>2</sup>)  
Melyikről lehet tudni, hogy igaz?

- csak az 1.-ről (tipp)
- csak a 2.-ról
- mindkettőről
- egyikről se

---

1\. RE számossága continuum  
2\. PSPACE számossága continuum  
Melyik állítás igaz?

- ~~csak az 1.~~
- ~~csak a 2.~~
- mindkettő
- **egyik se**

---

1\. állítás: { L | L⊆{0,1}* } számossága megszámlálhatóan végtelen.  
2\. állítás: A {0,1} inputábécéjű nemdeterminisztikus Turing gépek számossága megszámlálhatóan vételen  
Melyik állítás igaz?  

- csak az 1.
- csak a 2.
- ~~mindkettő~~
- egyik se

---

