# Commit Message Convention

This repository follows the [Conventional Commits](https://www.conventionalcommits.org/) specification.

## Format

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

## Types

- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation only changes
- `style`: Changes that do not affect the meaning of the code (white-space, formatting, etc)
- `refactor`: A code change that neither fixes a bug nor adds a feature
- `perf`: A code change that improves performance
- `test`: Adding missing tests or correcting existing tests
- `chore`: Changes to the build process or auxiliary tools

## Rules

- **All commit messages must be written in English**
- Use the imperative, present tense: "Change" not "changed" nor "changes"
- **Capitalize the first letter of the description**
- No period (.) at the end of the description

## Examples

```
feat: Add user authentication
fix: Resolve login validation error
docs: Update installation guide in README
refactor: Simplify error handling logic
test: Add unit tests for auth module
```

## Breaking Changes

Breaking changes should be indicated by `!` after the type/scope:

```
feat!: Remove deprecated API endpoints
```