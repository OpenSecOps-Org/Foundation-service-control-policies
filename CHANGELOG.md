# Change Log

## v1.0.10
    * `README.md` gains the OpenSSF Best Practices Passing-level badge (project entry [bestpractices.dev/projects/12827](https://www.bestpractices.dev/projects/12827)).

## v1.0.9
    * Converted to OpenSecOps supply-chain framework: hash-pinned dependencies (`boto3==1.42.94`, `urllib3>=2.7.0`, `pyyaml>=6.0,<7.0`), signed releases via Sigstore (SBOM + evidence tarball + SLSA Build L1 provenance, each accompanied by a Sigstore `.bundle`), daily CVE scan, OpenSSF Scorecard, customer-side release verification via `scripts/deploy.py` (Installer v3.0.11+). README H1 also retitled from generic "README" to the component name. See `SECURITY.md`.

## v1.0.8
    * Enable auto-close workflow for external pull requests, enforcing the cathedral governance policy uniformly across all OpenSecOps repositories. Pull requests from non-team authors are closed automatically with a redirect comment pointing to the bug-report template, the GitHub Security Advisory flow, and the fork-under-MPL-2.0 path.

## v1.0.7
    * Updated GitHub remote references in publish.zsh script to use only OpenSecOps-Org, removed Delegat-AB

## v1.0.6
    * Updated GitHub organization name from CloudSecOps-Org to OpenSecOps-Org.
    * Updated references to CloudSecOps-Installer to Installer.

## v1.0.5
    * File paths corrected for the new name of the installer.

## v1.0.4
    * Updated LICENSE file to MPL 2.0.

## v1.0.3
    * Updated publish.zsh to support dual-remote publishing to CloudSecOps-Org repositories.

## v1.0.2
    * Upgraded to Python 3.12.
    * Added `.python-version` file for pyenv.

## v1.0.1
    * Refreshed scripts.

## v1.0.0
    * Initial release.
