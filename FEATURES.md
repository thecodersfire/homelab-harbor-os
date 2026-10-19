# Built-in features for homelab-harbor-os

Purpose: home server administration

1. **prepare study and research files** — run homelab-harbor-os-workspace. It creates ~/Documents/homelab-harbor-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run homelab-harbor-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/homelab-harbor-os-session-plans/.
3. **check study and source readiness** — run homelab-harbor-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/homelab-harbor-os-workspace features/homelab-harbor-os-plan features/homelab-harbor-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for home server administration:

1. **DB Browser for SQLite** — org.sqlitebrowser.sqlitebrowser
2. **GNOME Builder** — org.gnome.Builder
3. **KeePassXC** — org.keepassxc.KeePassXC

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for home server administration:

1. **GNOME Maps** — look up places and plan routes (org.gnome.Maps)
2. **GNOME Weather** — check local weather conditions (org.gnome.Weather)
3. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)
4. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
5. **LibreOffice** — create reports and spreadsheets (org.libreoffice.LibreOffice)
6. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
7. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
8. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
9. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
10. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
