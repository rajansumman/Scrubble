Scrubble

Anti-Malware and Network Protection Service An investigation into effective forms of malware identification

Scrubble is a Python-based anti-malware prototype built as an A-level/NEA computer science investigation into how antivirus software actually works. Rather than treating "antivirus" as a black box, Scrubble implements three malware identification techniques independently — signature-based scanning, sandboxed behavioural analysis, and heuristic process monitoring — so each can be evaluated and compared on its own merits.

The project was born out of a simple observation: effective anti-malware software is often locked behind expensive subscriptions, leaving the most vulnerable users the least protected. Scrubble is an attempt at a free, transparent, locally-run alternative that explains what it's doing rather than hiding behind a black box.

⚠️ This is a student research/coursework project, not production security software. It has not been audited, hardened, or tested against real-world malware (see Safety & Disclaimer below). Do not rely on it to protect a real system.
