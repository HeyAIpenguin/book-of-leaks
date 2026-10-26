# Sources

Every number in the book, and where it comes from.

| Chapter | Facts | Sources |
|---|---|---|
| 1. Toyota (2017–2022) | A subcontractor put part of the T-Connect source code in a public GitHub repo, with a hard-coded access key to the customer-data server. Public from Dec 2017 to Sep 15, 2022. 296,019 email addresses and customer control numbers exposed. Key changed Sep 17, 2022; Toyota could not confirm or rule out access. | Toyota statement (Oct 7, 2022); GitGuardian; Infosecurity Magazine |
| 2. Uber (2016) | Attackers got into a private GitHub repo used by Uber engineers, found AWS credentials and downloaded data of 57M riders and drivers. Uber paid them $100,000 to delete it and stay quiet, and disclosed the breach a year later. | Uber statement (Nov 21, 2017); US Federal Trade Commission |
| 3. SolarWinds (2019) | The update-server password `solarwinds123` sat in a public GitHub repo from 2018 until researcher Vinoth Kumar reported it in Nov 2019. At the Feb 26, 2021 US House hearing, executives blamed an intern. It was never shown to be the SUNBURST entry point. | Vinoth Kumar via Reuters; US House hearing (Feb 26, 2021) |
| 4. OpenCode (Oct 2026) | A breach of a legacy system hit 1.4% of OpenCode Console users, those with linked OpenAI/Anthropic/Google keys. Users reported $1,700+ in charges overnight. | OpenCode notice (Oct 17, 2026); TechCrunch (Oct 19, 2026); BleepingComputer |
| 5. Tailscale (Oct 2026) | Erica Windisch published 11 unpatched Tailscale flaws. The SSH ones need an already-compromised device with SSH rights. My own tailnet: 7 devices, Tailscale SSH off on all of them. | tailworm.com (Oct 25, 2026); my own check |
| 6. My Mac (Oct 2026) | A keyaudit scan: 7,477 files in 8 s, 4 live secrets, 10 plaintext copies; one token in `~/.claude.json` existed in 7 files because of automatic backups. | My own scan with [keyaudit](https://github.com/HeyAIpenguin/keyaudit) |
