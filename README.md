### Hi, I'm Ali

Cybersecurity student at FAST-NUCES Islamabad. I mostly work on the defensive side: securing AWS setups, building CI/CD pipelines that won't ship a leaked secret or a vulnerable dependency, and writing detection and forensics tooling.

Most of the projects here started as a uni assignment or something I wanted to understand properly, and then I kept going.

#### Things I've built

**[Vigilance Core](https://github.com/holialli/Vigilance-Core)**: forensics tool for Windows disk images. It carves around sixteen artifact types (event logs, registry hives, prefetch, SRUM, USB history and more), flags anomalies with an Isolation Forest plus some hard rules, and lets you ask questions about the case in plain English. Every answer cites the artifact it came from, and it runs fully offline with Ollama, so evidence never leaves the machine.

**[CloudShield](https://github.com/holialli/cloudshield)**: read-only AWS posture scanner. IAM, S3 and EC2 checks mapped to CIS, can sweep every enabled region in one run, outputs PDF and JSON, and only touches your account if you explicitly pass `--remediate --allow`.

**[GameVerse](https://github.com/holialli/GameVerse)**: a MERN gaming platform I use as my DevSecOps testbed. Nothing deploys until secret scanning, dependency and container scans pass, and then OWASP ZAP runs against the live build. It ran on EC2 behind Cloudflare for six months and is now on Render + Vercel. Live at [game-verse.tech](https://game-verse.tech).

**[SOC Lab](https://github.com/holialli/soc-lab-suricata-elk)**: Suricata + ELK lab with 30 rules I wrote covering everything from recon to lateral movement, tested by attacking it from Kali.

#### Tools I reach for

Python, JavaScript/Node, React · AWS, Terraform, Docker, GitHub Actions, Jenkins · Suricata, ELK, The Sleuth Kit

#### Right now

Spending most of my time on cloud security automation and starting to contribute to open source security tools. If you're working on something in that space, I'd like to hear about it.
