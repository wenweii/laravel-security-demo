# Laravel Security CI | GitHub Free public demonstration

This repository is a **small PHP/Composer acceptance-test fixture**, not a fully installed Laravel application.
It demonstrates the same Composer Audit, Gitleaks and Semgrep security gate that can be
applied to a **real Laravel project with a genuine composer.lock**.

1. Replace `wenweii` in `.github/workflows/security-ci.yml`.
2. Open a clean PR against `main`, and wait for CI to finish.
3. Only after the first successful CI, add `security-gate` as a required check
   under Settings > Branches > Add classic branch protection rule.
4. Follow the accompanying Traditional Chinese beginner's manual for TC-01...TC-07.

Do not publish real company code, credentials, or logs in this public demonstration.
