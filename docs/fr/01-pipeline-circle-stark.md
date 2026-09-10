# 01 — Pipeline Circle STARK

STWO transforme une trace en contraintes AIR, engage les evaluations puis applique un test de faible degre.
Les Circle STARK utilisent un domaine circulaire adapte au champ Mersenne employe par le prouveur.
Chaque etape depend de parametres communs : domaine, hachage, transcript et nombre de requetes.
Une preuve n est interpretable qu avec la configuration exacte qui a produit ses engagements.
La revue doit lier colonnes de trace, donnees publiques et contraintes avant d examiner les optimisations.
Source : [`crates/prover`](https://github.com/starkware-libs/stwo/tree/dev/crates/prover).

[Suite](02-air-et-composition.md)
