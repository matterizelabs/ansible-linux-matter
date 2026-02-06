# Contributing

Thanks for considering a contribution.

## Ways To Contribute

- Report issues and request features
- Improve documentation
- Add or refine roles and tasks
- Improve CI and testing

## Development Setup

- Use the Nix dev shell or Python tools:

```bash
nix develop
# or
uv venv
uv sync --extra dev
```

## Linting

```bash
yamllint .
ansible-lint
```

## Pull Requests

- Keep PRs focused and small when possible.
- Include a clear summary and testing notes.
- Ensure lint passes before requesting review.

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
