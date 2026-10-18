# Sources candidates — phase 1 (veille)

Statut : **Vérifié** = page d'origine lue le 18 octobre 2026 (titre, auteurs, date, identifiant contrôlés). **À confirmer** = un élément reste à contrôler dans le document lui-même.
Les chiffres cités sont ceux lus sur la page d'origine. Chaque chiffre devra être recontrôlé dans le rapport complet (avec le numéro de page) avant d'entrer dans `data/sources.csv`.

## Rapports institutionnels (6)

| N° | Référence | Statut | Questions | Biais à nommer |
| --- | --- | --- | --- | --- |
| I1 | IEA (2025). *Energy and AI*. International Energy Agency. https://www.iea.org/reports/energy-and-ai | Vérifié (date exacte non indiquée sur la page, citation 2025) | Q1, Q3, Q4, Q5 | Agence liée aux pays membres de l'OCDE, scénarios de politique énergétique, périmètre « centres de données » sans cryptomonnaies |
| I2 | The Shift Project (octobre 2025). *IA, données, calcul : quelles infrastructures dans un monde décarboné ?* https://theshiftproject.org/app/uploads/2025/09/Rapport-final-IA-OK.pdf | Vérifié | Q1, Q3, Q4 | Groupe de réflexion qui plaide pour la sobriété et la décarbonation ; périmètre incluant les cryptomonnaies |
| I3 | Shehabi, A. et al. (décembre 2024). *2024 United States Data Center Energy Usage Report*. Lawrence Berkeley National Laboratory. DOI 10.71468/P1WC7Q | Vérifié | Q1, Q2 | Laboratoire du département américain de l'énergie, périmètre États-Unis uniquement |
| I4 | Arcep (17 avril 2025). *Enquête annuelle « Pour un numérique soutenable », édition 2025 (données 2023)*. https://www.arcep.fr/cartes-et-donnees/nos-publications-chiffrees/impact-environnemental/enquete-annuelle-pour-un-numerique-soutenable-edition-2025.html | Vérifié | Q1, Q4 (France) | Régulateur français, données déclarées par les opérateurs |
| I5 | GHG Protocol / WRI / WBCSD (2015). *Scope 2 Guidance*. https://ghgprotocol.org/scope-2-guidance | Vérifié pour le titre et l'année ; la définition des méthodes « location-based » et « market-based » reste à lire dans le document | Q4 (méthode) | Référence méthodologique du secteur privé, non indépendante de l'industrie |
| I6 | Commission européenne (14 mars 2024). *Règlement délégué (UE) 2024/1364 sur la première phase de la mise en place d'un système commun de notation des centres de données à l'échelle de l'Union*. https://eur-lex.europa.eu/eli/reg_del/2024/1364/oj | À confirmer : titre et dates vérifiés (adopté le 14 mars 2024, en vigueur le 6 juin 2024), contenu non lu | Q3, Q4 (volet réglementaire) | Texte juridique : décrit une obligation, pas une mesure |

## Articles scientifiques (peer-reviewed)

