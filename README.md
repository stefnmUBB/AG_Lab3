# AG_Lab3

Cerința:

<i>

<h3>Problema 1</h3>
  <h4>Cerința</h4>
<p>Având dat un graf orientat ponderat și un vârf sursă, calculați costul minim de la vârful sursă până la
fiecare vârf accesibil din graf. Implementarea trebuie să fie eficientă din punctul de vedere al memoriei
folosite și al timpului de execuție. (Implementați un algoritm de drum minim în graf: Bellman- Ford,
  Dijkstra.)</p>
<h4>Formatul sursei</h4>
<p>Soluția va fi implementată în limbajul de programare C++. Numele sursei va fi „p1.cpp”. Căile fișierelor
de intrare și de ieșire vor fi date ca parametrii în linia de comandă, prima fiind calea fișierului de intrare
  și a doua fiind calea fișierului de ieșire.</p>
<h4>Formatul fișierului de intrare</h4>
<p>Fișierul de intrare conține pe prima linie 3 numere separate prin spațiu: V E S. V reprezintă
numărul de vârfuri pentru graful dat. E reprezintă numărul arcelor din graf. S este nodul sursă
de la care se vor calcula costurile minime.
Următoarele E linii vor conține câte 3 numere separate prin spațiu, reprezentând câte un arc: x
y w. x este nodul sursă al arcului, y este nodul destinație, iar w este ponderea. Indexarea
vârfurilor se face de la 0.
</p>
Valorile din fișierul de intrare se încadrează în următoarele limite:
  
- 1 ≤ 𝑉 ≤ 10000
- 0 ≤ 𝐸 ≤ 150000
- 0 ≤ 𝑆 < 𝑉
- 0 ≤ 𝑥 < 𝑉
- 0 ≤ 𝑦 < 𝑉
- 1 ≤ 𝑤 ≤ 100
             
<h4>Formatul fișierului de ieșire</h4>

Fișierul de ieșire va conține o singură linie cu N valori separate prin spațiu. Valoarea de pe
poziția i reprezintă costul drumului de cost minim de la vârful sursă S până la vârful i. Dacă
vârful i este inaccesibil din vârful S, atunci pe poziția i se va scrie șirul de caractere „INF”. 

| Fișier de intrare        |
|---------|
| 5 7 0 <br/>0 2 4<br/>0 3 1<br/>1 0 1<br/>1 2 4<br/>2 0 1<br/>2 3 1<br/>3 4 1|

| Fișier de ieșire        |
|---------|
| 0 INF 4 1 2|

  
</i>
