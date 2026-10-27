## Hi there 👋
I'm **1sh1ro**.

🎓 **Tianjin University**
- **M.S. in Electronic Information** (Current)
- **B.E. in Cyberspace Security**

My primary interests are **operating systems, file systems, kernel security, and fuzzing**. I also build tools involving AI, blockchain security, and software engineering.

## 🔧 Upstream Kernel Contributions

I contribute patches and bug reports to [Asterinas](https://github.com/asterinas/asterinas), a Rust-based OS kernel, and report vulnerabilities and correctness bugs to the [Linux kernel](https://github.com/torvalds/linux). My work focuses on filesystem semantics, permission enforcement, Linux compatibility, and kernel fault analysis.

### Asterinas · Merged Patches

| Upstream PR | Contribution |
| --- | --- |
| [#4003](https://github.com/asterinas/asterinas/pull/4003) | Enforce `chown(2)` permissions and clear set-ID bits on ownership changes |
| [#4031](https://github.com/asterinas/asterinas/pull/4031) | Enforce sticky-bit protections for `unlink` and `rmdir` |
| [#4057](https://github.com/asterinas/asterinas/pull/4057) | Respect supplementary groups in discretionary access control (DAC) checks |

**Additional PRs in review (as of 2026-10-27):**
[#4028 · System V IPC permissions](https://github.com/asterinas/asterinas/pull/4028) ·
[#4063 · `noexec`/`nodev`/`nosymfollow` enforcement](https://github.com/asterinas/asterinas/pull/4063) ·
[#4083 · ramfs hole punching](https://github.com/asterinas/asterinas/pull/4083)

**Selected bug reports and research:**
[#4021 · malformed GPT kernel panics](https://github.com/asterinas/asterinas/issues/4021) ·
[#3866 · ext2 mount panic](https://github.com/asterinas/asterinas/issues/3866) ·
[#4065 · directory offset/cookie semantics](https://github.com/asterinas/asterinas/issues/4065) ·
[#4033 · Asterfuzz file-system fuzzing proposal](https://github.com/asterinas/asterinas/issues/4033)

### Linux Kernel · Bug Reports

- **Merged into mainline — NTFS:** [`ntfs: fix NULL dereference on index allocation open failure`](https://github.com/torvalds/linux/commit/9365c4a1357e2a5d7f1aff140429028ad292161f). Credited as **`Reported-by: 1sh1ro <yangguikun19@qq.com>`** in the upstream commit.
- **Reported; fix submitted — devlink:** [snapshot ID reference-count leak](https://lore.kernel.org/netdev/tencent_BE912BA710539F285F9FCF28E854ABEFCD07@qq.com/), leaving auto-allocated snapshot IDs permanently reserved after deletion. An upstream patch credits **`Reported-by: Guikun Yang`**; mainline merge has not yet been verified (as of 2026-10-27).

> **Contribution types:** Asterinas entries under *Merged Patches* are authored code contributions; Linux `Reported-by` entries credit bug discovery and reporting, not patch authorship.

---

# My Technical Highlights

## 🚀 Most Proficient Languages
- **Python** - Primary language for AI/ML, web development, and research projects
- **Solidity** - Smart contract development and blockchain applications  
- **JavaScript** - Browser extensions and frontend development
- **Go** - System programming and security tools

## 🛠️ Frequently Used Technologies

### AI & Machine Learning
- **OpenAI API Integration** - LLM-powered applications and analysis tools
- **Computer Vision** - Medical image processing and detection systems
- **Research Tools** - Fault localization and automated debugging systems

### Blockchain & Web3
- **Smart Contracts** - Multi-layered contract architectures
- **Security Analysis** - Vulnerability scanning and penetration testing
- **Web3 Integration** - Blockchain interaction and DApp development

### Web Development
- **Backend**: Flask, Python web frameworks
- **Frontend**: Vue.js, Element UI, HTML/CSS
- **Full-Stack**: Complete web application development

### Security & Research
- **Vulnerability Assessment** - Smart contract and web3 security
- **Kernel Fuzzing** - System-level security research with syzkaller
- **Browser Security** - Extension development and automation

## 📂 Project Categories

### 🤖 AI/Machine Learning Projects
- **Medical AI Systems** - Intelligent urine indicator detection with full-stack implementation
- **LLM Integration Tools** - AI-powered code analysis and research automation
- **Computer Vision** - Image processing and medical diagnostics

### 🔐 Security & Research
- **Web3 Vulnerability Scanner** - AI-assisted smart contract security analysis
- **Kernel Fuzzing** - System security research and bug discovery
- **Automated Fault Localization** - Research in software debugging

### 🌐 Blockchain Development
- **Smart Contract Architecture** - Complex multi-layer contract systems
- **DeFi Applications** - Decentralized finance project development
- **Security Auditing** - Blockchain vulnerability assessment tools

### 💻 Web & Extension Development  
- **Full-Stack Applications** - Complete web solutions with modern frameworks
- **Browser Extensions** - Productivity tools and automation
- **Desktop Applications** - GUI-based utility software

### 📚 Research & Algorithm Practice
- **Academic Research** - Published work in software fault localization
- **Algorithm Implementation** - LeetCode problem solving and optimization
- **Open Source Contributions** - Active in security and development communities

## 🎯 Notable Achievements
- Developed provincial-level innovation project (medical AI detection system)
- Created AI-powered Web3 security scanning platform
- Contributed to kernel security research with enhanced fuzzing tools
- Built production-ready full-stack applications
- Published research in automated software debugging

---

## 🆕 Recent Projects

| Project | Description | Tech |
|---------|-------------|------|
| [attentionfi](https://github.com/1sh1ro/attentionfi) | Attention-based DeFi application | TypeScript |
| [yearlymbti](https://github.com/1sh1ro/yearlymbti) | Summarize your yearly report to MBTI ⭐1 | TypeScript |
| [cve_crawler](https://github.com/1sh1ro/cve_crawler) | CVE vulnerability crawler tool | Python |
| [vitacheck](https://github.com/1sh1ro/vitacheck) | Health monitoring tool | Python |
| [Thyra_docs](https://github.com/1sh1ro/Thyra_docs) | Technical documentation | MDX |
| [apimanager](https://github.com/1sh1ro/apimanager) | API management tool ⭐1 | Python |

---

## 📫 How to reach me
- **Email**: yangxinmeng@tju.edu.cn
<!--
**1sh1ro/1sh1ro** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I'm currently working on ...
- 🌱 I'm currently learning ...
- 👯 I'm looking to collaborate on ...
- 🤔 I'm looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
