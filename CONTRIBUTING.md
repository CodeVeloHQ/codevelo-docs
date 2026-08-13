# Contributing

Documentation corrections and clarifications are welcome.

Before submitting a change:

1. Confirm that the information is intended for public release.
2. Do not include client information, private infrastructure details, credentials,
   internal URLs, or proprietary operating procedures.
3. Keep changes focused and explain why they improve accuracy or usability.
4. Link supporting public sources when a change depends on an external standard.

For substantial additions, open a public documentation issue before preparing a pull
request. Security concerns must follow the
[security policy](https://codevelohq.github.io/codevelo-docs/security-policy/).

## Preview documentation changes

Install the pinned documentation dependencies and start the local preview server:

```shell
python -m venv .venv
.venv\Scripts\activate
python -m pip install --requirement requirements.txt
mkdocs serve
```

On macOS or Linux, activate the environment with `source .venv/bin/activate`. Before
submitting a pull request, verify the production build succeeds:

```shell
mkdocs build --strict
```
