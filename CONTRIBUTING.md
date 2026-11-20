# Contributing to Musa CAD

Bug reports, documentation fixes, testing, accessibility feedback, and code changes
are welcome. Please follow the [Code of Conduct](https://github.com/MusaCAD/.github/blob/main/CODE_OF_CONDUCT.md).

## Choose the repository

| Project | Contributions and local checks |
| --- | --- |
| [MusaCAD](https://github.com/MusaCAD/MusaCAD) | Desktop application, CAD commands, file formats, and packaging. Start with the [application contribution guide](https://github.com/MusaCAD/MusaCAD/blob/main/CONTRIBUTING.md). |
| [wiki](https://github.com/MusaCAD/wiki) | User guides, tutorials, and command reference at [wiki.musacad.org](https://wiki.musacad.org/). Follow its README; `npm run verify` checks content, builds the site, and runs its audits. |
| [MusaCAD-Website](https://github.com/MusaCAD/MusaCAD-Website) | Pages at [musacad.org](https://musacad.org/). Follow its README and run `npm run build`; check changed pages on narrow and wide screens and with the keyboard. |
| [fabrication_pipeline](https://github.com/MusaCAD/fabrication_pipeline) | FreeCAD-to-drawing tools. Follow its README and run `python3 -m unittest discover -s tests -v`; inspect generated sheets when changing drawing layout. |
| [.github](https://github.com/MusaCAD/.github) | Organization profile and shared community files. Check Markdown links and issue-form YAML. |

Use each repository's README for prerequisites and setup. Repository-specific
contribution instructions take precedence over this shared guide.

## Report a problem

Search existing issues first, then open an issue in the affected repository.
Describe the steps, actual result, expected result, and version or commit. For a
website problem, include the page URL and browser. Screenshots, logs, or a small
reproducible example help, but remove personal information and confidential content.

Report vulnerabilities through the [security policy](https://github.com/MusaCAD/.github/blob/main/SECURITY.md).
For private conduct concerns, email [pranay@weberq.in](mailto:pranay@weberq.in).

## Send a change

1. Discuss large features or changes in direction in an issue before implementing them.
   Small fixes can go straight to a pull request.
2. Fork the relevant repository and use a branch named for the change.
3. Keep the change focused. Follow the surrounding code and documentation style,
   preserve license notices, and use material you have permission to contribute.
4. Run the relevant checks above and add regression coverage where behavior changes.
   Explain any checks that could not be run.
5. Describe the problem, resulting behavior, and validation in the pull request.
   Link related issues; use `Fixes #...` only when the issue is fully resolved.

Use concise commit and pull request titles that describe the change. Each repository
keeps its own license; contributing does not change the license of another project.
