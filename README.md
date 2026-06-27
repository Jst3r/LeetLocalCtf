# 1337 Local CTF - Reverse Engineering
- Date: [27 - 06 - 2026]

This repository contains the reverse engineering challenges I authored for the 1337 Local CTF competition.

## Challenges:

| Challenge Name | Description / Topic |
| :--- | :--- |
| **`big_brother`** | simulation of a privilege escalation via traffic-control `pedit` COW vulnerability (CVE-2026-46331). |
| **`dirty_ptrace`** | User-space simulation of Samsung Exynos driver Use-After-Free via dirty ptrace (CVE-2024-44068). |
| **`glitched_colosseum`** | Game Boy Advance (.gba) ROM reverse engineering. |
| **`minishell`** | Custom shell binary analysis. |
| **`moulcyber`** | Process injection detection bait with modular linear equation checks. |
| **`videur`** | Custom VM / interpreter reversing inside a Linux initramfs cpio archive. |
| **`zrbaan`** | Multi-process IPC with timing-sensitive metronome anti-debugging gates. |

## More info:

Each directory contains the distributed challenge files. To run or analyze them locally:
1. Navigate to the specific challenge directory.
2. Ensure you have the appropriate architectures and libraries set up (e.g., standard Linux tooling, GBA emulators for `glitched_colosseum`).
3. Make binaries executable if necessary: `chmod +x <binary>`



## notes:
- For the CVE-based challenges (`big_brother` and `dirty_ptrace`), i designed the challenges to simulate the core mechanics as much as possible.

---
*Authored by Jst3r*
