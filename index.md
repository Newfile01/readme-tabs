---
layout: default
title: Documentation ASN Queries
---

# Menu de navigation
[Accueil](#accueil) | [Arborescence](#section1) | [Modules](#section2) | [Exécution](#section3)

---

<details id="accueil">
  <summary>Accueil</summary>
  Bienvenue sur la documentation du projet **ASN Queries** .
</details>

---

<details id="section1">
  <summary>Arborescence du projet</summary>

  ```text
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

</details>

<details id="section2">
  <summary>Détails des modules</summary>
io.py

Gestion des entrées/sorties.
Création du dossier queries/.
asn.py

Analyse des ASN (Core/Branch).
</details>

<details id="section3">
  <summary>Exécution du script</summary>
python3 asn_queries/scripts/main.py
</details>

