# Qiaodan Hou · 侯乔聃

**Security Researcher & Engineer**

Email: [jordan_hou718@163.com](mailto:jordan_hou718@163.com)

**Research Interests:** LLM-augmented program analysis; dynamic vulnerability testing; AI-native authorization and business-logic security; multi-agent access control and information-flow isolation.

---

## Education

- **M.Sc., Computer Science — Fudan University** — System and Software Security Laboratory · 2021 – 2025
- **B.Eng., Information Security — Nanjing University of Posts and Telecommunications (NJUPT)** · 2017 – 2021

## Industry Experience

**Tencent** — Security Engineer · 2025 – Present

- **LLM-augmented vulnerability detection** — used LLMs to filter false positives, achieving **96.15%** precision (**+64.39 pp ↑**) on injection-vulnerability detection.
- **LLM-assisted SAST data-flow recovery** — used LLMs to supplement incomplete SAST data flows, increasing vulnerability coverage from 0 to **80%+** on an industrial benchmark built from real-world historical vulnerabilities and identifying **600+** new vulnerabilities.
- **White-box authorization / IDOR detection** — led the design of an LLM-based detection system covering **92%** of high-risk repositories, identifying **1,000+** verified access-control vulnerabilities and mitigating risks of billion-scale data exposure — spanning the full closed loop from vulnerability detection to fix verification.
- **LLM-based incremental scanning agent** — building an agent that analyzes incremental code changes; it is under active iteration, with internal rollout planned for **October 2026**.

## Publications

- **[ACM CCS 2026, accepted]** *Foot in the Door: Uncovering the Multi-Step Authorization Exploitation in Mobile Applications* — Yizhe Shi, Zhemin Yang, **Qiaodan Hou**, Lukai Cui, Cheng Sheng, Xiaohan Zhang, and Min Yang. **Contributions:** proposed the core idea; designed and implemented most of MAXChecker; contributed to evaluation and manuscript preparation. MAXChecker combines static and dynamic analysis to identify multi-step authorization exploitation, uncovering 362 vulnerable apps (13 vendor confirmations, 14 CNVD IDs, and 9 CVE IDs).
- **[Manuscript under review]** *Memoir: Learning, Verifying, and Evolving False-Positive Memories for Static Application Security Testing Tools* — **second author** · industry–academia collaboration. **Contributions:** designed the tool, conducted the experiments, and contributed to the writing. Memoir transforms historical false-positive alerts into reusable, self-evolving semantic memories through LLM-guided construction and retrieval-based verification against taxonomy consistency and security invariants. It achieves an F1 score of 99.43% (98.88% recall; 100% precision) on CWE-Bench-Java and generalizes across SAST tools without retraining in an industrial case study.
- **[ACM TOSEM, accepted]** *VulnBridge: Program Semantics Guided Agents for Vulnerability Discovery* — Xu Han, Guangliang Yang, Yi Wang, Can Li, YangShuo Bai, XinMing Guo, AoHan Mei, Keke Lian, Dong Zhang, **Qiaodan Hou**, and Min Yang. VulnBridge combines LLM probabilistic reasoning with structured static analysis to bridge semantic islands in source code, connecting source–sink pairs that were previously unreachable; evaluation on real-world software uncovered zero-day vulnerabilities leading to new CVE IDs.

## Skills

- **LLM-based software security**: LLM-augmented SAST, agentic vulnerability discovery
- **Program analysis**: static and dynamic analysis, taint analysis, CodeQL, Joern
- **Programming**: Python, Java, Go

## Standardized Tests

- GRE **327** (V 157 / Q 170 / AW 3.5) · September 2023
