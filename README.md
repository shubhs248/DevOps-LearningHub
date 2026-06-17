# 🧪 DevOps Practice Labs

> A growing collection of **clone-and-go, hands-on practice labs** for the tools DevOps engineers use every day — each one written in plain English, with real exercises, ready-made solutions, and **interview questions**. Pick a lab, clone, and start practising in minutes.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#-contributing)
[![Labs](https://img.shields.io/badge/Labs-10-blue.svg)](#-the-labs)

---

## 🎯 Why these labs exist

Most tutorials are either a tiny cheatsheet or a 600-page book. These sit in between: **small, focused, realistic exercises** you can finish in one sitting and come back to before an interview or a real task. Every lab follows the same recipe:

- **Plain-English explanations** — the *why*, not just the *what*.
- **Hands-on exercises** with realistic data/scenarios.
- **Ready-made solutions** to check yourself against.
- **A cheatsheet** for quick revision.
- **Interview questions** with answers you can say out loud.
- **Diagrams** (light + dark) for the key concepts — in each lab's `docs/` gallery, ready for slides and LinkedIn.

## 🧭 The labs

| # | Lab | What you practise | Interview Q&A |
|---|-----|-------------------|:---:|
| 1 | [🐧 Linux & Shell Scripting](linux-shell-practice-lab/README.md) | commands, conditionals, loops, `grep`/`awk`/`sed` | [✓](linux-shell-practice-lab/INTERVIEW-QUESTIONS.md) |
| 2 | [🐍 Python for DevOps](python-devops-practice-lab/README.md) | parsing logs/CSV/JSON, automation, subprocess | [✓](python-devops-practice-lab/INTERVIEW-QUESTIONS.md) |
| 3 | [🔀 Git Scenarios](git-scenarios-lab/README.md) | merge conflicts, rebase, bisect, reflog recovery | [✓](git-scenarios-lab/INTERVIEW-QUESTIONS.md) |
| 4 | [📄 YAML](yaml-practice-lab/README.md) | syntax, gotchas, fix-the-yaml, real DevOps configs | [✓](yaml-practice-lab/INTERVIEW-QUESTIONS.md) |
| 5 | [⚙️ Groovy & Jenkins](groovy-practice-lab/README.md) | Groovy basics, automation, Jenkins pipelines | [✓](groovy-practice-lab/INTERVIEW-QUESTIONS.md) |
| 6 | [🐳 Docker](docker-practice-lab/README.md) | Dockerfiles, multi-stage, fix-it, Compose | [✓](docker-practice-lab/INTERVIEW-QUESTIONS.md) |
| 7 | [☸️ Kubernetes](kubernetes-practice-lab/README.md) | workloads, services, probes, **debugging broken pods** | [✓](kubernetes-practice-lab/INTERVIEW-QUESTIONS.md) |
| 8 | [🌍 Terraform](terraform-practice-lab/README.md) | HCL, state & drift, modules, fix-it (cost-free) | [✓](terraform-practice-lab/INTERVIEW-QUESTIONS.md) |
| 9 | [☁️ Cloud Fundamentals (AWS·Azure·GCP)](cloud-fundamentals-lab/README.md) | core services, LocalStack hands-on, free-account setup | [AWS](cloud-fundamentals-lab/INTERVIEW-QUESTIONS-AWS.md) · [Azure](cloud-fundamentals-lab/INTERVIEW-QUESTIONS-AZURE.md) · [GCP](cloud-fundamentals-lab/INTERVIEW-QUESTIONS-GCP.md) |
| 10 | [🏗️ System Design (DevOps/SRE)](system-design-practice-lab/README.md) | a framework, building blocks, **worked design scenarios** (CI/CD, observability, HA) | [✓](system-design-practice-lab/INTERVIEW-QUESTIONS.md) |

## 🗺️ Suggested learning order

A sensible path from fundamentals to platform skills:

```
Linux/Shell → Python → Git → YAML → Docker → Kubernetes → Terraform → Cloud → System Design
                                  (Groovy/Jenkins any time you touch CI/CD)
```

1. **Foundations:** Linux/Shell, Python, Git — the everyday muscle memory.
2. **Config & packaging:** YAML, Docker.
3. **Orchestration & infra:** Kubernetes, Terraform.
4. **Cloud:** AWS/Azure/GCP fundamentals (with free, local hands-on).
5. **CI/CD glue:** Groovy & Jenkins whenever you're ready for pipelines.
6. **Tie it together:** System Design — once you know the tools, practise combining them into resilient architectures (a common interview round).

## 🚀 How to use

```bash
# clone the whole collection
git clone https://github.com/shubhs248/devops-practice-labs.git
cd devops-practice-labs

# enter any lab and follow its README
cd kubernetes-practice-lab
cat README.md
```

Each lab is self-contained: open its `README.md`, work through the numbered parts, check the `solutions/`, and revise with its `CHEATSHEET.md`. When you're prepping for interviews, go through each lab's interview-questions file.

## 🎤 Interview prep

Every lab ships with an interview-questions file — plain-English answers you can say out loud, grouped from warm-up to senior level, plus hands-on prompts. They're linked in the table above.

## 🖼️ Diagrams

Every lab includes brand-styled diagrams of its key concepts, in **light and dark**, that adapt to your GitHub theme and double as ready-to-post images for LinkedIn/slides. Each lab's images live in its `docs/` folder (see that lab's `docs/README.md` gallery).

They're generated from plain-text [Mermaid](https://mermaid.js.org/) sources (`<lab>/docs/src/*.mmd`) by a single script, so the look stays consistent everywhere:

```powershell
# from the repo root - renders every lab's diagrams (light + dark, PNG + SVG)
powershell -NoProfile -ExecutionPolicy Bypass -File .\render-diagrams.ps1 -Force
```

No install needed — it uses the free [Kroki](https://kroki.io) rendering service.

## 🤝 Contributing

Contributions of every size are welcome — even fixing a typo. Each lab has its own `CONTRIBUTING.md` with specifics. In general: keep the plain-English style, prefer free/clone-and-go tooling, and make sure exercises actually run.

If these helped you, please **star** ⭐ the repo and **share** 🔗 it on LinkedIn so others can find it too.

## 👋 About the author

Made with care by **Shubham Sharma**.

- GitHub: [github.com/shubhs248](https://github.com/shubhs248)
- LinkedIn: [linkedin.com/in/shubhs248](https://www.linkedin.com/in/shubhs248)

## 📜 License

MIT — free to use, fork, teach with, and share. A star ⭐ or a tag on LinkedIn is always appreciated!
