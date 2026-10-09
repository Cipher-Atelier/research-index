# Foix: baseline and witness comparison, 9 October 2026

This summary reports our checks of published material; it does not claim a new decipherment. It is hosted in the research index; no dedicated Foix repository has been created.

Public baseline: dbourdeau/cyphersolver, commit 1fb3c46fd9637e71ac0952f937f0f5b37d687d22.
An independent local decoder reproduced the frozen Beck literal from its recorded source and key: 41 lines, 1038 units, 25 unresolved units, 1013 assigned units and 54 empty expansions. Mapped coverage is not historical accuracy. The upstream full verifier still failed its README hash; the other 17 baseline files matched the manifest. This defect was preserved rather than repaired or described as a total PASS.

Beck/Feyseel K0 comparison used literally identical textual labels: 25 shared, 17 equal preferred values, 19 compatible with an alternative, 20 after i/j normalization. Differences remained at 2, 3, D, r and z. Label compatibility does not prove identical handwriting. K1 was fitted to the target and is not independent validation.

The updated narrative's 1029/1038 assigned count and 827/1157 linked letters were not reproduced from updated key/source/ledger files. They must remain separate from the frozen baseline with 25 unresolved units.

The Potter comparison supports matching the excerpts to letter no. 65, but the witnesses differ: Potter cites TNA SP70/67 ff82–84; Beck/Bourdeau targets BL Add MS 4136 ff148v–149. Manuscript pixels were unavailable for this comparison. A conflict between the published values 32=de and 32=par, and the different financial readings debourssement/rembourssement, remains a source-checking question. These comparisons do not establish glyph identity, choose a financial interpretation, identify a payer or prove a completed transaction.

Required evidence: lawfully accessible manuscript images with documented glyph alignment; dated BnF witness pairs for proposed key transfers; updated machine-readable key/source/ledger for the current narrative counts. Restricted-source access was not bypassed.

Sources:
https://github.com/dbourdeau/cyphersolver/blob/1fb3c46fd9637e71ac0952f937f0f5b37d687d22/targets/foix1563/beck-preliminary/CURRENT_STATUS.md
https://github.com/dbourdeau/cyphersolver/blob/1fb3c46fd9637e71ac0952f937f0f5b37d687d22/targets/foix1563/NOTES.md
https://github.com/dbourdeau/cyphersolver/blob/1fb3c46fd9637e71ac0952f937f0f5b37d687d22/targets/foix1563/r9241_foix1565key/reading.md
https://cryptiana.web.fc2.com/code/henryiii.htm#Foix0
https://www.academia.edu/143900518/Correspondence_of_Paul_de_Foix_French_Ambassador_at_the_Court_of_Elizabeth_I_1562_1565_

Local report SHA256: f0862cfeb0e2f79c6f92d87e92e7694034202a29796428cb3bde3b9c5efc0347.
Independent replay record SHA256: 6c72ebb732d61cdceb2f536c71b12914d2a9231eaa7ce1a8aba93bb2bfcce2e8.
Key-label comparison SHA256: a93c350a233123e4e4317c07c60fc0fa29ad76b375a67483f2b70ddca84bbe17.

Publication scope: our short findings only. No full Potter, manuscript images, crops, private correspondence, or upstream dossier copies are included. The saved report and numeric output were read during this publication pass; the original experiments were not rerun. Codex assisted the analysis and summary. New experiment scripts and the full report are not included.
