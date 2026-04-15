# Secure DevSecOps App

This project demonstrates a secure CI pipeline using GitHub Actions.

## Features
- SAST (Semgrep)
- Dependency scanning (pip-audit)
- Secret scanning (Gitleaks)
- Container scanning (Trivy)
- SBOM generation (Syft)
- Artifact storage

## How it works
Pipeline runs on push and:
1. Scans code
2. Builds Docker image
3. Generates SBOM
4. Stores results as artifacts