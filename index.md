---
layout: default
title: Documentation ASN Queries
---

# Menu de navigation
[Accueil](#accueil) | [Arborescence](#section1) | [Modules](#section2) | [Exécution](#section3)

---

<details id="accueil">
  <summary><h2>Accueil</h2></summary>
  Bienvenue sur la documentation du projet **ASN Queries**
</details>

---

<details id="section1">
  <summary><h2>Arborescence du projet</h2></summary>

```
asn_queries/
├── scripts/
│   ├── __init__.py
│   ├── io.py
│   ├── asn.py
│   ├── paths.py
│   └── main.py
└── queries/
    ├── asn_present.txt
    ├── asn_core.txt
    ├── asn_branch.txt
    └── asn_longest_path.txt
```
</details>

<details id="section2">
  <summary><h2>Détails des modules</h2></summary>
  
### io.py

Gestion des entrées/sorties.
Création du dossier queries/.
***
### asn.py

Analyse des ASN (Core/Branch).
</details>

<details id="section3">
  <summary><h2>Exécution du script</h2></summary>
`python3 asn_queries/scripts/main.py`
</details>

