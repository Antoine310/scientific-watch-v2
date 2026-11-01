# Veille scientifique — Semaine 44 (2026)

Période de détection : **26/10/2026 – 01/11/2026**

**7 publication(s)** retenue(s) par la veille.

> Les scores indiquent la pertinence estimée pour une thèse sur les RoT, TEE RISC-V et canaux auxiliaires, et non la qualité scientifique absolue.

## 1. Implicit end-point attestation for trusted channel establishment in the keystone TEE

**Pertinence indicative :** 90/100
**Thèmes :** T03 — RISC-V TEE & Enclaves

Non disponible dans les métadonnées.

[Consulter la publication originale](https://doi.org/10.1016/j.comnet.2026.112603)

## 2. RingTrace: Model-Free Spatio-Temporal Detection and Core Attribution for Cache Side-Channels

**Pertinence indicative :** 85/100
**Thèmes :** T06 — Microarchitectural Side Channels, T08 — Cache & Temporal Isolation

RingTrace est un système de surveillance matériel pour détecter et attribuer les canaux cachés de type cache side-channel (ex. Flush+Reload) sur les processeurs multi-cœurs modernes. Il combine des métriques locales aux cœurs et des données de trafic non-core via une matrice d'activité conjointe spatio-temporelle (JSTA) sans nécessiter d'apprentissage de modèle. L'approche permet d'identifier précisément le cœur malveillant et de limiter les faux positifs sous forte charge mémoire, tout en maintenant un faible surcoût.

[Consulter la publication originale](https://eprint.iacr.org/2026/2587)

## 3. Toward Trustworthy Simulation-Based Security Evaluation: A TPM-PUF Root of Trust for RISC-V in gem5

**Pertinence indicative :** 85/100
**Thèmes :** T01 — Root of Trust & Secure Boot

Ce document aborde l'évaluation de la sécurité par simulation orientée vers la fiabilité, en proposant une racine de confiance combinant TPM et PUF pour l'architecture RISC-V au sein du simulateur gem5.

[Consulter la publication originale](https://doi.org/10.1145/3847160.3848079)

## 4. IPFS-SE: A multi-enclave runtime architecture for block-granular data-in-use protection in IPFS on RISC-V Keystone

**Pertinence indicative :** 85/100
**Thèmes :** T03 — RISC-V TEE & Enclaves

Non disponible dans les métadonnées.

[Consulter la publication originale](https://doi.org/10.1016/j.sysarc.2026.104062)

## 5. Unfenced: Atomic Guards Against Spectre: ISA-Level Lock-Free Mitigation for Multi-Core RISC-V Processors

**Pertinence indicative :** 80/100
**Thèmes :** T06 — Microarchitectural Side Channels

Cet article présente "Unfenced", une solution logicielle au niveau de l'ISA utilisant des barrières atomiques groupées (via les paires acquire/release lr.w.aq/sc.w.rl) pour atténuer les attaques Spectre Variant 1 sur les processeurs RISC-V multicœurs, en remplaçant les barrières de type fence.

[Consulter la publication originale](https://doi.org/10.1145/3857307.3857311)

## 6. Lightweight Two-Stage Secure Boot with Automatic Rollback for STM32 IoT Devices

**Pertinence indicative :** 75/100
**Thèmes :** T01 — Root of Trust & Secure Boot

Cette étude présente une architecture de démarrage sécurisé légère en deux étapes avec retour en arrière automatique pour les microcontrôleurs STM32 IoT. Elle élimine le besoin de modules matériels dédiés en répartissant les fonctions de sécurité entre deux chargeurs de démarrage (BL1 et BL2) via une machine à états et une mémoire flash à double banque, tout en intégrant des protocoles cryptographiques (AES, SHA-256, RSA-2048) et une authentification multifacteur par TOTP.

[Consulter la publication originale](https://doi.org/10.21553/rev-jec.455)

## 7. Enabling Extended SGX Enclaves inside Confidential Virtual Machines

**Pertinence indicative :** 75/100
**Thèmes :** T03 — RISC-V TEE & Enclaves

Ce papier présente TEEVisor, une architecture résidant dans une machine virtuelle confidentielle (CVM) et exploitant les niveaux de privilège de machine virtuelle (VMPL) d'AMD SEV-SNP pour imbriquer des enclaves de processus (type Intel SGX) à l'intérieur d'une CVM. L'approche propose un mode de compatibilité binaire SGX pour exécuter des applications non modifiées et un mode étendu (eSGX) optimisant les chemins d'exécution et enrichissant le modèle de programmation.

[Consulter la publication originale](https://arxiv.org/abs/2610.12695)
