# Contribute to StackAnvil

Start in the repository that owns the behavior you want to change.
Its local contribution guide and build configuration take precedence over these organization defaults.

## Choose the right place

- For setup questions, read [the support guide](SUPPORT.md).
- For security concerns, read [the private reporting instructions](SECURITY.md).
- For a defect, search existing issues and include a minimal reproduction.
- For a larger API, architecture, or dependency change, discuss the design before implementation.
- For documentation, identify the reader's task and check instructions against the applicable release.

## Prepare and verify a change

1. Read the target repository's README and applicable contributor instructions.
2. Use the tool versions and dependency lockfiles declared by that repository.
3. Keep each pull request focused on one coherent change.
4. Add focused tests for new behavior when practical.
5. Run the target project's documented checks. State any checks that could not run and why.
6. Update user instructions when a command, API, permission, or default changes.

Keep generated files under their owning tool. Do not copy secrets or production data into examples.
Avoid unrelated formatting and dependency updates. Keep commit hooks enabled.

## Open a pull request

Target the repository's default branch. Explain the problem, resulting behavior, and validation evidence.
Link related issues. Include screenshots for visible changes and migration notes for compatibility changes.

Use Conventional Commits: `type(scope): description`. Use a meaningful scope, or omit it.
Keep the subject concise and imperative. Explain non-obvious decisions in the commit body.
Respond to review with concrete changes or evidence. Maintainers decide when the change is ready to merge.

## Community

Be respectful, specific, and patient in reviews and support conversations.
Read [the code of conduct](CODE_OF_CONDUCT.md).

These defaults follow [GitHub's community file precedence](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).
Repository templates override organization templates. Licenses remain specific to each repository.
