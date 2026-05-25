# PROJET DE SITE WEB HYDRAULIQUE
Projet qui va décrire certaines expériences de modélisation hydraulique réalisées par Johary RAMORASATA

**Niveau 0 — Fondements transversaux**

- **Note 0.2** — *Énergie, charge et dégradation* : approfondit la décomposition de $H$, la nature physique de $\Delta H$ et le bilan énergétique — prolongement direct de la section « hydraulique en charge »
- **Note 0.3** — *Ouvrages et conditions aux limites* : seuils, vannes, pompages, réservoirs — prolongement de la section « transition de régime » et du callout sur l'hypothèse hydrostatique
- **Note 0.4** — *Analyse dimensionnelle et similitude* : fonde Reynolds, Froude, le diagramme de Moody et les lois d'échelle invoqués dans cette note — à lire pour comprendre d'où viennent ces nombres

**Niveau 1 — Entrées métier**

- **Note 1.A** — *Enjeux AEP* : décline le @tbl-domaines côté eau potable
- **Note 1.B** — *Enjeux assainissement* : décline le @tbl-domaines côté collecte et épuration
- **Note 1.C** — *Enjeux irrigation* : décline le @tbl-domaines côté agriculture

**Niveau 2 — Applications**

- **Note 2.A1** — *Dimensionnement AEP* : réseau en charge, point de fonctionnement pompe/réseau
- **Note 2.A2** — *Coups de bélier* : transitoire en charge, méthode des caractéristiques — le cas où l'incompressibilité tombe
- **Note 2.B1/2.B2/2.B3** — *Surface libre pluviale* : Saint-Venant appliqué, onde cinématique/diffusive, surcharges et engorgements (fente de Preissmann)
- **Note 2.C1/2.C2/2.C3** — *Irrigation* : canaux gravitaires, irrigation sous pression, transitoires
- **Note 2.D** — *Pompes et turbines* : machines hydrauliques comme conditions aux limites actives du réseau

**Niveau 3 — Transversales**

- **Note 3.1** — *Calage et validation* : méthodologie complète du NSE au bilan de masse — prolonge directement la section « calage »
- **Note 3.2** — *Quand le 1D ne suffit plus* : CFD, modélisation 2D/3D des ouvrages et plaines inondables
- **Note 3.3** — *Qualité de l'eau et thermique* : transport d'un scalaire porté par l'hydraulique — le couplage faible et ses limites
- **Note 3.4** — *Transport solide et morphodynamique* : quand le fond rétroagit sur l'écoulement — le couplage fort
- **Note 3.5** — *Méthodes numériques* : schémas, stabilité, DNS/LES/RANS — le détail de la résolution invoqué ici
- **Note 3.6** — *Limites et responsabilité du modélisateur* : documenter les hypothèses, tracer les incertitudes, responsabilité professionnelle

## ⚖️ Licence & Propriété Intellectuelle

Le projet SmartHydro utilise un double système de licence pour protéger ses différents contenus :
* **Code informatique & Scripts :** Distribués sous licence **MIT** (libre d'utilisation, modification et distribution avec citation).
* **Articles & Contenu textuel :** Protégés par la licence **Creative Commons (CC BY-NC-ND 4.0)** (Partage autorisé avec citation, mais utilisation commerciale et modifications interdites).

Veuillez consulter le fichier [LICENSE.md](./LICENSE.md) pour lire l'intégralité des termes juridiques ainsi que la **clause de non-responsabilité (Disclaimer)** relative aux calculs hydrauliques.