**Languages:** [English](#english) | [Français](#francais)

<a id="english"></a>
# 🧮 OpenG7 – Customs Valuation Lab

---

## 🇬🇧 English

![OpenG7 – Customs Valuation Lab](assets/customs-valuation-lab-banner-en.png)

**Open-source modelling lab to bring customs valuation rules closer to real supply chains**

🔎 **What it is**  
OpenG7 – Customs Valuation Lab is a product-ready, open-source toolkit that helps you **model**, **visualize** and **explain** how customs valuation rules apply to **real-world import flows**, across sectors and regions.

🧪 **Status:** Pending

> ℹ️ This project is **independent** from any government or customs authority.  
> It is a **neutral, open-source solution** built by and for practitioners, advisors, and analysts.

---

### 🧩 The problem

Customs valuation rules (e.g. “transaction value”, “sale for export”, exclusions, consignments) are:

- complex to interpret in **multi-step supply chains**  
- hard to explain to non-specialists  
- spread across legal texts, policies, and internal business practices.

Result:  
- inconsistent application,  
- avoidable disputes,  
- time lost in emails, spreadsheets, and one-off diagrams.

---

### ✅ The solution

**OpenG7 – Customs Valuation Lab** gives you:

- A **common language** to describe chains of sales, contracts, and roles  
- **Machine-readable schemas** for transactions and valuation rules  
- A library of **ready-to-use scenarios** (anonymised) you can adapt  
- Visual templates to **show** how a given rule affects the customs value  
- A fully open-source base that can be:
  - audited  
  - forked  
  - integrated into your own tools or internal workflows.

It is designed to be **jurisdiction-agnostic**, with a default profile tuned for **Canada’s customs valuation framework** and extensible to other countries.

---

### 🔑 Key features

- **Scenario engine**  
  Describe supply chains as YAML files: suppliers, intermediaries, contracts, incoterms, transfers of title, etc.

- **Valuation rule schemas**  
  Represent valuation methods, exclusions, and decision paths as JSON schemas or rule graphs.

- **Impact views**  
  Quickly see:
  - which transaction becomes the “valuation pivot”  
  - which sales are excluded and why  
  - how this affects different actors in the chain.

- **Business-friendly visuals**  
  Use the included diagram templates (Mermaid, graph configs) to generate clear flows for:
  - internal training  
  - management presentations  
  - client explanations.

- **Open-source foundation**  
  MIT/Apache-style licensing (see `LICENSE`) so you can:
  - embed the logic  
  - extend the schemas  
  - integrate with ERPs, BI tools, or your own compliance platforms.

---

### 👥 Who is it for?

- **Importing businesses** (any size)  
  who want to *understand and standardize* how they determine customs value.

- **Customs brokers & trade advisors**  
  who need reusable, transparent models for explaining scenarios to clients.

- **In-house legal & tax teams**  
  who want structured, documented reasoning they can review and archive.

- **Policy, research & think tanks**  
  who analyse how valuation rules impact sectors, regions, or supply-chain resilience.

- **Developers / data teams**  
  who build internal tools for trade compliance, logistics, or scenario analysis.

---

### 💡 Example use cases

- Document how your company currently values imports **across several business lines**.  
- Test what happens if:
  - a consignment agreement is replaced by a direct sale, or  
  - an intermediary changes role (agent vs principal).  
- Build internal training material where each module is backed by a **real scenario file**.  
- Compare the treatment of similar chains under **different valuation policies** or countries.

---

### 🧱 Repository structure (high level)

Planned structure (may evolve):

- `docs/`  
  - Product overview & concepts  
  - How to model a scenario  
  - Glossary (transactions, roles, valuation concepts)

- `profiles/`  
  - Jurisdiction profiles (e.g. `canada/`, `eu/`, `generic/`)  
  - Each profile contains its specific rule sets and examples.

- `scenarios/`  
  - Realistic but anonymised supply-chain stories, grouped by:
    - sector (manufacturing, retail, energy, agro, etc.)  
    - region or corridor (ports, inland hubs, cross-border routes)

- `data/`  
  - JSON schemas for transactions, rules, and decision trees  
  - Sample datasets for testing.

- `tools/`  
  - Notebooks, CLI samples, and visualization templates.

---

### 🚀 Getting started

1. **Clone the repo**

   ```bash
   git clone git@github.com:OpenG7/openg7-customs-valuation-lab.git
   cd openg7-customs-valuation-lab
   ```

2. **Explore the docs**

   - Start with `docs/overview.md` and `docs/how-to-model-a-scenario.md` (once available).  

3. **Run a sample scenario**

   - Pick a scenario under `scenarios/`  
   - Load it in your favourite environment (Python, Node, etc.) using the JSON schemas in `data/`.

4. **Create your own**

   - Copy an existing scenario  
   - Replace actors, contracts, and flows with a case close to your business  
   - Run it through the same rule profile to see how customs value is determined.

---

### 🤝 Contributing

We welcome contributions from:

- practitioners, brokers, and importers  
- legal and policy experts  
- developers and data scientists.

You can:

- Propose new scenarios  
- Improve or add jurisdiction profiles  
- Refine schemas and documentation  
- Build integrations (e.g. examples with popular ERPs or BI tools).

Please open an issue first if you plan a significant change, so we can coordinate.

---

### 📜 License & disclaimer

- License: see `LICENSE` file (open-source, business-friendly).  
- This project is for **educational and modelling purposes**.  
- It does **not** replace professional legal or customs advice.

---

<a id="francais"></a>
## 🇫🇷 Français

![OpenG7 – Customs Valuation Lab](assets/customs-valuation-lab-banner-fr.png)

**Laboratoire open source pour rapprocher les règles de valeur en douane des chaînes d’approvisionnement réelles**

🔎 **Ce que c’est**  
OpenG7 – Customs Valuation Lab est une boîte à outils open source, prête à l’usage, qui permet de **modéliser**, **visualiser** et **expliquer** comment les règles de valeur en douane s’appliquent à des **flux d’importation réels**, tous secteurs et régions confondus.

🧪 **Statut :** En attente

> ℹ️ Ce projet est **indépendant** de tout gouvernement ou autorité douanière.  
> C’est une solution **neutre, open source**, pensée par et pour les praticiens, conseillers et analystes.

---

### 🧩 Le problème

Les règles de valeur en douane (ex. “valeur transactionnelle”, “vendu pour exportation”, exclusions, consignation) sont :

- complexes à interpréter dans des **chaînes multi-étapes**  
- difficiles à expliquer à des non-spécialistes  
- éparpillées entre textes juridiques, politiques internes et pratiques métier.

Résultat :  
- application inégale,  
- litiges évitables,  
- temps perdu en courriels, tableurs et schémas ad hoc.

---

### ✅ La solution

**OpenG7 – Customs Valuation Lab** vous apporte :

- Un **langage commun** pour décrire ventes, contrats et rôles dans la chaîne  
- Des **schémas lisibles par machine** pour les transactions et les règles  
- Une bibliothèque de **scénarios prêts à l’emploi** (anonymisés) que vous pouvez adapter  
- Des gabarits visuels pour **montrer** comment une règle donnée fixe la valeur en douane  
- Une base totalement open source, que vous pouvez :
  - auditer  
  - forker  
  - intégrer à vos outils ou workflows internes.

Le tout est conçu pour être **neutre juridictionnellement**, avec un profil par défaut orienté vers le cadre canadien, mais extensible à d’autres pays.

---

### 🔑 Fonctionnalités clés

- **Moteur de scénarios**  
  Décrivez vos chaînes d’approvisionnement en YAML : fournisseurs, intermédiaires, contrats, incoterms, transferts de propriété, etc.

- **Schémas de règles de valeur en douane**  
  Représentez méthodes de valorisation, exclusions et arbres de décision via des schémas JSON ou graphes de règles.

- **Vues d’impact**  
  Visualisez rapidement :
  - quelle transaction devient le “pivot de valorisation”  
  - quelles ventes sont exclues et pourquoi  
  - comment cela affecte les différents acteurs de la chaîne.

- **Visuels adaptés au métier**  
  Utilisez les gabarits de diagrammes fournis (Mermaid, graphes) pour produire des flux clairs pour :
  - la formation interne  
  - des présentations à la direction  
  - des explications clients.

- **Base open source**  
  Licence de type MIT/Apache (voir `LICENSE`), pour :
  - intégrer la logique  
  - étendre les schémas  
  - connecter l’outil à vos ERP, outils BI ou plateformes de conformité.

---

### 👥 À qui ça s’adresse ?

- **Entreprises importatrices**  
  qui veulent *comprendre et standardiser* la détermination de leur valeur en douane.

- **Courtiers et conseillers en commerce international**  
  qui ont besoin de modèles réutilisables et transparents pour illustrer les cas clients.

- **Équipes juridiques / fiscales internes**  
  qui souhaitent disposer d’un raisonnement structuré et documenté, révisable dans le temps.

- **Organismes de recherche, think tanks, observatoires**  
  qui analysent l’impact des règles de valorisation sur les secteurs, régions ou chaînes d’approvisionnement.

- **Équipes de développement & data**  
  qui construisent des outils internes pour la conformité, la logistique ou la simulation de scénarios.

---

### 💡 Exemples d’usage

- Documenter la façon dont votre groupe valorise ses importations à travers **plusieurs divisions**.  
- Tester ce qui se passe si :
  - un contrat de consignation est remplacé par une vente directe ;  
  - un intermédiaire change de rôle (mandataire vs principal).  
- Construire des modules de formation interne où chaque cas est relié à un **fichier de scénario**.  
- Comparer le traitement de chaînes similaires sous **différentes politiques de valorisation** ou différents pays.

---

### 🧱 Structure du dépôt (vue d’ensemble)

Structure prévue (évolutive) :

- `docs/`  
  - Vue d’ensemble du produit et concepts  
  - Guide “Comment modéliser un scénario”  
  - Glossaire (transactions, rôles, concepts de valeur en douane)

- `profiles/`  
  - Profils par juridiction (`canada/`, `eu/`, `generic/`, etc.)  
  - Chaque profil contient ses règles et exemples spécifiques.

- `scenarios/`  
  - Histoires de chaînes d’approvisionnement anonymisées, classées par :
    - secteur (fabrication, détail, énergie, agro, etc.)  
    - région ou corridor (ports, hubs intérieurs, routes transfrontalières)

- `data/`  
  - Schémas JSON pour transactions, règles et arbres de décision  
  - Jeux de données d’exemple.

- `tools/`  
  - Notebooks, exemples de CLI, gabarits de visualisation.

---

### 🚀 Démarrage rapide

1. **Cloner le dépôt**

   ```bash
   git clone git@github.com:OpenG7/openg7-customs-valuation-lab.git
   cd openg7-customs-valuation-lab
   ```

2. **Parcourir la documentation**

   - Commencez par `docs/overview.md` et `docs/how-to-model-a-scenario.md` (une fois disponibles).  

3. **Exécuter un scénario d’exemple**

   - Choisissez un scénario dans `scenarios/`  
   - Chargez-le dans votre environnement (Python, Node, etc.) via les schémas de `data/`.

4. **Créer votre cas concret**

   - Copiez un scénario existant  
   - Adaptez acteurs, contrats et flux à votre réalité d’affaires  
   - Appliquez le même profil de règles pour voir comment se détermine la valeur en douane.

---

### 🤝 Contribution

Les contributions sont bienvenues de la part :

- des praticien·nes, courtiers et importateurs  
- des expert·es juridiques et en politiques publiques  
- des développeur·euses et spécialistes data.

Vous pouvez :

- Proposer de nouveaux scénarios  
- Ajouter ou améliorer des profils de juridiction  
- Affiner les schémas et la documentation  
- Construire des intégrations (ex. exemples avec des ERP ou outils BI).

Merci d’ouvrir un ticket avant les modifications majeures pour coordonner les efforts.

---

### 📜 Licence & avertissement

- Licence : voir le fichier `LICENSE` (open source, favorable aux usages professionnels).  
- Ce projet a vocation **pédagogique et de modélisation**.  
- Il ne remplace pas un avis professionnel en matière douanière ou juridique.

---
