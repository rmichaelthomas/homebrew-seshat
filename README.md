# homebrew-seshat

Homebrew tap for [Seshat](https://github.com/rmichaelthomas/seshat-app) — govern what AI agents do on your machine.

## Install

```bash
brew tap rmichaelthomas/seshat
brew install seshat
```

Every install artifact — the source tarball and all 56 PyPI dependency
resources the formula pulls in — is pinned by SHA-256 in
[`Formula/seshat.rb`](Formula/seshat.rb). If GitHub or PyPI ever served a
different file at one of those URLs, `brew install` would fail rather
than silently install something else.

This doesn't make the formula signed — Homebrew has no formula-signing
mechanism — and installing it runs Ruby code with your user privileges,
the same as any Homebrew formula. Trust ultimately rests on who can push
to this tap's `main` branch.

## What is Seshat?

Seshat is a local environmental agent harness for AI coding agents. Write permissions in plain English, get tamper-proof receipts for every action.

→ [github.com/rmichaelthomas/seshat-app](https://github.com/rmichaelthomas/seshat-app)
→ [liminate.dev](https://liminate.dev)
