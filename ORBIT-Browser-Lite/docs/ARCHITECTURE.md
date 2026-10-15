# ORBIT architecture

Browser UI -> same-origin local Python API (`127.0.0.1:8765`) -> allowlisted installed CLI. No arbitrary command endpoint; subprocess uses `shell=False`, bounded body/output/runtime, and target validation. The server is loopback-only and intentionally not suitable for public deployment without authentication, CSRF defenses, and an isolated worker. MiroFish and FreeLLMAPI remain separate services.
