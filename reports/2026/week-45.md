# Veille scientifique — Semaine 45 (2026)

Période de détection : **02/11/2026 – 08/11/2026**

**8 publication(s)** retenue(s) par la veille.

> Les scores indiquent la pertinence estimée pour une thèse sur les RoT, TEE RISC-V et canaux auxiliaires, et non la qualité scientifique absolue.

## 1. Flashpoint: Privileged-Software Isolation on RISC-V for Dynamic Root of Trust

**Pertinence indicative :** 95/100
**Conférence / Revue :** ASPLOS '27: 32nd ACM International Conference on Architectural Support for Programming Languages and Operating Systems
**Thèmes :** T01 — Root of Trust & Secure Boot

Flashpoint est une co-conception matérielle-logicielle pour l'isolation des logiciels privilégiés sur RISC-V afin d'établir une racine de confiance dynamique (Dynamic Root of Trust). Elle combine une extension minimale du jeu d'instructions (ISA) et un logiciel de médiation léger pour retirer le micrologiciel de démarrage de la base de confiance (TCB).

[Consulter la publication originale](https://doi.org/10.1145/3845814.3850073)

## 2. Last-Level Cache Side-Channel Attacks Are Feasible in the Modern Public Cloud

**Pertinence indicative :** 90/100
**Conférence / Revue :** ASPLOS '24: 29th ACM International Conference on Architectural Support for Programming Languages and Operating Systems, Volume 2
**Thèmes :** T06 — Microarchitectural Side Channels

Cette publication étudie la faisabilité des attaques par canal auxiliaire sur le cache de dernier niveau (LLC) dans un environnement de cloud public moderne, alors qu'elles étaient auparavant principalement démontrées dans des environnements locaux contrôlés. Les auteurs soulignent les défis du cloud, notamment le bruit généré par les autres locataires et la fenêtre temporelle très limitée dans les charges de travail Function-as-a-Service (FaaS).

[Consulter la publication originale](https://doi.org/10.1145/3620665.3640403)

## 3. DyFORA: Dynamic Firmware Obfuscation and Remote Attestation using Hardware Signatures

**Pertinence indicative :** 90/100
**Conférence / Revue :** GLSVLSI '24: Great Lakes Symposium on VLSI 2024
**Thèmes :** T04 — Runtime Attestation

Ce papier présente le framework DyFORA, conçu pour protéger en temps réel le micrologiciel des appareils embarqués sans stockage de clés. Il s'appuie sur des liaisons uniques entre matériel et micrologiciel et sur une méthode d'attestation dynamique et continue pour vérifier l'intégrité.

[Consulter la publication originale](https://doi.org/10.1145/3649476.3658715)

## 4. SoK: Understanding Design Choices and Pitfalls of Trusted Execution Environments

**Pertinence indicative :** 90/100
**Conférence / Revue :** ASIA CCS '24: 19th ACM Asia Conference on Computer and Communications Security
**Thèmes :** T03 — RISC-V TEE & Enclaves

Cet article (SoK) analyse les choix de conception et les pièges des environnements d'exécution de confiance (TEE) pour le calcul sécurisé distant, en examinant diverses solutions commerciales et académiques (Intel, AMD, ARM, IBM et RISC-V).

[Consulter la publication originale](https://doi.org/10.1145/3634737.3644993)

## 5. CaSA: End-to-End Quantitative Security Analysis of Randomly Mapped Caches

**Pertinence indicative :** 85/100
**Conférence / Revue :** IEEE Design &amp; Test
**Thèmes :** T08 — Cache & Temporal Isolation

Cet article étudie l'efficacité des caches à mappage aléatoire en tant que défense populaire contre les attaques ciblant les caches des processeurs modernes pour voler des informations.

[Consulter la publication originale](https://doi.org/10.1109/mdat.2024.3416250)

## 6. On The Effect of Replacement Policies on The Security of Randomized Cache Architectures

**Pertinence indicative :** 82/100
**Conférence / Revue :** ASIA CCS '24: 19th ACM Asia Conference on Computer and Communications Security
**Thèmes :** T08 — Cache & Temporal Isolation

Cette publication étudie l'impact des politiques de remplacement sur la sécurité des architectures de caches randomisés, une technique efficace pour contrer les attaques par contention comme Prime+Probe. Elle souligne que la plupart des analyses négligent ce choix, se limitant souvent aux politiques aléatoires (random) ou LRU, alors que LRU engendre un coût matériel excessif et que le remplacement aléatoire n'est pas idéal pour les performances et la sécurité.

[Consulter la publication originale](https://doi.org/10.1145/3634737.3637677)

## 7. R5Detect: Detecting Control-Flow Attacks from Standard RISC-V Enclaves

**Pertinence indicative :** 80/100
**Thèmes :** T01 — Root of Trust & Secure Boot

R5Detect est un logiciel de surveillance de la sécurité conçu pour détecter et prévenir les attaques par flux de contrôle sur des architectures RISC-V standard et non modifiées, ciblant les appareils IoT et embarqués à faible consommation. Il combine une pile fantôme (shadow stack) protégée en mémoire et une détection heuristique basée sur des compteurs de performance matérielle (Hardware Performance Counters). L'évaluation montre une protection efficace avec un surcoût de performance inférieur à 5 %.

[Consulter la publication originale](http://arxiv.org/abs/2404.03771)

## 8. Salus: A Practical Trusted Execution Environment for CPU-FPGA Heterogeneous Cloud Platforms

**Pertinence indicative :** 75/100
**Conférence / Revue :** ASPLOS '24: 29th ACM International Conference on Architectural Support for Programming Languages and Operating Systems, Volume 4
**Thèmes :** T04 — Runtime Attestation

Cet article présente Salus, un environnement d'exécution de confiance (TEE) pratique pour les plateformes cloud hétérogènes combinant CPU et FPGA. Il analyse les défis du déploiement des TEE sur des FPGA commerciaux (COTS) et propose une approche innovante utilisant une enclave sur le CPU hôte pour protéger et attester le flux binaire (bitstream) chargé sur le FPGA, en s'appuyant sur des utilitaires existants et une IP FPGA sécurisée.

[Consulter la publication originale](https://doi.org/10.1145/3622781.3674169)