| N° | Référence | Statut | Questions | Biais ou limite |
| --- | --- | --- | --- | --- |
| P1 | Masanet, E. R., Shehabi, A., Lei, N., Smith, S. J., Koomey, J. G. (2020). Recalibrating global data center energy-use estimates. *Science*, 367(6481), 984-986. DOI 10.1126/science.aba3758 | Vérifié | Q1 | Antérieur à l'essor de l'IA générative ; sert surtout de contrepoint aux projections de doublement |
| P2 | Hoffmann, J. et al. (2022). An Empirical Analysis of Compute-Optimal Large Language Model Training. *NeurIPS 2022*. https://proceedings.neurips.cc/paper_files/paper/2022/hash/c1e2faff6f588870935f114ebe04a3e5-Abstract.html | Vérifié. Attention : la version arXiv a un autre titre (*Training Compute-Optimal Large Language Models*, arXiv:2203.15556). Citer la version NeurIPS. | Q2 | Travail d'un laboratoire industriel (DeepMind) |
| P3 | Strubell, E., Ganesh, A., McCallum, A. (2020). Energy and Policy Considerations for Modern Deep Learning Research. *AAAI 2020*, 34(9), 13693-13696. DOI 10.1609/aaai.v34i09.7123 | Vérifié (version courte de l'article ACL 2019 du même titre) | Q2, Q4 | Les chiffres détaillés sont dans l'article ACL 2019, à lire pour les valeurs ; ancien, mais classique |
| P4 | Luccioni, A. S., Jernite, Y., Strubell, E. (2024). Power Hungry Processing: Watts Driving the Cost of AI Deployment? DOI 10.1145/3630106.3658542 | À confirmer : auteurs, titre et DOI vérifiés sur arXiv (2311.16863), la page ACM n'a pas pu être lue ; la conférence (FAccT 2024) est à contrôler | Q2 (inférence) | Mesures sur un jeu de modèles précis, à ne pas généraliser |

## Prépublications arXiv (à utiliser avec prudence)

| N° | Référence | Statut | Questions | Limite |
| --- | --- | --- | --- | --- |
| A1 | Kaplan, J. et al. (2020). Scaling Laws for Neural Language Models. arXiv:2001.08361 | Vérifié : aucune version de revue ou de conférence indiquée | Q2 | Prépublication ; les lois ont été révisées par Hoffmann et al. (2022) |
| A2 | Patterson, D. et al. (2021). Carbon Emissions and Large Neural Network Training. arXiv:2104.10350 | Vérifié : aucune version de revue indiquée sur la page | Q2, Q4 | Auteurs de Google, qui évalue ses propres systèmes |
| A3 | Li, P., Yang, J., Islam, M. A., Ren, S. (2023, version 4 de janvier 2025). Making AI Less « Thirsty »: Uncovering and Addressing the Secret Water Footprint of AI Models. arXiv:2304.03271 | Vérifié pour arXiv ; une version dans *Communications of the ACM* (2025) est à confirmer | Q4 (eau) | Estimations basées sur des hypothèses (par exemple 700 000 litres évaporés pour l'entraînement de GPT-3, d'après les auteurs) |

## Candidat non vérifié

- de Vries, A. (2023). The growing energy footprint of artificial intelligence. *Joule*. DOI 10.1016/j.joule.2023.09.004. La page de l'éditeur n'a pas pu être lue : à vérifier avant tout usage.

## Bilan par rapport à la checklist du cours

- 13 références vérifiées ou presque (objectif : 15 au minimum) : il en manque au moins 2.
- Rapports institutionnels : 6 sur 3 demandés.
- Peer-reviewed : 3 certains (P1, P2, P3) + 1 à confirmer (P4), pour 5 demandés : il en manque 1 ou 2 (de Vries, Li dans CACM, ou un autre).
- Dates récentes (moins de 3 ans) : seules I1 à I4, I6, P4 et A3 (version de janvier 2025) le sont ; les autres sont des classiques.
- Sources industrielles : aucune pour l'instant. À ajouter, par exemple des rapports de développement durable de grandes entreprises du numérique, à traiter comme biaisés.

## Contradictions à analyser (niveau 3 du cours)

1. **Consommation mondiale des centres de données.** L'IEA donne 415 TWh en 2024 (1,5 % de l'électricité mondiale, sans cryptomonnaies). The Shift Project donne 530 TWh en 2023 avec les cryptomonnaies, et 380 TWh sans. Les années et les périmètres diffèrent : il faut les harmoniser avant de comparer.
2. **Projection 2030.** L'IEA annonce environ 945 TWh. The Shift Project annonce 1 250 à 1 500 TWh dans un scénario sans changement majeur. À expliquer par les méthodes, les périmètres et le positionnement de chaque organisation.
3. **« Le doublement de la consommation ».** Masanet et al. (2020) estiment une croissance plus modérée que les analyses qui annonçaient un doublement, en tenant compte des gains d'efficacité. À confronter aux projections actuelles liées à l'IA générative.
