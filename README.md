# pial-widgets

Widgets Grist du PIAL 21 N (pages statiques servies par GitHub Pages).

- `demande-absence-aesh.html` : demande d autorisation d absence AESH au format officiel, remplie depuis la ligne selectionnee (colonne `Formulaire_json` de `Depot_absence`), bouton Imprimer / PDF.
- `selecteur.html` : menu deroulant compact qui remplace une liste-tableau ; il pilote les autres widgets de la page (« Selectionner par » ce widget). Colonnes a associer : `Libelle` (obligatoire), `Groupe` et `Detail` (facultatives). Parametres d URL : `titre=`, `tri=0`, `fleches=1`, `compte=0`, `premier=0`.
