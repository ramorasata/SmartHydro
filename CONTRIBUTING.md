# Contribution à SmartHydro

Merci de l'intérêt que vous portez à **SmartHydro** ! Ce blog et son dépôt associé ont pour objectif de partager des connaissances, des scripts et des méthodes fiables entre ingénieurs hydrauliciens. 

Les contributions de la communauté (corrections de bugs, améliorations de scripts, suggestions méthodologiques) sont les bienvenues. Pour garantir la qualité technique du contenu et la clarté juridique du projet, merci de suivre les lignes directrices ci-dessous.

---

## 1. Propriété Intellectuelle et Cession de Droits

En proposant une contribution à ce dépôt (via une *Pull Request* ou une *Issue*), vous acceptez explicitement les conditions suivantes :
* **Pour le Code Source & Scripts :** Vous acceptez que votre code soit publié et distribué sous la **Licence MIT** du projet.
* **Pour les Textes & Documentation :** Vous acceptez que vos écrits soient publiés sous la licence **Creative Commons CC BY-NC-ND 4.0**.
* Vous garantissez que vous êtes l'auteur original du contenu soumis ou que vous disposez des droits nécessaires pour le publier sous ces licences.

---

## 2. Comment Contribuer ?

### A. Signaler une anomalie ou suggérer une amélioration (Issues)
Si vous identifiez une erreur dans un script de calcul (formule de Manning-Strickler mal implémentée, erreur de syntaxe, problème de convergence hydrodynamique, etc.) ou une coquille dans un article :
1. Allez dans l'onglet **Issues** de GitHub.
2. Vérifiez qu'une feuille similaire n'est pas déjà ouverte.
3. Ouvrez une nouvelle *Issue* en décrivant précisément le problème, l'impact sur le calcul et, si possible, la correction théorique ou technique requise.

### B. Proposer une modification directe (Pull Requests)
Pour soumettre directement une modification de code ou de texte :
1. **Forkez** le dépôt SmartHydro sur votre compte GitHub.
2. Créez une branche thématique décrivant votre modification (ex: `fix-perte-de-charge` ou `feature-calcul-debit-crue`).
3. Effectuez vos modifications dans votre branche.
4. Soumettez une **Pull Request (PR)** vers la branche principale (`main` ou `master`) du dépôt SmartHydro.
5. Décrivez clairement dans la PR les changements apportés et les justifications physiques ou empiriques de vos calculs.

---

## 3. Standards de Qualité et Rigueur Technique

L'hydraulique est une science d'ingénierie qui engage la sécurité des biens et des personnes. Nous appliquons donc des critères de révision rigoureux :
* **Vérification des calculs :** Tout script, formule ou modèle modifié doit être testé en amont. Indiquez dans votre description si les résultats ont été confrontés à des cas d'école ou des abaques connus.
* **Lisibilité du code :** Commentez vos scripts (Python, R, VBA, MATLAB ou autre) de manière claire. Nommez vos variables explicitement en accord avec les notations usuelles de la mécanique des fluides (ex: `Q` pour le débit, `Rh` pour le rayon hydraulique, `Ks` pour le coefficient de Strickler).
* **Clarté rédactionnelle :** Pour le contenu textuel, maintenez un ton professionnel, technique et pédagogique, adapté à un public d'ingénieurs et de techniciens.

---

## 4. Code de Conduite

Les échanges au sein des *Issues* ou des *Pull Requests* doivent rester courtois, constructifs et basés sur des arguments scientifiques ou techniques factuels. Le respect mutuel entre pairs est une condition *sine qua non* pour participer à ce projet.