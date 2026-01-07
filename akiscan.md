 # Akiscan : l'outil d'analyse de site web

<img width="1259" height="582" alt="Capture d&#39;écran 2025-10-02 153350" src="https://github.com/user-attachments/assets/69b65a41-079f-4cc0-b8fe-b9e13d47702c" />
<img width="1195" height="702" alt="Capture d&#39;écran 2025-10-02 153519" src="https://github.com/user-attachments/assets/916c5043-7574-4236-8c3d-82c90d0afa96" />
<img width="1147" height="644" alt="Capture d&#39;écran 2025-10-02 153547" src="https://github.com/user-attachments/assets/ac7b2cc7-5429-4e0b-b19c-69d47a24bc9d" />
<img width="792" height="620" alt="Capture d&#39;écran 2025-10-02 153905" src="https://github.com/user-attachments/assets/9e95bb7d-9df7-4a24-8a08-e710b2ea60b2" />


## Présentation

Akiscan est un outil d'analyse qui permet de mesurer le niveau d'accessibilité d'une page web ainsi que sa performance environnementale.

## Technologies utilisées

AkiScan est un outil d’analyse développé avec le framework Symfony, conçu pour évaluer à la fois l’accessibilité web et la performance environnementale des sites.

La partie accessibilité repose sur axe-core, une librairie JavaScript open source développée par Deque Systems, utilisée comme moteur d’analyse automatisée de la conformité aux WCAG. Axe Core est exécuté sur les pages analysées afin d’identifier les non-conformités (structure sémantique, attributs ARIA, contrastes, navigation, etc.), dont les résultats sont ensuite collectés et structurés.

La partie performance environnementale s’appuie sur Green IT Analysis, un outil d’analyse de l’empreinte environnementale des pages web, permettant d’évaluer des indicateurs tels que la complexité du DOM, le poids des ressources, les requêtes réseau et les bonnes pratiques d’éco-conception.

Les données issues de ces analyses sont centralisées et exploitées afin de fournir un diagnostic technique global, orienté accessibilité, performance et numérique responsable.

