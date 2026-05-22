# gitlab-project-scan

Security scanning for GitLab projects.

This repository is a demo project that showcases how to enable and configure GitLab's built-in security scanning capabilities within your projects. It demonstrates integrating automated security checks directly into CI/CD pipelines to identify vulnerabilities and security risks early in the development lifecycle. Important is how to bring all scanning in one stage by overriding default "test" stage of Gitlab.

Included security scanning features:

* **SAST (Static Application Security Testing)** – Detects security vulnerabilities in source code.
* **Dependency Scanning** – Identifies known vulnerabilities in project dependencies and third-party libraries.
* **Secret Detection** – Scans for accidentally exposed credentials, API keys, tokens, and sensitive information.
* **Container Scanning** – Checks container images for known vulnerabilities and insecure packages.

The goal of this repository is to provide a simple reference implementation that teams can use to understand, enable, and adopt GitLab-native security scanning across their projects.
