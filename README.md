# Naučno izračunavanje
## Walsh–Hadamard transform

**Autor:** Nevena Vilotić

**Programski jezik:** Python

Hadamardova transformacija (Hadamard transform, Walsh–Hadamard transform) je primer klase koja generalizuje Furijeovu transformaciju.
 Ona izvodi ortogonalnu, simetričnu, involutivnu, linearnu operaciju nad $2^{m}$ realnih (kompleksnih) brojeva.
 
 Matrica Hademardove transformacije se dobija rekurentnom relacijom:

$$H_0 = + (1)$$

$$H_m = \frac{1}{\sqrt{2}} \begin{pmatrix}H_{m-1} & H_{m-1}\\
H_{m-1} & -H_{m-1}
\end{pmatrix}$$

Složenost Hadamardove transofrmacije je $n^2, (n = 2^m)$,
U klasičnoj primeni, Hadamardova transformacija se može izračunati u $nlogn$ operacija $(n = 2^m)$, koristći algoritam brze Hadamardove transformacije.
U kvantnom domenu, Hadamardova se transformacija može izračunati u $O(1)$ vremenu.

Hadamardova transformacija se koristi u kriptografiji, kao i u procesiranje signala i algoritmima za kompresiju podataka. U  aplikacijama za video kompresije, obično se koristi u obliku sume apsolutno transformiranih razlika. To je takođe presudan deo Groverovog i Šorovog algoritma u kvantnom računanju. Hadamardova se primenjuje i u eksperimentalnim tehnikama poput NMR, masovne spektrometrije i kristalografije.
