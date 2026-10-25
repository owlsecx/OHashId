# 🦉 OHashId

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OPass-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OHashId** — Hash Identifier & Cracker

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OHashId — Hash Identifier & Cracker. It provides hash identifier — ranked candidate detection by length, charset and structural format for MD5, SHA-1, SHA-224/256/384/512, SHA-3 family, NTLM (MD4), MySQL (old/new), bcrypt, sha256crypt / sha512crypt, md5crypt, LM, CRC-32, Django PBKDF2 and argon2 — each with a confidence score, hashcat -m mode and John format name. Operators can export results (including machine-readable formats) and gate CI with severity thresholds where supported.

---

## ✨ Features

- Hash identifier — ranked candidate detection by length, charset and structural format for MD5, SHA-1, SHA-224/256/384/512, SHA-3 family, NTLM (MD4), MySQL (old/new), bcrypt, sha256crypt / sha512crypt, md5crypt, LM, CRC-3
- Dictionary cracker for stdlib-supported fast hashes (md5, sha1, sha224, sha256, sha384, sha512, ntlm when MD4 is present, and the crypt families md5crypt / sha256crypt / sha512crypt implemented in pure Python, plus MySQL
- Salt support — salt+pass, pass+salt, and crypt-style salt auto-extracted from the stored hash.
- Rule / mangling engine — case variants, leet, digit and year suffixes, prefixes and reversal, all bounded by a configurable cap so runs stay predictable.
- Built-in ~500-word starter wordlist for offline runs with no external list.
- Benchmark — hashes-per-second estimate per algorithm.

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OHashId                                     # interactive menu
./OHashId --json -o report.json
./OHashId --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
