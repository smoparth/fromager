## What

<!-- Brief description of the change. -->

## Why

<!-- Link to issue (Closes #NNN) or explain the motivation. -->

## Testing

- [ ] `hatch run test:test` passes
- [ ] `hatch run lint:check` passes
- [ ] `hatch run mypy:check` passes
- [ ] New behavior has tests

<!-- For changes affecting build/bootstrap workflows, also run: hatch run e2e:run -->

## Standards

- [ ] Type annotations on all new/modified functions
- [ ] Docstrings on public APIs
- [ ] Conventional Commit format used (`feat:`, `fix:`, `refactor:`, etc.)
- [ ] No trailing whitespace; files end with newline

See [CONTRIBUTING.md](https://github.com/python-wheel-build/fromager/blob/main/CONTRIBUTING.md) for full guidelines.
