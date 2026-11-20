# Accessibility

Musa CAD's application, websites, documentation, and contribution process should be
usable by people with different access needs. Accessibility reports and improvements
are welcome across the organization.

## Scope and priorities

- **Desktop application:** see the [application accessibility statement](https://github.com/MusaCAD/MusaCAD/blob/main/ACCESSIBILITY.md)
  for supported platforms, keyboard features, and known limitations.
- **Website and wiki:** prioritize semantic headings and controls, visible keyboard
  focus, text alternatives for meaningful images, readable contrast, zoom and reflow,
  and reduced-motion preferences. WCAG 2.2 Level AA is a design target for web content,
  not a claim that every page meets the standard.
- **Fabrication tools:** command-line operation does not establish accessibility of
  generated PDFs. Screen-reader usability and PDF tagging have not been verified.
- **GitHub:** issues and pull requests accept text descriptions. Screenshots and video
  are optional, and email is available if GitHub's interface is a barrier.

The wiki includes automated contrast, keyboard, layout, and accessibility checks in
`npm run verify`. Automated results do not replace testing with assistive technology.
There is no verified list of browser and screen-reader combinations for all projects.

## Report a barrier

Open an accessibility report in the affected repository or email
[pranay@weberq.in](mailto:pranay@weberq.in). Include the page or task, what prevented
progress, the expected result, and any relevant operating system, browser, assistive
technology, or display settings. Share only details you are comfortable making public;
a diagnosis or medical history is not needed.

Reports are reviewed alongside other usability issues, with attention to barriers
that prevent completing a task. How soon a problem can be fixed depends on the work
needed and the time available.
