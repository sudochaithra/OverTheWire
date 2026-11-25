# OverTheWire ₍⑅ᐢ..ᐢ₎
<!-- 
Don't Stop Believin' ᯓ★
Welcome to the vault. If you're reading this, you a real one. Congrats. 
-->
This repo is my personal dump of exploit scripts, custom crypto-breakers, and dirty one-liners used to tear through [OverTheWire](https://overthewire.org) wargames. 

---

## Objectives & Progress ᯓ★

| Wargame | Focus | Status | Gists |
| :--- | :--- | :--- | :--- |
| **[Bandit](https://overthewire.orgwargames/bandit/)** | Linux Recon & Basic Ops | `COMPLETED` | read man pages, automated the rest. [View Gist](https://gist.github.com/sudochaithra/adb9bdd7d30dbe2e18f0ada1e1a5d43c) |
| **[Natas](https://overthewire.orgwargames/natas/)** | Server-Side Web & SQLi | `IN PROGRESS` | Spoofing sessions and pulling files off sloppy servers. [View Gist](https://github.com) |
| **[Krypton](https://overthewire.orgwargames/krypton/)** | Signals & Cryptography | `IN PROGRESS` | Cracking substitution ciphers while humming Journey. [View Gist](https://github.com) |
| **[Narnia](https://overthewire.orgwargames/narnia/)** | Memory & Buffer Overflows | `QUEUED` | Warm-up before the heavy lifting. [View Gist](https://github.com) |
| **[Vortex](https://overthewire.orgwargames/vortex/)** | Mixed Exploitation | `LOCKED` | Raw sockets, C, and assembly. The real playground. [View Gist](https://github.com) |

---

## Tools Loadout ᯓ★

If you're going in, don't go in blind. Here is what you need in a terminal:

* **OS:** Custom stripped-down Linux build (best for no bloat, maximum speed)
* **Languages:** Python 3 (for brute-forcing whatever annoys me) & Bash (for quick lines)
* **Web Toys:** `curl`, Burp Suite, and a healthy disrespect for client-side validation
* **Binary / Crypto:** `gdb`, `objdump`, `openssl`, and way too much caffeine

---

## Rules of Engagement ᯓ★

1. **No walkthroughs.** If you look up the flag, you might as well hand your keyboard to someone.
2. **Automate everything.** If a task takes more than 30 seconds by hand, write a 10-line Python script.
3. **Never lose the keys.** Keep your SSH passwords locked in a local encrypted vault.

---

## Quick Links & Gist Dump ᯓ★

* [Master SSH Connection Script](https://github.com) — *Because typing port numbers manually is for amateurs.*
* [Frequency Analysis Helper (Python)](https://github.com) — *Built specifically for Krypton.*
* [Blind SQLi Brute-Forcer](https://github.com) — *For when Natas gets stubborn.*

---

*Disclaimer: Everything in here is strictly for educational wargaming. If you use my scripts to poke around servers you don't own, you're on your own—I'm not bailing you out.*
