![header](https://capsule-render.vercel.app/api?type=waving&color=0D1B2A&height=150&section=header)

<h1 align="center">Amin Wafi</h1>
<p align="center"><b>AI &amp; Machine Learning Engineer</b></p>

<div align="center">

<a href="https://git.io/typing-svg">

![typing](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=C9A227&center=true&vCenter=true&width=700&lines=YOLOv8+%C2%B7+spaCy+%C2%B7+On-device+LLMs;shell-pilot+%C2%B7+screenshield+%C2%B7+redact;GDPR+%2B+AI%3A+structurally+incompatible;Open+to+AI+and+ML+roles+in+Paris)

</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Amin%20Wafi-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amin-wafi-227a292ab)
[![shell-pilot](https://img.shields.io/badge/AWL--001-shell--pilot-0D1B2A?style=for-the-badge&logo=gnometerminal&logoColor=C9A227)](https://github.com/aminwa/shell-pilot)
[![Email](https://img.shields.io/badge/Email-aminwa%40icloud.com-C9A227?style=for-the-badge&logo=icloud&logoColor=white)](mailto:aminwa@icloud.com)

</div>

---

### What I do

I train and ship AI systems with a focus on how they behave in deployment. The work spans computer vision, on-device LLMs, and developer tools, with one principle running through all of it: the user's data should not leave the user's machine. [AW Labs](https://github.com/aminwa) is where that work ships.

I also write on the boundary between AI systems, security, and privacy law. Recent work covers GDPR compatibility with frontier LLM training, governance after the M&S ransomware incident, and deployment ethics for object detection in security screening. The thread is the same: how these systems hold up under real conditions, not just in notebooks.

---

### AW Labs

<table>
<tr>
<td width="50%">

**[shell-pilot](https://github.com/aminwa/shell-pilot)** `AWL-001`

Agentic AI terminal assistant. Hooks into zsh/bash, blocks dangerous commands before they run, corrects typos locally, explains failures with an LLM, learns from your shell history. All history processing is local.

`Python` `SQLite` `Click` `Rich`

![](https://img.shields.io/badge/tests-58%20passing-brightgreen?style=flat-square)
![](https://img.shields.io/badge/version-1.0.0-C9A227?style=flat-square)
![](https://img.shields.io/badge/license-MIT-blue?style=flat-square)

</td>
<td width="50%">

**[screenshield](https://github.com/aminwa/screenshield)** `AWL-002`

Local screen guardian. Captures frames at 2 FPS, runs OCR, and scans for 12 secret types — AWS keys, GitHub tokens, private keys, credit cards. Escalates to critical when a screen share is active and redacts in real time.

`Python` `Tesseract` `spaCy` `Rich`

[![CI](https://github.com/aminwa/screenshield/actions/workflows/ci.yml/badge.svg?style=flat-square)](https://github.com/aminwa/screenshield/actions/workflows/ci.yml)
![](https://img.shields.io/badge/license-MIT-blue?style=flat-square)

</td>
</tr>
<tr>
<td width="50%">

**[redact](https://github.com/aminwa/redact)** `AWL-003`

PII redaction that shows its work. Runs a spaCy NER model and Claude in parallel, merges their outputs, and lets you compare what each engine caught and why. Pipe-friendly: `cat file.txt | redact`.

`Python` `spaCy` `Claude API` `Typer`

[![CI](https://github.com/aminwa/redact/actions/workflows/ci.yml/badge.svg?style=flat-square)](https://github.com/aminwa/redact/actions/workflows/ci.yml)
![](https://img.shields.io/badge/license-MIT-blue?style=flat-square)

</td>
<td width="50%"></td>
</tr>
</table>

---

### Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-0D1B2A?style=for-the-badge&logo=python&logoColor=C9A227)
![C++](https://img.shields.io/badge/C++-0D1B2A?style=for-the-badge&logo=cplusplus&logoColor=C9A227)
![PyTorch](https://img.shields.io/badge/PyTorch-0D1B2A?style=for-the-badge&logo=pytorch&logoColor=C9A227)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-0D1B2A?style=for-the-badge&logo=huggingface&logoColor=C9A227)
![OpenCV](https://img.shields.io/badge/OpenCV-0D1B2A?style=for-the-badge&logo=opencv&logoColor=C9A227)
![YOLOv8](https://img.shields.io/badge/YOLOv8-0D1B2A?style=for-the-badge&logo=ultralytics&logoColor=C9A227)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0D1B2A?style=for-the-badge&logo=scikitlearn&logoColor=C9A227)
![Docker](https://img.shields.io/badge/Docker-0D1B2A?style=for-the-badge&logo=docker&logoColor=C9A227)

</div>

---

### Research

**LLMs and GDPR: A Structural Incompatibility**

GDPR was designed for bounded, purpose-specific data processing. Frontier-scale LLM training on web-scraped data is unbounded and purpose-flexible. The gap between them is not a compliance problem - it is an architectural one.

My dissertation connects three literatures kept largely apart: empirical work on memorisation in LLMs (Carlini et al.), doctrinal GDPR analysis (Articles 5, 6, 13-22), and normative work on EU Charter fundamental rights (Articles 7-8). The central argument is that the La Quadrature du Net prohibition on indiscriminate processing applies to web-scraped LLM training and cannot be resolved by transparency measures or consent mechanisms alone.

Evaluated against EDPB Opinion 28/2024, CNIL June 2025 guidance, and EU AI Act Article 53. Proposes data trusts as a governance reform.

*University of Derby - 6CM995 - Submitted May 2026*

**Selected Work**

- **YOLOv8 for Prohibited Item Detection in Airport X-ray.** Trained and shipped to ONNX/Docker. mAP50 0.924 across five knife classes on the OPIXray benchmark, with explicit deployment ethics framing.
- **Cyber Security Posture of M&S Following the April 2025 Ransomware Incident.** Critical evaluation of control failures with a costed remediation programme aligned to ISO 27001 and NIST SP 800-61r3.

*Full versions available on request.*

---

<div align="center">

![footer](https://capsule-render.vercel.app/api?type=waving&color=0D1B2A&height=100&section=footer)

</div>
