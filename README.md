# MAGIA — public research compute laboratory

This **public** repository is an isolated laboratory for reproducible experiments
associated with the MAGIA research program. The authoritative development
repository (`Fioletibiel/mAGI`) is **private**.

## Publication boundary

**Do not mirror or push the private repository or its Git history here.**
Any source, protocol, logs, workflow output, artifacts or results committed or
uploaded here can be viewed or copied by third parties. Deleting files or
GitHub Actions artifacts later cannot retract copies or necessarily erase Git
history.

Only explicitly reviewed, intentionally publishable experiment subsets may be
committed. Never commit secrets, personal data, internal notes, proprietary
unreviewed algorithms, private checkout credentials or unpublished results
that must remain confidential.

GitHub Actions must be used only for legitimate development and testing of
the software and experiments **associated with this repository**, subject to
GitHub's usage limits and Terms. This is not an unrestricted computation
service. 

## Reproducibility and cleanup

- Freeze a preregistered experimental protocol in the private MAGIA repository
  **before** implementation. Keep the original code revision and expected
  metrics identifiable by SHA.
- For each released public experiment, pin public source and record the exact
  tested revision, environment, seeds, results, checksums, and scientific
  conclusion (including negative results) in the private authoritative record.
- Review every file and Actions output for public disclosure before pushing.
- Remove obsolete working files and public Actions artifacts **after private
  results are confirmed and verified**; understand that historical commits,
  forks, logs and third-party copies may still exist.
- Do not rewrite scientific outcomes or silently tune a frozen protocol.

## Current status

Public repository initialized. **No private MAGIA experimental source or
M2-P1 result has been published by this setup step.**

Official GitHub guidance:
- https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/removing-sensitive-data-from-a-repository
- https://docs.github.com/en/actions/how-tos/manage-workflow-runs/remove-workflow-artifacts
- https://docs.github.com/en/site-policy/github-terms/github-terms-for-additional-products-and-features
