# Phonlaphat (Tan) - SAP Business One add-on developer

นักพัฒนา SAP Business One add-on

## About

I build SAP Business One add-ons in C# with the UI API and DI API, backed by SAP HANA.
I learned the craft by shipping production add-ons on a live client project during a 2026 apprenticeship.
My working method is a team of Claude Code agents run under a written operating model. I am open to developer roles.

## What I build

| Repository | What it is | Stack |
|---|---|---|
| `sapb1-payment-run-approval` | SAP B1 10.0 add-on: a maker / checker / approver chain that gates a payment run's bank-file export. SAP-free core with 1990 unit tests that need no B1 client. | C#, .NET Framework 4.6.1, UI API + DI API, HANA, MSTest |
| `sapb1-asset-duplicate-addon` | SAP B1 10.0 add-on: one-click duplicate of a fixed-asset master record with automatic code increment and post-write verification. | C#, .NET Framework 4.6.1, UI API + DI API, WinForms |
| `claude-01-harness` | A portable Claude Code operating model: one dispatcher agent, specialist squads, and rules learned from measured incidents. | PowerShell 5.1, Markdown, Claude Code |
| `portfolio` | Landing page describing the projects above in more depth. | Markdown |
| `coop-presentation-2569` | Co-op project presentation (1 October 2026) on the asset duplicate add-on. | PowerShell, Markdown |

These repositories are private for now. Access is available on request.

## How I work

- **One dispatcher.** A single agent triages each request, routes it to the narrowest specialist, and reports one answer.
- **Verified by execution.** A result counts only when a QA step has run it and quoted the output, not when the writer says it passed.
- **Every release proven from the artefact.** A release is tested from the package that ships, not from the source tree it was meant to come from.

## Stack

- C# / .NET Framework 4.6.1
- SAP Business One UI API and DI API (forms, events, user-defined tables, fields and objects)
- SAP HANA SQL and SQLScript
- Crystal Reports for SAP Business One
- Visual Studio 2015, MSBuild 14.0, MSTest
- PowerShell 5.1
- Claude Code multi-agent workflows

## Education

**Rajamangala University of Technology Isan (RMUTI)** - Information Systems, Faculty of Business Administration.
Co-op (สหกิจศึกษา) 2026: SAP Business One add-on development; project presented on 1 October 2026.

## Contact

Through GitHub: open an issue on this repository.
