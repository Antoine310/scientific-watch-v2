# Veille scientifique — Semaine 46 (2026)

Période de détection : **09/11/2026 – 15/11/2026**

**4 publication(s)** retenue(s) par la veille.

> Les scores indiquent la pertinence estimée pour une thèse sur les RoT, TEE RISC-V et canaux auxiliaires, et non la qualité scientifique absolue.

## 1. Reconfiguring System-Level Protection Through Bounded Delegation in RISC-V MCUs

**Pertinence indicative :** 92/100
**Conférence / Revue :** Prépublication (conférence non vérifiée)
**Thèmes :** T03 — RISC-V TEE & Enclaves

Cet article étudie la protection au niveau système dans les microcontrôleurs RISC-V, où les politiques de sécurité doivent évoluer dynamiquement à l'exécution. Les auteurs introduisent la notion d'autorité de configuration bornée et un modèle fondé sur la propriété pour encadrer la délégation et la modification des règles de protection sans impacter le chemin de données des accès. Une implémentation sur SoC CVA6 et FPGA démontre une faible surcharge matérielle sans perte de performance, ainsi qu'une réduction significative de la latence lors des mises à jour OTA.

[Consulter la publication originale](https://arxiv.org/pdf/2611.12622)

## 2. Branch Target Reuse: Practical Spectre-v2 Attacks in JIT Engines via Stale Branch Prediction Entries

**Pertinence indicative :** 90/100
**Conférence / Revue :** CCS '26: ACM SIGSAC Conference on Computer and Communications Security
**Thèmes :** T06 — Microarchitectural Side Channels

Cet article étudie une nouvelle attaque par exécution spéculative nommée BTR (Branch Target Reuse), qui exploite le code auto-modifié (SMC) dans les moteurs JIT. Les auteurs démontrent que si la cohérence architecturale est assurée, les entrées de prédiction de branches indirectes obsolètes persistent souvent dans la microarchitecture, permettant de détourner le flux de contrôle spéculatif vers du code nouvellement généré malgré les protections logicielles.

[Consulter la publication originale](https://doi.org/10.1145/3830454.3846672)

## 3. Toward Secure Live Enclave Introspection

**Pertinence indicative :** 85/100
**Conférence / Revue :** IEEE Transactions on Dependable and Secure Computing
**Thèmes :** T03 — RISC-V TEE & Enclaves

Cet article présente SMILE, une architecture d'introspection d'enclaves en temps réel conçue pour Intel SGX. Elle permet au propriétaire légitime d'une enclave de récupérer des pages de mémoire authentifiées et en direct, même si le système d'exploitation hôte, le noyau ou l'hyperviseur est compromis. L'approche repose sur un protocole d'interrogation confiné, un gestionnaire à hauts privilèges (SMILE-Manager) et une liaison de session cryptographique pour garantir l'intégrité et l'authenticité des données récupérées.

[Consulter la publication originale](https://doi.org/10.1109/tdsc.2026.3720276)

## 4. Robust & Scalable Website Fingerprinting via Minimal DRAM Traffic

**Pertinence indicative :** 75/100
**Conférence / Revue :** Prépublication (conférence non vérifiée)
**Thèmes :** T03 — RISC-V TEE & Enclaves

Cet article présente une attaque par empreinte de site web (website fingerprinting) co-localisée et scalable, baptisée memory-chasing. Elle exploite les interférences du trafic DRAM via des parcours de type pointer-chasing avec un minimum d'interférences. Évaluée sur les 50 meilleurs sites web, l'approche atteint une précision de 96 % sur un système à 24 cœurs et démontre sa robustesse face à divers environnements et contre-mesures.

[Consulter la publication originale](https://arxiv.org/pdf/2611.09422)
