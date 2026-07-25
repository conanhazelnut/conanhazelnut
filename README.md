### conanhazelnut

Small, local-first tools — mostly for people who live in a terminal.
做本機優先的小工具:裝完就能用,不上傳、不追蹤。

---

#### [wander](https://github.com/wander-dao/wander) · 天下行走

Turn your Claude Code token usage into a cultivation journey — a status bar line
and a CLI, entirely local.
把 Claude Code 的 token 用量化作一場修行 —— status bar 一行 + 一套指令,全在本機。

[![wander](https://raw.githubusercontent.com/wander-dao/wander/main/assets/readme/statusline.png)](https://github.com/wander-dao/wander)

```sh
# macOS
curl -fsSL https://raw.githubusercontent.com/wander-dao/wander/main/install.sh | bash
# Windows (PowerShell)
irm https://raw.githubusercontent.com/wander-dao/wander/main/install.ps1 | iex
```

#### [supa](https://github.com/conanhazelnut/supa)

Run multiple local Supabase stacks — one per project — on a single machine.
A thin manager over the official Supabase CLI; it decides *which* stacks run and
reads each project's live ports from its own config.

```sh
# macOS / Linux
curl -fsSL https://raw.githubusercontent.com/conanhazelnut/supa/main/install.sh | sh
# Windows (PowerShell)
irm https://raw.githubusercontent.com/conanhazelnut/supa/main/install.ps1 | iex
```

---

<sub>Both CLIs are single binaries (Deno-compiled), macOS + Windows, no runtime to
install. Found a problem? Issues are the fastest way to reach me.</sub>
