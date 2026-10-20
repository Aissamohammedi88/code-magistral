# code-magistral
🧬 Le juge des agents. 10 moteurs d'analyse scientifique, Judge Bayésien anti-faux positifs, et Auto-Fix. 100% local.
 <div align="center">
# 🧬 LE CODE MAGISTRAL

**NEXUS OMEGA FORGE — Le Juge des Agents**

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776ab?style=for-the-badge&logo=python)](https://python.org)
[![License](https://img.shields.io/badge/License-NEXUS--OS%20v1.0-c8a45c?style=for-the-badge)](LICENSE)
[![Signature](https://img.shields.io/badge/Signature-940006d54e0cc4bb-ff2d8f?style=for-the-badge)](.)

*10 moteurs scientifiques · Judge Agent bayésien · Auto-Fix · Workflow GitHub Actions*

<img src="https://raw.githubusercontent.com/Aissamohammedi88/code-magistral/main/screenshots/dashboard.png" width="800" alt="Dashboard">

</div>

---

## 🎯 Pourquoi le Code Magistral ?

Les outils actuels génèrent trop de faux positifs. Ils vous fatiguent avec des alertes inutiles. **Le Code Magistral** a été conçu pour être honnête.

- 🧠 **10 Moteurs indépendants** : Compilateurs, AST, secrets, injections SQL, angles morts (IDOR/SSRF).
- ⚖️ **Judge Agent Bayésien** : Il croise les résultats pour éliminer les faux positifs (ce que SonarQube ne fait pas).
- 🔧 **Auto-Fix** : Il génère le code corrigé (eval → ast.literal_eval, shell=True → False, etc.).
- 📄 **Workflow Generator** : Il te génère le fichier `.yml` GitHub Actions prêt à l'emploi.
- 💻 **100% Local** : Aucune donnée ne quitte ta machine. Pas de cloud. Pas d'API externe.

---

## 🚀 Installation

Aucune dépendance nécessaire. Juste **Python 3.10+**.

```bash
# Clone le dépôt
git clone https://github.com/Aissamohammedi88/code-magistral.git
cd code-magistral

# Lance le moteur
python3 nexus_omega_forge.py
