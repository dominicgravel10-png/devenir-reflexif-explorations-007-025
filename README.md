# Découvrir son propre devenir — Explorations 007–025

**Auteur :** Dominic Gravel, avec assistance computationnelle de Claude (Anthropic).  
**État des travaux :** synthèse exploratoire, référence historique gelée le 16 novembre 2026.

## Objet

Ce programme étudie comment des agents computationnels peuvent inférer leurs propres caractéristiques, réviser leurs croyances et reconnaître leurs transformations au fil du temps. Il distingue trois difficultés : (1) l'absence d'observations pertinentes, (2) l'interprétation des données par un modèle inadapté et (3) l'insuffisance des hypothèses disponibles.

## Résultats sélectionnés

- **Exploration 020 :** dans un modèle stable simplifié résolu par programmation dynamique, la recherche d'information n'est avantageuse que si son bénéfice attendu justifie son coût. Les gains optimaux sur l'abstention rapportés sont 0,0000 à enjeu 0,5 ; +0,0005 à enjeu 1 ; +0,0107 à enjeu 2 ; +0,0240 à enjeu 3.
- **Exploration 021 :** la modélisation d'un facteur persistant associé à l'agent favorise le transfert entre environnements dans les scénarios testés. Ce résultat ne démontre pas la nécessité d'une représentation intérieure de soi.
- **Exploration 023 :** avec une observation à chaque pas, le modèle FIXE présente un biais moyen d'environ −0,1141 en progrès et +0,1145 en déclin. Un contrôle suivant les trajectoires bornées ramène ces biais à environ −0,0016 et +0,0024, dans le modèle discret testé.
- **Exploration 025 :** un bilan périodique améliore la reconnaissance durable du déclin de 36 % à 58 % dans le scénario simulé. Cette mesure ne doit pas être confondue avec la part de l'avantage captée, qui passe de 12 % à 32 %.

## Limites

Les résultats concernent des simulations simplifiées et ne démontrent ni conscience subjective, ni nécessité universelle d'un modèle de soi, ni généralisation aux humains. Les validations logiques indépendantes sont ciblées. La politique de Thompson de l'exploration 023 n'est pas certifiée optimale. Les prédictions historiques ne disposent pas d'une preuve d'antériorité horodatée externe.

## Intégrité et provenance

L'archive historique complète est conservée séparément. Empreinte SHA-256 de la référence historique :

`1fe96a0f3451ffa92a90ad0655f2599115178f276507d8b782f7594a1e003dba`

Cette publication est une **présentation publique limitée des résultats**, et non une mise en ligne des données et programmes complets.

## Réutilisation

Tous droits réservés en l'absence de licence explicite. Pour une réutilisation, contacter l'auteur via GitHub.
