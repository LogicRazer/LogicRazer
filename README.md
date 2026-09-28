<!-- ===================== HEADER ===================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f2a17,50:4b5320,100:8a9a5b&height=220&section=header&text=logicrazer&fontSize=64&fontColor=e6e6d0&fontAlignY=38&desc=Malware%20Analyst%20%7C%20Reverse%20Engineering&descSize=20&descAlignY=60&animation=fadeIn" alt="header"/>
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=8A9A5B&center=true&vCenter=true&width=650&lines=Static+%26+Dynamic+Malware+Analysis;Reverse+Engineering+%7C+Unpacking+%7C+IOC+Extraction;Behavioral+Profiling+%26+Threat+Hunting;Dissecting+malware%2C+one+sample+at+a+time" alt="Typing SVG"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Role-Malware%20Analyst-4B5320?style=for-the-badge&logo=hackthebox&logoColor=E6E6D0" alt="role"/>
  <img src="https://img.shields.io/badge/Focus-Reverse%20Engineering-3B4A2A?style=for-the-badge&logo=gnu&logoColor=E6E6D0" alt="focus"/>
  <img src="https://img.shields.io/badge/Status-Active-8A9A5B?style=for-the-badge&logoColor=1F2A17" alt="status"/>
  <img src="https://img.shields.io/badge/Location-France-556B2F?style=for-the-badge&logo=googlemaps&logoColor=E6E6D0" alt="location"/>
</p>

---

## 🪖 À propos

```text
$ whoami
logicrazer

$ cat profile.txt
> Analyste malware : profiling, analyse statique et dynamique
> Je décortique les échantillons pour comprendre ce qu'ils font,
> comment ils le font, et comment les détecter.
```

Je travaille sur le **profiling de malware** : comprendre le comportement d'un échantillon, identifier sa famille, extraire ses indicateurs de compromission et produire des règles de détection exploitables par les équipes défensives.

---

## 🎯 Domaines d'expertise

<table>
  <tr>
    <td width="50%" valign="top">

### 🔬 Analyse statique
- Triage : hashes, entropie, strings, imports/exports
- Analyse de structure PE / ELF
- Détection de packers & obfuscation
- Désassemblage / décompilation
- Extraction de configuration

    </td>
    <td width="50%" valign="top">

### ⚙️ Analyse dynamique
- Exécution en sandbox isolée
- Analyse comportementale (fichiers, registre, processus)
- Analyse du trafic réseau & C2
- Debugging & unpacking manuel
- Analyse mémoire (dumps, injections)

    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">

### 🧬 Profiling
- Classification par famille
- Mapping **MITRE ATT&CK**
- Persistance, évasion, mouvement latéral
- Corrélation d'échantillons

    </td>
    <td width="50%" valign="top">

### 🛡️ Détection
- Règles **YARA**
- Règles **Sigma**
- Extraction d'**IOC**
- Rapports d'analyse

    </td>
  </tr>
</table>

---

## 🧰 Arsenal

**Reverse engineering & analyse statique**

![Ghidra](https://img.shields.io/badge/Ghidra-4B5320?style=flat-square&logo=ghidra&logoColor=E6E6D0)
![IDA](https://img.shields.io/badge/IDA%20Pro-3B4A2A?style=flat-square&logoColor=E6E6D0)
![x64dbg](https://img.shields.io/badge/x64dbg-556B2F?style=flat-square&logoColor=E6E6D0)
![PE-bear](https://img.shields.io/badge/PE--bear-4B5320?style=flat-square&logoColor=E6E6D0)
![DIE](https://img.shields.io/badge/Detect%20It%20Easy-3B4A2A?style=flat-square&logoColor=E6E6D0)
![CyberChef](https://img.shields.io/badge/CyberChef-556B2F?style=flat-square&logoColor=E6E6D0)

**Analyse dynamique & réseau**

![Wireshark](https://img.shields.io/badge/Wireshark-4B5320?style=flat-square&logo=wireshark&logoColor=E6E6D0)
![Procmon](https://img.shields.io/badge/Procmon-3B4A2A?style=flat-square&logo=windows&logoColor=E6E6D0)
![API Monitor](https://img.shields.io/badge/API%20Monitor-556B2F?style=flat-square&logoColor=E6E6D0)
![FakeNet-NG](https://img.shields.io/badge/FakeNet--NG-4B5320?style=flat-square&logoColor=E6E6D0)
![CAPE](https://img.shields.io/badge/CAPE%20Sandbox-3B4A2A?style=flat-square&logoColor=E6E6D0)
![Volatility](https://img.shields.io/badge/Volatility-556B2F?style=flat-square&logoColor=E6E6D0)

**Environnements & scripting**

![FLARE-VM](https://img.shields.io/badge/FLARE--VM-4B5320?style=flat-square&logo=windows&logoColor=E6E6D0)
![REMnux](https://img.shields.io/badge/REMnux-3B4A2A?style=flat-square&logo=linux&logoColor=E6E6D0)
![VirtualBox](https://img.shields.io/badge/VirtualBox-556B2F?style=flat-square&logo=virtualbox&logoColor=E6E6D0)
![Python](https://img.shields.io/badge/Python-4B5320?style=flat-square&logo=python&logoColor=E6E6D0)
![YARA](https://img.shields.io/badge/YARA-3B4A2A?style=flat-square&logoColor=E6E6D0)
![Git](https://img.shields.io/badge/Git-556B2F?style=flat-square&logo=git&logoColor=E6E6D0)

---

## 🔄 Méthodologie

```mermaid
flowchart LR
    A[📥 Échantillon] --> B[🔎 Triage<br/>hash · strings · entropie]
    B --> C[🔬 Analyse statique<br/>RE · désassemblage]
    C --> D[⚙️ Analyse dynamique<br/>sandbox · debug · réseau]
    D --> E[🧬 Profiling<br/>famille · TTPs · ATT&CK]
    E --> F[🛡️ Détection<br/>IOC · YARA · Sigma]
    F --> G[📄 Rapport]
```

---

## 📊 Stats GitHub

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=logicrazer&show_icons=true&hide_border=true&bg_color=1F2A17&title_color=8A9A5B&icon_color=8A9A5B&text_color=E6E6D0" alt="stats"/>
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=logicrazer&layout=compact&hide_border=true&bg_color=1F2A17&title_color=8A9A5B&text_color=E6E6D0" alt="top langs"/>
</p>

---

## 📡 Contact

<p align="center">
  <a href="mailto:logicrazer@tutamail.com">
    <img src="https://img.shields.io/badge/Email-logicrazer%40tutamail.com-4B5320?style=for-the-badge&logo=tutanota&logoColor=E6E6D0" alt="email"/>
  </a>
  <a href="tel:+33757899112">
    <img src="https://img.shields.io/badge/Tél-%2B33%207%2057%2089%2091%2012-3B4A2A?style=for-the-badge&logo=signal&logoColor=E6E6D0" alt="phone"/>
  </a>
</p>

---

## ⚠️ Avertissement

> Toutes mes analyses sont réalisées dans des **environnements isolés et contrôlés**, à des fins de **recherche, de défense et d'éducation**. Je ne publie aucun code malveillant fonctionnel et ne soutiens aucune utilisation offensive ou illégale.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f2a17,50:4b5320,100:8a9a5b&height=100&section=footer" alt="footer"/>
</p>
