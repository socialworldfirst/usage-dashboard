# usage-dashboard

Personal Claude Code usage dashboard for Steven Chen.

Password-gated (AES-GCM, password: `z`). Rebuilt nightly at 00:05 Asia/Shanghai via launchd `com.worldfirst.usage-report`. Weekly digest at Fri 18:00.

Live: https://socialworldfirst.github.io/usage-dashboard/

Source: `~/.local/bin/wf/usage_report.py` — pure Python, no Claude API calls. Reads `~/.claude/projects/-Users-steven-Documents-Claude/**/*.jsonl` directly.

