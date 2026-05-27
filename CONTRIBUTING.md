# Contributing to Awesome AI Storyboarding

Thanks for considering a contribution! This project is maintained by the team behind [STORYLINER](https://www.storyliner.online), an AI storyboard generator for film and ad pre-production.

## How to contribute

### Reporting bugs

Open an issue with:
- What you tried to do
- What happened
- What you expected
- Minimal reproduction (if applicable)

### Suggesting features

Open an issue tagged `enhancement`. We're particularly interested in:
- Use cases we haven't anticipated
- Integration patterns with other tools
- Performance improvements

### Submitting code

1. Fork the repo
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Make your changes
4. Add or update tests as needed
5. Run the existing tests to confirm nothing broke
6. Submit a pull request with a clear description

### Code style

Keep it simple and consistent with existing patterns. Specifically:
- Pure-stdlib when possible (avoid adding runtime dependencies)
- Clear function and variable names
- Comments only for non-obvious decisions
- One feature per PR

### What we won't accept

- Adding heavyweight runtime dependencies without strong justification
- Changes that break the public API without a clear migration path
- Code that doesn't have a clear use case from the issue tracker

## Code of conduct

Be respectful, focus on the work, assume good intent. The team behind this code uses it daily in production at [storyliner.online](https://www.storyliner.online) — we want it to be useful for other AI pre-production builders.

## Recognition

Contributors are listed in the repo. For significant contributions, we'll also credit you in the next Storyliner release notes.

## License

By contributing, you agree your contributions will be licensed under the project's MIT license.
