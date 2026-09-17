# Qiaodan Hou · 侯乔聃

**Security Researcher & Engineer**

Email: [jordan_hou718@163.com](mailto:jordan_hou718@163.com)

**Research Interests:** LLM-augmented program analysis and dynamic testing for vulnerability discovery, with a focus on authorization security.

---

## Education

- **M.Sc., Computer Science — Fudan University** — System and Software Security Laboratory · 2021 – 2025
- **B.Eng., Information Security — Nanjing University of Posts and Telecommunications (NJUPT)** · 2017 – 2021

## Industry Experience

**Tencent** — Security Engineer · `[时间待补]`

- **LLM-augmented vulnerability detection** — used LLMs to filter false positives, pushing precision to **96.15%** (**+64.39 pp ↑**, vs 33.3% for the strongest SOTA).
- **SAST engine extension** — used LLMs to supplement the broken data flows of SAST engines, raising vulnerability coverage from 0 to **80%+** on an industrial benchmark of real-world vulnerability samples and surfacing **600+** new vulnerabilities.
- **White-box authorization / IDOR detection** — led the design of an LLM-based detection system covering **92%** of risk code repositories, surfacing **6000+** permission-risk findings and preventing billion-scale data leaks — the system spans the full closed loop from vulnerability detection to fix verification.
- **LLM-based incremental scanning agent** — currently building from scratch an LLM-based agent that scans only incremental code changes, now under active iteration, with internal launch and operation planned for **October 2026**.

## Publications

- **[ACM CCS 2026, accepted]** *Foot in the Door: Uncovering the Multi-Step Authorization Exploitation in Mobile Applications* — Yizhe Shi, Zhemin Yang, **Qiaodan Hou**, Lukai Cui, Cheng Sheng, Xiaohan Zhang, and Min Yang. **Contributions:** proposed the core idea; designed and implemented most of MAXChecker; contributed to evaluation and manuscript preparation. MAXChecker combines static and dynamic analysis to identify multi-step authorization exploitation, uncovering 362 vulnerable apps (13 vendor confirmations, 14 CNVD IDs, and 9 CVE IDs).
- **[ACM TOSEM, accepted]** *VulnBridge: Program Semantics Guided Agents for Vulnerability Discovery* — Xu Han, Guangliang Yang, Yi Wang, Can Li, YangShuo Bai, XinMing Guo, AoHan Mei, Keke Lian, Dong Zhang, **Qiaodan Hou**, and Min Yang. Combines LLM probabilistic reasoning with structured static analysis to bridge the semantic islands of source code, connecting more sources and sinks that were previously unreachable — an evaluation on real-world software uncovered zero-day vulnerabilities leading to new CVE IDs.

## Skills

- **LLM for software security**: LLM-augmented SAST, agentic vulnerability discovery
- **Program analysis**: static & dynamic analysis, taint analysis, CodeQL, Joern
- **Programming**: Python, Java, Go

## Standardized Tests

- GRE **327** (AW 3.5)
