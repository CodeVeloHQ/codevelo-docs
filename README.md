# CodeVelo documentation

**Discover. Deliver. Operate.**

This repository contains public documentation for CodeVelo's services, platform
direction, engineering approach, and selected product concepts.

CodeVelo is a West Virginia engineering partner for web platforms, managed hosting,
commercial networks, structured cabling, and conference room AV. We connect software,
infrastructure, deployment, and ongoing operations under one accountable technical
partner.

## Documentation

- [Browse the documentation site](https://codevelohq.github.io/codevelo-docs/)
- [Platform overview](https://codevelohq.github.io/codevelo-docs/platform-overview/)
- [Product and capability catalog](https://codevelohq.github.io/codevelo-docs/product-catalog/)
- [Service capabilities](https://codevelohq.github.io/codevelo-docs/service-capabilities/)
- [Architecture principles](https://codevelohq.github.io/codevelo-docs/architecture-principles/)
- [Security and privacy](https://codevelohq.github.io/codevelo-docs/security-and-privacy/)
- [Public release status](https://codevelohq.github.io/codevelo-docs/release-status/)

## Scope

These documents explain CodeVelo at a public, product-oriented level. They intentionally
exclude production topology, privileged configuration, client information, credentials,
private operating procedures, and proprietary implementation details.

Product names and architectural roles describe the current CodeVelo platform direction.
They do not guarantee that every component is publicly available, separately licensed,
or offered as a standalone service.

Unless a repository includes an explicit license, publication on GitHub does not grant
permission to copy, modify, or redistribute CodeVelo material.

## Contact

- Website: [codevelo.dev](https://codevelo.dev)
- Email: [contact@codevelo.dev](mailto:contact@codevelo.dev)
- Discovery call: [codevelo.dev/book](https://codevelo.dev/book)

For suspected vulnerabilities, follow the [security policy](https://codevelohq.github.io/codevelo-docs/security-policy/)
rather than opening a public issue.

## Local preview

The documentation site is built with [MkDocs](https://www.mkdocs.org/) and the Material
theme. With Python 3 installed:

```shell
python -m venv .venv
.venv\Scripts\activate
python -m pip install --requirement requirements.txt
mkdocs serve
```

On macOS or Linux, activate the environment with `source .venv/bin/activate`. Open
`http://127.0.0.1:8000` to preview the site. Run `mkdocs build --strict` before
submitting a change.

Pushes to `main` are automatically built and deployed to GitHub Pages. Pull requests
run the same strict build without deploying.
