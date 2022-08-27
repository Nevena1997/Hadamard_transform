# Naučno izračunavanje
## Walsh–Hadamard transform

**Autor:** Nevena Vilotić

**Programski jezik:** Python

Hademardova transformacija (Hadamard transform, Walsh–Hadamard transform) je primer klase koja generalizuje Furijeovu transformaciju.
 Ona izvodi ortogonalnu, simetričnu, involutivnu, linearnu operaciju nad $2^{m}$ realnih (kompleksnih) brojeva.
 
 Hadamardova transformacija se može smatrati izgrađenom od diskretnih Furijeovih transformacija (DFT) veličine 2 i zapravo je ekvivalentna višedimenzionalnom DFT-u veličine 2 × 2 × ⋯ × 2 × 2.
 
 Matrica Hademardove transformacije se dobija rekurentnom relacijom:

$$H_0 = + (1)$$

$$H_m = \frac{1}{\sqrt{2}} \begin{pmatrix}H_{m-1} & H_{m-1}\\
H_{m-1} & -H_{m-1}
\end{pmatrix}$$

U klasičnoj primeni, Hadamardova transformacija se može izračunati u $nlogn$ operacija $(n = 2^m)$, koristći algoritam brze Hadamardove transformacije.
U kvantnom domenu, Hadamardova se transformacija može izračunati u $O(1)$ vremenu.

Hadamardova transformacija se takođe koristi u kriptografiji, kao i u procesiranje signala i algoritmima za kompresiju podataka. U  aplikacijama za video kompresije, obično se koristi u obliku sume apsolutno transformiranih razlika. To je takođe presudan deo Groverovog i Šorovog algoritma u kvantnom računanju. Hadamardova se primenjuje i u eksperimentalnim tehnikama poput NMR, masovne spektrometrije i kristalografije.
