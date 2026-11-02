# Hey, I'm Jatin.

I work in security, usually somewhere between “that looks odd” and “let’s figure out why.” A quick look has a habit of turning into a bug report or an open-source patch.

## Some recent open-source work

- **[parsedmarc](https://github.com/domainaware/parsedmarc/security/advisories/GHSA-7grx-mj6g-qxmc):** A closer look at the legacy failure-report parser uncovered a high-severity CPU-exhaustion issue. The maintainers credited me as the reporter and shipped their fix in `11.0.4`.
- **[rex-core](https://github.com/rapid7/rex-core/pull/46) + [Metasploit](https://github.com/rapid7/metasploit-framework/pull/22002):** Two cleanup paths were holding onto state that should have been gone. The changes landed in `rex-core 0.1.37` and Metasploit Framework `6.5.8`.
- **[osquery](https://github.com/osquery/osquery):** Three corners of the project needed attention: [`chrome_extensions` state](https://github.com/osquery/osquery/pull/9170), [custom-flag thread safety](https://github.com/osquery/osquery/pull/9195), and [Linux Audit argument reconstruction](https://github.com/osquery/osquery/pull/9208). All three changes are included in `5.24.1`, which GitHub marks as a prerelease.
- **[Keycloak](https://github.com/keycloak/keycloak/pull/53721):** At the client-scope boundary, role visibility needed a clearer line. The merged change includes regression tests for legacy RBAC and FGAP v2.

The rest of my open-source work is in [my pull requests](https://github.com/search?q=is%3Apr+author%3Amjatin2007&type=pullrequests).

## Writing

A few pieces about the places where security decisions meet everyday work:

- [Infrastructure as Code: An IaC Guide to Cloud Security](https://www.darkreading.com/cloud-security/infrastructure-code-iac-guide-cloud-security), *Dark Reading*
- [Rethinking Our Approach to SIEM: Stop Collecting Everything](https://www.isc2.org/Insights/2026/08/rethinking-our-approach-to-siem), *ISC2 Insights*
- [How to Focus Vendor Security Reviews on the Risks that Matter](https://www.secureworld.io/industry-news/focus-vendor-security-reviews-risks), *SecureWorld*

More: [Dark Reading](https://www.darkreading.com/author/jatin-mannepalli) · [SecureWorld](https://www.secureworld.io/industry-news/author/jatin-mannepalli) · [LinkedIn](https://www.linkedin.com/in/jatin-mannepalli-7a7b05a5/)
