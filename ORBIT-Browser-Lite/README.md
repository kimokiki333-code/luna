# ORBIT Browser Lite v0.1

A lightweight, static, browser-only edition based on the ORBIT dashboard already in the user's library. It is designed for browsing tool documentation and organizing a research workflow without installing Python or running a local backend.

## Open
Open `site/index.html` in a browser, or upload the `site` folder to a static host.

## Honest limitations
- This edition does not execute Sherlock, Maigret, Amass, ZoomEye, or other local command-line tools.
- The service-status controls intentionally explain this limitation instead of claiming a tool is running.
- Source cards are reference links only; they do not mean those connectors are installed or integrated.
- A hosted webpage cannot access the visitor's PC-local services as if they were hosted remotely.
- No API keys or credentials are included.

## Other edition
Use the separate `ORBIT-Local-OSINT-v0.3.zip` if you want a loopback-only Python helper that can invoke allowlisted local CLI tools after they have been installed and configured. It requires Python 3 and has not been tested on the user's PC.
