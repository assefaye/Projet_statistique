Voici la structure demandée, sans espaces supplémentaires, tout en intégrant vos images :

---

## Construction d'un Intervalle de Confiance pour les Dépenses Annuelles au Restaurant
Pour construire un intervalle de confiance pour la moyenne des dépenses annuelles au restaurant, nous allons suivre plusieurs étapes clés. Voici les étapes détaillées avec des explications :

### Étapes pour Construire l'Intervalle de Confiance
#### 1. Collecte des données :
- **Taille de l'échantillon** (\( n \)) = 1 402 ménages  
- **Moyenne des dépenses** (\( \bar{x} \)) = 1 863 $  
- **Écart type corrigé** (\( s \)) = 558 $  
#### 2. Choisir le niveau de confiance :
- **Niveau de confiance choisi** = 90 %  
- Pour un niveau de confiance de 90 %, le critère de confiance (\( \alpha \)) est 0,10. Cela signifie une erreur de chaque côté de 0,05 (0,10 / 2).
#### 3. Trouver la valeur critique :
- Pour un niveau de confiance de 90 %, nous utilisons la distribution normale (puisque \( n \) est grande). La valeur critique \( z \) correspondante peut être trouvée dans une table de distribution normale ou calculée.

<img width="167" height="32" alt="Capture d’écran 2025-11-12 à 14 59 07" src="https://github.com/user-attachments/assets/6f7bfc90-29cf-43ba-8259-6aae6290f41f" />

[ z_{0.05} \approx 1,645 ]

#### 4. Calculer l'erreur standard de la moyenne (ESM) :
L'erreur standard de la moyenne se calcule comme suit :

\[
ESM = \frac{s}{\sqrt{n}} = \frac{558}{\sqrt{1402}} \approx \frac{558}{37,45} \approx 14,91
\]

<img width="395" height="80" alt="Capture d’écran 2025-11-12 à 15 00 39" src="https://github.com/user-attachments/assets/858af563-102f-46d0-b31b-27a7f825a1ee" />

#### 5. Calculer la marge d'erreur (ME) :
La marge d'erreur se calcule comme suit :

\[
ME = z \times ESM = 1,645 \times 14,91 \approx 24,48
\]

<img width="400" height="58" alt="Capture d’écran 2025-11-12 à 15 01 31" src="https://github.com/user-attachments/assets/8b88f72b-0b58-41d1-b2f1-d93a24e77e41" />

#### 6. Construire l'intervalle de confiance :
- **Limite inférieure** :

\[
\bar{x} - ME = 1863 - 24,48 \approx 1838,52
\]

<img width="348" height="63" alt="Capture d’écran 2025-11-12 à 15 02 30" src="https://github.com/user-attachments/assets/286ce3bf-4e7e-4e97-ba92-930aa2efacd2" />

- **Limite supérieure** :

\[
\bar{x} + ME = 1863 + 24,48 \approx 1887,48
\]

<img width="340" height="54" alt="Capture d’écran 2025-11-12 à 15 03 19" src="https://github.com/user-attachments/assets/1c410e8f-10ce-4556-9364-83ef6c7c54df" />

### Résultat Final
L'intervalle de confiance à 90 % pour le montant annuel moyen des dépenses au restaurant de l’ensemble des ménages est donc :

\[
[1838,52 \, \$ ; 1887,48 \, \$]
\]

<img width="215" height="50" alt="Capture d’écran 2025-11-12 à 15 04 27" src="https://github.com/user-attachments/assets/e7caade2-dcec-45da-b899-0f8e9b7d4ec9" />

### Interprétation
Cela signifie que nous sommes 90 % confiants que la moyenne des dépenses des ménages pour l'ensemble de la population se situe entre 1 838,52 $ et 1 887,48 $ par an au restaurant.

--- 

Cette version est compacte et conserve toutes les informations nécessaires ainsi que vos images. Si vous avez besoin d'autres ajustements, faites-le moi savoir !
