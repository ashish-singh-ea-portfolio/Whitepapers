<!--
  Ashish Singh | Enterprise Architecture Portfolio
  Director, Enterprise Architecture & GCC Transformation | Cloud-First Strategy & Innovation
  License: CC BY-NC-ND 4.0
-->

<p align="center">
  <img src="assets/banner.png" alt="Ashish Singh — Enterprise Architecture Portfolio" width="100%">
</p>

<h1 align="center">🏛️ Ashish Singh — Enterprise Architecture Portfolio</h1>

<p align="center">
  <b>Director, Enterprise Architecture & GCC Transformation</b><br>
  <i>Architecting Cloud-First Futures — Driving Transformation from Vision to Execution.</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Read%20Only-lightgrey?style=flat-square">
  <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/">
    <img src="https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-blue?style=flat-square">
  </a>
  <img src="https://img.shields.io/badge/Focus-Enterprise%20Architecture%20%7C%20Cloud%20Strategy-green?style=flat-square">
</p>

---

## 🧭 About This Portfolio

This repository is a **curated showcase of my professional whitepapers, frameworks, and architecture blueprints**, authored during global transformation initiatives.

Each paper captures a practical application of **Enterprise Architecture principles**, aligning TOGAF thinking with **cloud adoption**, **GCC operating models**, and **data-driven transformation**.

> 🧩 **Purpose:** Demonstration and knowledge sharing only.  
> Redistribution or modification without permission is prohibited.

---

Data Mesh & Lakehouse CoE Model**](./Whitepapers/Data-Services-CoE) | 📊 Data Architecture | Federated data ownership and platform governance design for enterprise-wide analytics adoption. |

---

## 🧩 Architecture Snippet Example

```plantuml
@startuml
title Backoffice → GCC Digital Transformation (FinTech)
actor "FinTech Ops Team" as Ops
rectangle "Legacy Backoffice" as Legacy
rectangle "GCC Digital Platform" as GCC
Ops --> Legacy : Manual Ops
Legacy -[#FF8C00]-> GCC : Process Automation
GCC -[#228B22]-> Core : API Integration
@enduml
