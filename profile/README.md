**MuTMS** (Multi-Tenant Management System) is a GPL 3.0-licensed suite of plugins for Moodle™ LMS, bringing multi-tenancy, structured learning programs, certifications, training credits, and more to standard Moodle installations. MuTMS adds features that many Moodle administrators and organisations need but are not available in standard Moodle. It is an independent open-source project, not affiliated with or endorsed by Moodle Pty Ltd.

All components work together as a coherent system but can also be used independently. They are all compatible with Moodle 4.5.x, 5.0.x, 5.1.x and 5.2.x.

Releases are synchronised with official Moodle releases, ensuring security fixes and new features are available without delay. Plugin version numbers follow Moodle's own versioning scheme. Documentation is available at [docs.mutms.org](https://docs.mutms.org/).

## Contributing
Contributions are welcome — bug reports, fixes, and improvements via GitHub Issues and pull requests.

Because MuTMS is standard Moodle plugin code published under GPL-3.0, any Moodle administrator, developer, or Moodle Partner familiar with the platform can provide support, maintenance, and customisation without any dependency on the MuTMS project itself.

For support options, see [mutms.org/#support](https://www.mutms.org/#support).

## Plugins

- [Multi-tenancy](https://github.com/mutms/moodle-tool_mutenancy) — Partition a single Moodle instance into isolated tenants, each with their own users, courses, and settings.
- [Programs](https://github.com/mutms/moodle-tool_muprog) — Define structured learning paths, manage enrolments, track progress, and automate completion across a program as a whole.
- [Certifications](https://github.com/mutms/moodle-tool_mucertify) — Issue and manage certifications tied to program completion, with expiry and renewal cycle support.
- [Training credits](https://github.com/mutms/moodle-tool_mutrain) — Allocate credit budgets and gate access to learning activities based on available credits.
- [Supervisors & teams](https://github.com/mutms/moodle-tool_murelation) — Model learner–supervisor relationships so managers can monitor team progress and compliance.
- [Custom home pages](https://github.com/mutms/moodle-tool_muhome) — Configure cohort- and tenant-specific dashboards and landing pages.
- [Interactive book](https://github.com/mutms/moodle-mod_mubook) — A structured, page-based content module for course materials.
- [Compromised password blocking](https://github.com/mutms/moodle-tool_mupwned) — Blocks known breached passwords via HaveIBeenPwned, using k-Anonymity so passwords never leave Moodle.
- [Privileged sessions](https://github.com/mutms/moodle-tool_musudo) — Sudo-style privilege escalation for admins, reducing risk during routine work.
- [Log-in-as via Incognito](https://github.com/mutms/moodle-tool_muloginas) — Opens impersonated sessions in a new Incognito window, keeping the admin session active.

## Roadmap

- Universal catalogue
- Improved cohorts
- Seminar activity
- Approval workflows
- Core security hardening

## Moodle Marketplace

Great news — MuTMS is now officially recognised by Moodle HQ as directly competing with Moodle Workplace, which under clause 2.1 of the [Moodle Marketplace Terms](https://moodle.atlassian.net/wiki/external/NzZlYWExYTIzZmU5NDJiYzgwODJjNmU1MjhiNDQ0YjQ) is exactly why it cannot be listed there.

We consider that the best review we have ever had: a GPL-3.0 community project delivering what a commercial product is sold for. Nothing changes for you — install straight from the repositories above and see [docs.mutms.org](https://docs.mutms.org/).
