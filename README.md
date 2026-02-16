# Claude dev container template

Simple docker container and compose set up, to have claude-code running in a
container.

project repo should be cloned into `workplace`, but suggest ignoring the `docs`,
such as in this `./workspace/.git/info/exclude`:

```
# git ls-files --others --exclude-from=.git/info/exclude

# Claude
docs/
CLAUDE.md
.claude/
```
