# Built-in features for homelab-harbor-os

Purpose: home server administration

1. **prepare study and research files** — run homelab-harbor-os-workspace. It creates ~/Documents/homelab-harbor-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run homelab-harbor-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/homelab-harbor-os-session-plans/.
3. **check study and source readiness** — run homelab-harbor-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/homelab-harbor-os-workspace features/homelab-harbor-os-plan features/homelab-harbor-os-check "$HOME/.local/bin/"
