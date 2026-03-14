# PR Security Agent

AI-powered Pull Request security reviewer.

PR Security Agent analyzes code changes in Pull Requests and detects potential security vulnerabilities before merge.

Part of the **AppSecAI** initiative.

---

## Overview

Security reviews are often slow, manual, and skipped under delivery pressure.

PR Security Agent automates security feedback directly in developer workflows by analyzing Pull Request diffs using AI.

The agent identifies common security risks and posts inline comments on Pull Requests.

---

## Features

* Detect injection vulnerabilities
* Identify hardcoded secrets
* Suggest secure code fixes
* Analyze only changed files in Pull Requests
* Post comments directly on GitHub PRs

---

## Architecture

Pull Request Event
↓
GitHub Webhook Trigger
↓
Fetch PR Diff / Changed Files
↓
AI Security Analysis
↓
Generate Findings
↓
Post Inline Comments to PR

---

## Example Finding

Potential SQL Injection detected.

User input is directly concatenated into a SQL query.

Recommendation: Use parameterized queries or prepared statements.

---

## Project Roadmap

Phase 1
AI vulnerability detection in Pull Requests

Phase 2
Secret detection and prompt injection scanning

Phase 3
AI-assisted threat modeling

---

## Security

If you discover a security vulnerability in this project, please report it responsibly.

Contact: [security@appsecai.xyz](mailto:security@appsecai.xyz)

---

## Contributing

Contributions and ideas are welcome.

Open an issue or submit a pull request.

---

## License

MIT License
